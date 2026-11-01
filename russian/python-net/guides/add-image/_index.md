---
title: "Добавить изображения водяных знаков"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "В этой статье показано, как добавить изображение водяного знака в документ и сохранить результат с помощью GroupDocs.Watermark для Python через .NET."
type: docs
url: /ru/python-net/guides/add-image/
is_root: false
weight: 50
---


Одна из основных функций GroupDocs.Watermark — добавление изображений водяных знаков в документы. Вы можете добавлять водяные знаки в документы или изображения из локального пути, а также из потока. Для полного списка поддерживаемых форматов см. [Поддерживаемые форматы документов](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Чтобы добавить изображение водяного знака, выполните следующие шаги:

1. Откройте документ, передав его путь (или поток) классу [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).
2. Создайте [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) из файла изображения водяного знака (или из потока).
3. Расположите водяной знак — например, установите `horizontal_alignment`, `vertical_alignment` и `opacity`.
4. Вызовите `add()`, чтобы применить водяной знак, и `save()`, чтобы записать результат.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Создайте изображение водяного знака из файла логотипа и разместите его по центру
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` и `logo.png` являются примерными файлами, используемыми в этом примере. Скачайте [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) и [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark предлагает больше возможностей для изображений водяных знаков — загрузка из потоков, масштабирование, мозаика и абсолютное или относительное позиционирование. См. [Добавление изображений водяных знаков](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) в расширенном руководстве.
