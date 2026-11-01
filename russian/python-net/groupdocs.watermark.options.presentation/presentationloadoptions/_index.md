---
title: "Класс PresentationLoadOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры загрузки документа для документа Presentation."
type: docs
url: /ru/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Представляет параметры загрузки документа для документа Presentation.

Тип PresentationLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Инициализирует новый экземпляр класса [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Инициализирует новый экземпляр класса PresentationLoadOptions с указанным паролем. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Тип файла, указывающий его формат (например, docx, pdf, xlsx и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Семейство форматов документа, указывающее его тип (например, Image, Pdf, Spreadsheet и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Пароль для открытия зашифрованного документа. (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Получает значение по умолчанию для класса. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # работать с документом
    pass
```

### См. также
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
