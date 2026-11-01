---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定されたファイルパスで新しい ImageWatermark インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

指定されたファイルパスで新しい ImageWatermark インスタンスを初期化します。

```python
def __init__(self, file_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | 透かしとして使用される画像へのパス。 |

### 例

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

提供された画像ストリームで新しい ImageWatermark を初期化します。

```python
def __init__(self, stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 透かしとして使用される画像を含むストリーム。 |

### 例

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

with open("logo.png", "rb") as f:
    image_data = f.read()

with Watermarker("sample.docx") as watermarker:
    with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("watermarked.docx")
```

### 関連項目
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
