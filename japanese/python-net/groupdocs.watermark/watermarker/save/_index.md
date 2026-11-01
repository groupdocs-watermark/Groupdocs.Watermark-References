---
title: "save メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ドキュメントデータを基になるストリームに保存します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

ドキュメントデータを基になるストリームに保存します。

ドキュメントの保存について詳しくは: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### 例

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

ドキュメントを指定されたファイル場所に保存します。

ドキュメントの保存について詳しくは: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | ドキュメントデータを保存するファイルパス。 |

### 例

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

ドキュメントを指定されたストリームに保存します。

ドキュメントの保存について詳しくは https://docs.groupdocs.com/display/watermarknet/Saving+documents にて。

```python
def save(self, document):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントデータを保存するストリーム。 |

### 例

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
    # `stream` は現在、保存された PDF バイト列を含んでいます
```

## save {#options}

保存オプションを使用してドキュメントデータを基になるストリームに保存します。

ドキュメントの保存について詳しくは。

```python
def save(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | `SaveOptions` | ドキュメントを保存する際に使用する追加オプション。 |

### 例

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

保存オプションを使用してドキュメントを指定されたファイル場所に保存します。

ドキュメントの保存について詳しくは: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | ドキュメントデータを保存するファイルパス。 |
| options | `SaveOptions` | ドキュメントを保存する際に使用する追加オプション。 |

### 例

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

指定されたストリームに保存オプションを使用してドキュメントを保存します。

GroupDocs のドキュメントでドキュメントの保存について詳しくは。

```python
def save(self, document, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| document | `io.RawIOBase` | ドキュメントデータを保存するストリーム。 |
| options | `SaveOptions` | ドキュメントを保存する際に使用する追加オプション。 |

### 例

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
        # ストリームは現在、保存された PDF データを含んでいます
        # 例：ファイルに書き込む
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### 関連項目
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
