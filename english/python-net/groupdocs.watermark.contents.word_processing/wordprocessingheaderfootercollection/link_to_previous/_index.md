---
title: link_to_previous method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1010
---


## link_to_previous {#is_link_to_previous}

Links or unlinks all headers and footers to the corresponding headers and footers in the previous section.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| is_link_to_previous | `bool` | True to link the headers and footers to the previous section; False to unlink them. |

### Example

```python
for i in range(1, content.sections.count):
    content.sections[i].headers_footers.link_to_previous(True)
```

### See Also
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
