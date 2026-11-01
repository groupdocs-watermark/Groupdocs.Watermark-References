---
title: "link_to_previous メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "前のセクションの対応するヘッダーとフッターにすべてのヘッダーとフッターをリンクまたはリンク解除します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

前のセクションの対応するヘッダーとフッターにすべてのヘッダーとフッターをリンクまたはリンク解除します。

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| is_link_to_previous | `bool` | True はヘッダーとフッターを前のセクションにリンクし、False はリンクを解除します。 |

### 例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
import groupdocs.watermark.contents.word_processing as wp

load_options = WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content()
    for i in range(1, content.sections.count):
        content.sections[i].headers_footers.link_to_previous(True)
    watermarker.save("output.docx")
```

### 関連項目
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
