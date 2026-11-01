---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр Watermarker с указанным путём к документу."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Инициализирует новый экземпляр Watermarker с указанным путём к документу.

Узнайте больше о загрузке документов: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу, из которого загружается документ. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker

# Загрузить документ.
watermarker = Watermarker("./document.pdf")
# Используйте методы Watermarker для добавления, поиска или удаления водяных знаков.

# Сохранить документ.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Инициализирует новый экземпляр Watermarker с указанным путём к документу и параметрами загрузки.

Узнайте больше о загрузке документов: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу, из которого загружается документ. |
| options | `LoadOptions` | Дополнительные параметры, используемые при загрузке документа. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # выполнять операции над зашифрованным PDF
    pass
```

## __init__ {#file_path-settings}

Инициализирует Watermarker с указанным путём к документу и настройками.

Узнайте больше о загрузке документов: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу, из которого загружается документ. |
| settings | `WatermarkerSettings` | Дополнительные настройки, используемые при работе с загруженным документом. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
                     | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS
                  | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    # работать с watermarker, например, искать или удалять водяные знаки
    pass
```

## __init__ {#file_path-options-settings}

Инициализирует новый экземпляр Watermarker с указанным путём к документу, параметрами загрузки и настройками.

Узнайте больше о загрузке документов: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу, из которого загружается документ. |
| options | `LoadOptions` | Дополнительные параметры, используемые при загрузке документа. |
| settings | `WatermarkerSettings` | Дополнительные настройки, используемые при работе с загруженным документом. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.search_criteria import TextSearchCriteria
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects

def search_email():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        email_searchable_objects=(
            EmailSearchableObjects.Subject
            | EmailSearchableObjects.HtmlBody
            | EmailSearchableObjects.PlainTextBody
        )
    )
    load_options = EmailLoadOptions()
    with Watermarker("./test.msg", load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save()
```

## __init__ {#document}

Инициализирует новый экземпляр класса Watermarker с указанным потоком.

Узнайте больше о загрузке документов: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток для загрузки документа. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Используйте методы Watermarker для добавления, поиска или удаления водяных знаков.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Инициализирует новый экземпляр Watermarker с указанным потоком и параметрами загрузки.

Узнайте больше о загрузке документов.

```python
def __init__(self, document, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток для загрузки документа. |
| options | `LoadOptions` | Дополнительные параметры, используемые при загрузке документа. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # выполнять операции с watermarker
        pass
```

## __init__ {#document-settings}

Инициализирует новый экземпляр Watermarker с указанным потоком и настройками.

Узнайте больше о загрузке документов.

```python
def __init__(self, document, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток для загрузки документа. |
| settings | `WatermarkerSettings` | Дополнительные настройки, используемые при работе с загруженным документом. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

for file_path in ["./document1.pdf", "./document2.docx"]:
    with open(file_path, "rb") as stream:
        with Watermarker(stream, settings) as watermarker:
            watermarks = watermarker.search()
            # работать с найденными водяными знаками
```

## __init__ {#document-options-settings}

Инициализирует новый экземпляр класса [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) с указанным потоком, параметрами загрузки и настройками.

Узнайте больше о загрузке документов по адресу https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток для загрузки документа. |
| options | `LoadOptions` | Дополнительные параметры, используемые при загрузке документа. |
| settings | `WatermarkerSettings` | Дополнительные настройки, используемые при работе с загруженным документом. |

| Вызывает | Описание |
| :- | :- |
| `UnsupportedFileTypeException` | Указанный тип документа не поддерживается. |
| `InvalidPasswordException` | Указанный пароль неверен. |

### Пример

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    email_searchable_objects=(
        EmailSearchableObjects.Subject
        | EmailSearchableObjects.HtmlBody
        | EmailSearchableObjects.PlainTextBody
    )
)

load_options = EmailLoadOptions()
with open("./test.msg", "rb") as stream:
    with Watermarker(stream, load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save("./output.msg")
```

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
