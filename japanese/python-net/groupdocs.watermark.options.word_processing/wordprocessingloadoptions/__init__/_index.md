---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "WordProcessingLoadOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#password}

指定されたパスワードで WordProcessingLoadOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, password):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| password | `str` | 暗号化されたコンテンツを開くためのパスワードです。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # 透かし操作を実行する
    pass
```

### 関連項目
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
