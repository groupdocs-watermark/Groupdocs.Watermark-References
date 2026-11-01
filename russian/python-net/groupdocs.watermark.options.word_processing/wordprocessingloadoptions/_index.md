---
title: "Класс WordProcessingLoadOptions"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет параметры загрузки документа для документа Word."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Представляет параметры загрузки документа для документа Word.

Тип WordProcessingLoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Инициализирует новый экземпляр класса [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Инициализирует новый экземпляр класса WordProcessingLoadOptions с указанным паролем. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Тип файла, указывающий его формат (например, docx, pdf, xlsx и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Семейство форматов документа, указывающее его тип (например, Image, Pdf, Spreadsheet и т.д.). (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Пароль для открытия зашифрованного документа. (наследуется от [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Поля
| Поле | Описание |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Получает значение по умолчанию для класса. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # выполнять операции над содержимым, например, защищать, снимать защиту, добавлять водяные знаки
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### См. также
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
