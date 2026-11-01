---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "WordProcessingWatermarkPagesOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

WordProcessingWatermarkPagesOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# 特定のページに透かしを適用するためのオプションを作成します
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### 関連項目
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
