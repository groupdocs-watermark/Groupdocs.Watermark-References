---
title: "protect 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "保护文档免受更改并设置保护密码。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

保护文档免受更改并设置保护密码。

要使文档内容可编辑，请使用适当的方法添加水印，并使用 `WordProcessingLockType.allow_only_form_fields` 或 `WordProcessingLockType.read_only_with_editable_content` 参数。

```python
def protect(self, protection_type, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | 指定文档的保护类型。 |
| password | `str` | 用于保护文档的密码。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")
```

### 另请参见
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
