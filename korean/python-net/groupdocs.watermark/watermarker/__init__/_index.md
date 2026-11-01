---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 문서 경로로 새로운 Watermarker 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

지정된 문서 경로로 새로운 Watermarker 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보기: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 문서를 로드할 파일 경로. |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

```python
from groupdocs.watermark import Watermarker

# 문서를 로드합니다.
watermarker = Watermarker("./document.pdf")
# Watermarker 메서드를 사용하여 워터마크를 추가, 검색 또는 제거하십시오.

# 문서를 저장합니다.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

지정된 문서 경로와 로드 옵션으로 새로운 Watermarker 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보기: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 문서를 로드할 파일 경로. |
| options | `LoadOptions` | 문서를 로드할 때 사용할 추가 옵션. |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # 암호화된 PDF에 대한 작업 수행
    pass
```

## __init__ {#file_path-settings}

지정된 문서 경로와 설정으로 Watermarker를 초기화합니다.

문서 로드에 대해 자세히 알아보기: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 문서를 로드할 파일 경로. |
| settings | `WatermarkerSettings` | 로드된 문서를 작업할 때 사용할 추가 설정. |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

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
    # watermarker와 작업하기, 예를 들어 워터마크를 검색하거나 제거합니다
    pass
```

## __init__ {#file_path-options-settings}

지정된 문서 경로, 로드 옵션 및 설정으로 새로운 Watermarker 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보기: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 문서를 로드할 파일 경로. |
| options | `LoadOptions` | 문서를 로드할 때 사용할 추가 옵션. |
| settings | `WatermarkerSettings` | 로드된 문서를 작업할 때 사용할 추가 설정. |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

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

지정된 스트림으로 Watermarker 클래스의 새로운 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보기: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서를 로드할 스트림 |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Watermarker의 메서드를 사용하여 워터마크를 추가, 검색 또는 제거합니다
            watermarker.save(output_stream)
```

## __init__ {#document-options}

지정된 스트림과 로드 옵션으로 새로운 Watermarker 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요

```python
def __init__(self, document, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서를 로드할 스트림 |
| options | `LoadOptions` | 문서를 로드할 때 사용할 추가 옵션. |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # watermarker와 작업 수행
        pass
```

## __init__ {#document-settings}

지정된 스트림과 설정으로 새로운 Watermarker 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요

```python
def __init__(self, document, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서를 로드할 스트림 |
| settings | `WatermarkerSettings` | 로드된 문서를 작업할 때 사용할 추가 설정. |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

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
            # 찾은 워터마크와 작업하기
```

## __init__ {#document-options-settings}

지정된 스트림, 로드 옵션 및 설정으로 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) 클래스의 새로운 인스턴스를 초기화합니다.

https://docs.groupdocs.com/display/watermarknet/Loading+documents에서 문서 로드에 대해 자세히 알아보세요

```python
def __init__(self, document, options, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서를 로드할 스트림 |
| options | `LoadOptions` | 문서를 로드할 때 사용할 추가 옵션. |
| settings | `WatermarkerSettings` | 로드된 문서를 작업할 때 사용할 추가 설정. |

| 예외 | 설명 |
| :- | :- |
| `UnsupportedFileTypeException` | 제공된 문서 유형은 지원되지 않습니다. |
| `InvalidPasswordException` | 제공된 비밀번호가 올바르지 않습니다. |

### 예시

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

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
