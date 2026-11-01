---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "PresentationLoadOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

def remove_slide_background():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.slides[0].image_fill_format.background_image = None
        watermarker.save("./output.pptx")
```

## __init__ {#password}

指定されたパスワードで PresentationLoadOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, password):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| password | `str` | 暗号化されたコンテンツを開くためのパスワードです。 |

### 例

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### 関連項目
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
