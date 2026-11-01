---
title: "Класс SpreadsheetLoadOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры загрузки документа для документа Spreadsheet."
type: docs
url: /ru/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

Представляет параметры загрузки документа для документа Spreadsheet.

Тип SpreadsheetLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | Инициализирует новый экземпляр класса [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | Инициализирует новый экземпляр класса [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) с указанным паролем. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Тип файла, указывающий его формат (например, docx, pdf, xlsx и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Семейство форматов документа, указывающее его тип (например, Image, Pdf, Spreadsheet и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Пароль для открытия зашифрованного документа. (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | Получает значение по умолчанию для класса. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # выполните операции с водяным знаком здесь
    pass
```

### См. также
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
