---
title: "generate_preview метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Создаёт изображения предварительного просмотра для документа."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Создаёт изображения предварительного просмотра для документа.

```python
def generate_preview(self, preview_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Дополнительные параметры, используемые при генерации изображений предварительного просмотра. |

### Пример

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

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
