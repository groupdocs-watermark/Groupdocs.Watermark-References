---
title: "Добавить текстовые водяные знаки"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "В этой статье показано, как добавить текстовый водяной знак к документу и сохранить результат с помощью GroupDocs.Watermark для Python через .NET."
type: docs
url: /ru/python-net/guides/add-text/
is_root: false
weight: 40
---


Одной из основных возможностей GroupDocs.Watermark является добавление текстовых водяных знаков в документы. Вы можете добавлять водяные знаки в документы или изображения как из локального пути, так и из потока. Полный список поддерживаемых форматов см. в разделе [Поддерживаемые форматы документов](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Чтобы добавить текстовый водяной знак, выполните следующие шаги:

1. Откройте документ, передав его путь (или поток) классу [Watermarker](https://reference.groupdocs.com/watermark/python-net/), используя блок `with`, чтобы документ освобождался автоматически.
2. Создайте [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) с нужным текстом и [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Оформите водяной знак — например, задайте `foreground_color` и выравнивание.
4. Вызовите `add()`, чтобы применить водяной знак, и `save()`, чтобы записать результат.

{{< tabs "code-example-add-text">}}
{{< tab "add_text_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Создайте текстовый водяной знак и оформите его
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Запустите программу. Новый документ с водяным знаком появится по указанному пути.

## What's next

GroupDocs.Watermark предоставляет множество дополнительных возможностей для текстовых водяных знаков — фон и передний цвет, пользовательские шрифты, непрозрачность, вращение, мозаика и абсолютное или относительное позиционирование. См. раздел [Добавление текстовых водяных знаков](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) в расширенном руководстве.
