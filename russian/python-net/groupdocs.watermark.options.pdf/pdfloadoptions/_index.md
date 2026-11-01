---
title: "Класс PdfLoadOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры загрузки документа для PDF-документа."
type: docs
url: /ru/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/
is_root: false
weight: 30
---


## PdfLoadOptions class

Представляет параметры загрузки документа для PDF-документа.

Тип PdfLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/) | Инициализирует новый экземпляр класса [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/#password) | Инициализирует новый экземпляр класса [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) с указанным паролем. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Тип файла, указывающий его формат (например, docx, pdf, xlsx и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Семейство форматов документа, указывающее его тип (например, Image, Pdf, Spreadsheet и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Пароль для открытия зашифрованного документа. (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/default/) | Получает значение по умолчанию для класса. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    # выполнять операции над watermarker
    pass
```

### См. также
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
