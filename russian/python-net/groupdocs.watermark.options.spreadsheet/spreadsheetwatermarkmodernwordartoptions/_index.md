---
title: "Класс SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры при добавлении современного водяного знака в виде Word Art в лист Spreadsheet."
type: docs
url: /ru/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
is_root: false
weight: 110
---


## SpreadsheetWatermarkModernWordArtOptions class

Представляет параметры при добавлении современного водяного знака в виде Word Art в лист Spreadsheet.

Узнать больше:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Тип SpreadsheetWatermarkModernWordArtOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/) | Инициализирует новый экземпляр класса [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheet_index/) | Индекс листа, к которому будет добавлен водяной знак. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | Описательный (альтернативный) текст, который будет связан с фигурой. (унаследовано от [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | Свойство указывает, запрещено ли редактирование фигуры в Excel. (унаследовано от [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | Имя фигуры. (унаследовано от [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Получает значение по умолчанию для класса. (наследуется от [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkModernWordArtOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker("./spreadsheet.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    options = SpreadsheetWatermarkModernWordArtOptions()
    options.worksheet_index = 0
    options.is_locked = False
    watermarker.add(watermark, options)
    watermarker.save("./output.xlsx")
```

### См. также
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
