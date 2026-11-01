---
title: "Класс SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры при добавлении водяного знака в верхний/нижний колонтитул Spreadsheet."
type: docs
url: /ru/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
is_root: false
weight: 100
---


## SpreadsheetWatermarkHeaderFooterOptions class

Представляет параметры при добавлении водяного знака в верхний/нижний колонтитул Spreadsheet.

Узнать больше:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Тип SpreadsheetWatermarkHeaderFooterOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/__init__/) | Инициализирует новый экземпляр класса [`SpreadsheetWatermarkHeaderFooterOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheet_index/) | Индекс листа, к которому будет добавлен водяной знак. |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkHeaderFooterOptions
from groupdocs.watermark.watermarks import Font, TextWatermark
load_options = SpreadsheetLoadOptions()
with Watermarker("./test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 14))
    options = SpreadsheetWatermarkHeaderFooterOptions()
    options.worksheet_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### См. также
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
