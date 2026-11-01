---
title: "Привет, мир!"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Быстро начните работу с GroupDocs.Watermark для Python через .NET, создав и запустив простой пример."
type: docs
url: /ru/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Пример "Hello, World!", как правило, является первым шагом при изучении GroupDocs.Watermark для Python через .NET. Он служит простым тестом, подтверждающим правильную настройку вашей среды разработки и корректную работу библиотеки.

## Overview
GroupDocs.Watermark для Python через .NET позволяет добавлять, искать и удалять водяные знаки в различных форматах документов. Широкий спектр [поддерживаемых форматов](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) делает его универсальным для разных сценариев использования.

## How to add a watermark
Следующие шаги демонстрируют, как добавить текстовый водяной знак в документ с использованием GroupDocs.Watermark for Python via .NET:

1. Импортируйте необходимые классы `groupdocs.watermark`.
2. Откройте [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) с путем к образцу документа.
3. Создайте [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) с нужным текстом и шрифтом и оформите его.
4. Примените водяной знак с помощью `add()`.
5. Сохраните результат.

## Complete example
Пример ниже добавляет полупрозрачный, диагональный текстовый водяной знак "Hello, Watermark!" и сохраняет результат:

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Откройте документ, добавьте один текстовый водяной знак и сохраните результат
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Водяной знак сохраняется обратно в том же формате PDF, что и `output.pdf`. Чтобы нанести его на другой документ, измените путь входного файла и расширение выходного — GroupDocs.Watermark сохраняет в формате исходного документа.

## Additional resources
Эта демонстрация ссылается на GroupDocs.Watermark for Python via .NET [примеры кода](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/).
