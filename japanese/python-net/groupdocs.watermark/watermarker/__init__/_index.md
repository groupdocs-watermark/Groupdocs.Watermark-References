---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定されたドキュメントパスで新しい Watermarker インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

指定されたドキュメントパスで新しい Watermarker インスタンスを初期化します。

ドキュメントの読み込みについて詳しく見る: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | ドキュメントを読み込むファイルパス。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

```python
from groupdocs.watermark import Watermarker

# ドキュメントを読み込む。
watermarker = Watermarker("./document.pdf")
# Watermarker メソッドを使用して透かしを追加、検索、または削除する。

# ドキュメントを保存する。
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

指定されたドキュメントパスとロードオプションで新しい Watermarker インスタンスを初期化します。

ドキュメントの読み込みについて詳しく見る: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | ドキュメントを読み込むファイルパス。 |
| options | `LoadOptions` | ドキュメントを読み込む際に使用する追加オプション。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # 暗号化された PDF に対して操作を実行する
    pass
```

## __init__ {#file_path-settings}

指定されたドキュメントパスと設定で Watermarker を初期化します。

ドキュメントの読み込みについて詳しく見る: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | ドキュメントを読み込むファイルパス。 |
| settings | `WatermarkerSettings` | 読み込んだドキュメントを操作する際に使用する追加設定。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

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
    # watermarkerで作業する、例として透かしの検索や削除
    pass
```

## __init__ {#file_path-options-settings}

指定されたドキュメントパス、ロードオプション、設定で新しい Watermarker インスタンスを初期化します。

ドキュメントの読み込みについて詳しく見る: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | ドキュメントを読み込むファイルパス。 |
| options | `LoadOptions` | ドキュメントを読み込む際に使用する追加オプション。 |
| settings | `WatermarkerSettings` | 読み込んだドキュメントを操作する際に使用する追加設定。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

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

指定されたストリームで Watermarker クラスの新しいインスタンスを初期化します。

ドキュメントの読み込みについて詳しく見る: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントを読み込むためのストリームです。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Watermarker のメソッドを使用して、透かしを追加、検索、または削除します。
            watermarker.save(output_stream)
```

## __init__ {#document-options}

指定されたストリームとロードオプションで新しい Watermarker インスタンスを初期化します。

ドキュメントの読み込みについて詳しく知る。

```python
def __init__(self, document, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントを読み込むためのストリームです。 |
| options | `LoadOptions` | ドキュメントを読み込む際に使用する追加オプション。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # watermarkerで操作を実行する
        pass
```

## __init__ {#document-settings}

指定されたストリームと設定で新しい Watermarker インスタンスを初期化します。

ドキュメントの読み込みについて詳しく知る。

```python
def __init__(self, document, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントを読み込むためのストリームです。 |
| settings | `WatermarkerSettings` | 読み込んだドキュメントを操作する際に使用する追加設定。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

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
            # 見つかった透かしを操作する
```

## __init__ {#document-options-settings}

指定されたストリーム、ロードオプション、設定で [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) クラスの新しいインスタンスを初期化します。

https://docs.groupdocs.com/display/watermarknet/Loading+documents のドキュメント読み込みについて詳しく知る。

```python
def __init__(self, document, options, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントを読み込むためのストリームです。 |
| options | `LoadOptions` | ドキュメントを読み込む際に使用する追加オプション。 |
| settings | `WatermarkerSettings` | 読み込んだドキュメントを操作する際に使用する追加設定。 |

| 例外が発生 | 説明 |
| :- | :- |
| `UnsupportedFileTypeException` | 指定されたドキュメントタイプはサポートされていません。 |
| `InvalidPasswordException` | 指定されたパスワードが正しくありません。 |

### 例

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

### 関連項目
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
