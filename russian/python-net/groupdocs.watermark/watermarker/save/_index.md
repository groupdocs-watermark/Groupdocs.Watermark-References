---
title: "save метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Сохраняет данные документа в базовый поток."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Сохраняет данные документа в базовый поток.

Узнайте больше о сохранении документов: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

Сохраняет документ в указанное файловое расположение.

Узнайте больше о сохранении документов: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу, в который сохраняются данные документа. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

Сохраняет документ в указанный поток.

Узнайте больше о сохранении документов по адресу https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток, в который сохраняются данные документа. |

### Пример

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` теперь содержит сохранённые байты PDF.
```

## save {#options}

Сохраняет данные документа в базовый поток, используя параметры сохранения.

Узнайте больше о сохранении документов.

```python
def save(self, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `SaveOptions` | Дополнительные параметры, используемые при сохранении документа. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

Сохраняет документ в указанное файловое расположение, используя параметры сохранения.

Узнайте больше о сохранении документов: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу, в который сохраняются данные документа. |
| options | `SaveOptions` | Дополнительные параметры, используемые при сохранении документа. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

Сохраняет документ в указанный поток, используя параметры сохранения.

Узнайте больше о сохранении документов в документации GroupDocs.

```python
def save(self, document, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток, в который сохраняются данные документа. |
| options | `SaveOptions` | Дополнительные параметры, используемые при сохранении документа. |

### Пример

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # stream теперь содержит сохранённые данные PDF.
        # например, записать в файл
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
