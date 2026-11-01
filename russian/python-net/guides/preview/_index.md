---
title: "Предпросмотр документа"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Создавайте изображения предварительного просмотра (PNG/JPG/BMP) страниц документа с помощью GroupDocs.Watermark для Python через .NET."
type: docs
url: /ru/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark может рендерить страницы документов в виде изображений, чтобы вы могли показывать миниатюры страниц, не открывая документ полностью в просмотрщике. Вы управляете рендерингом с помощью обратного вызова `create_page_stream`, который предоставляет поток записи файла для каждой страницы — библиотека записывает изображение страницы в него и закрывает его за вас.

## Generate a document preview

Установите [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) с обратным вызовом `create_page_stream`, выберите `preview_format` и укажите `page_numbers` для рендеринга.

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Предоставьте поток записываемого файла для каждой страницы, которую нужно отобразить
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это двухстраничный примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Изображения страниц записываются в текущий каталог — один PNG на каждую запрошенную страницу. Используйте `PreviewFormats.JPEG` или `PreviewFormats.BMP` для других форматов и задайте `options.width` / `options.height`, чтобы контролировать размер рендеринга.

Библиотека закрывает каждый файл, возвращённый `create_page_stream`, после записи страницы. Чтобы обработать страницу сразу после её готовности, передайте второй обратный вызов: `PreviewOptions(create_page_stream, release_page_stream)` вызывает `release_page_stream(page_number, stream)` с объектом, возвращённым `create_page_stream` для этой страницы, после того как всё изображение окажется в нём. Также работает вариант с одним аргументом `release_page_stream(page_number)`. `create_page_stream` может возвращать и `io.BytesIO`: он остаётся открытым и удерживает изображение страницы до момента, когда `release_page_stream` его получит.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
