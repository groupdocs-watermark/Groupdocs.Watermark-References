---
title: "Класс EmailLoadOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры загрузки документа для сообщения электронной почты."
type: docs
url: /ru/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Представляет параметры загрузки документа для сообщения электронной почты.

Тип EmailLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Инициализирует новый экземпляр класса [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Тип файла, указывающий его формат (например, docx, pdf, xlsx и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Семейство форматов документа, указывающее его тип (например, Image, Pdf, Spreadsheet и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Пароль для открытия зашифрованного документа. (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Получает значение по умолчанию для класса. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # манипулировать содержимым электронной почты здесь
    watermarker.save("./output.msg")
```

### См. также
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
