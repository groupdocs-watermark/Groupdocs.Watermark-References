---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "使用後に出力ストリームを閉じる新しい PreviewOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

使用後に出力ストリームを閉じる新しい PreviewOptions インスタンスを初期化します。

```python
def __init__(self, create_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – 特定のページプレビュー用のストリームを作成します。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 各ページをレンダリングするための書き込み可能なファイルストリームを提供します
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

## __init__ {#create_page_stream-release_page_stream}

さらに使用できるように出力ストリームをクライアントに返す新しい PreviewOptions インスタンスを初期化します。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 特定のページプレビュー用のストリームを作成する Callable。ページ番号（`int`）を受け取り、書き込み可能なストリーム（`io.RawIOBase`）を返す必要があります。 |
| release_page_stream | `ReleasePageStream` | ページプレビュー生成が完了したときに呼び出され、出力ストリームを提供する Callable。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 各ページをレンダリングするための書き込み可能なファイルストリームを提供します
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### 関連項目
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
