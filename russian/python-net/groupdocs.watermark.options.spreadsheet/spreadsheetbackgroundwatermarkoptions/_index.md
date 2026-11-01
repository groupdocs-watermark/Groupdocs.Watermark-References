---
title: "Класс SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры при добавлении водяного знака в качестве фона листа Spreadsheet."
type: docs
url: /ru/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

Представляет параметры при добавлении водяного знака в качестве фона листа Spreadsheet.

Узнайте больше: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Тип SpreadsheetBackgroundWatermarkOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | Инициализирует новый экземпляр класса [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | Желаемая высота фонового изображения в пикселях. |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | Желаемая ширина фонового изображения в пикселях. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | Индекс листа, к которому будет добавлен водяной знак. |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetBackgroundWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker(r"C:\Documents\test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36))

    options = SpreadsheetBackgroundWatermarkOptions()
    options.worksheet_index = -1  # default
    options.background_width = 800
    options.background_height = 600

    watermarker.add(watermark, options)
    watermarker.save()
```

### См. также
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
