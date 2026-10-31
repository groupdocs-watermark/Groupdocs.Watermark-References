---
title: "link_to_previous 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "将所有页眉和页脚链接或取消链接到前一节中的相应页眉和页脚。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

将所有页眉和页脚链接或取消链接到前一节中的相应页眉和页脚。

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| is_link_to_previous | `bool` | True 表示将页眉和页脚链接到前一个章节；False 表示取消链接。 |

### 示例

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

### 另请参见
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
