---
title: "EmailContent 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示电子邮件消息。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

表示电子邮件消息。

了解更多：
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

EmailContent 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 释放当前实例。（继承自 [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)） |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 根据指定的搜索条件查找图像。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 指定的对象中进行。(inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 根据指定的搜索条件查找可能的水印。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 列出的对象上执行。(inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | 电子邮件消息的所有附件集合。 |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | 电子邮件消息的密件抄送（BCC）收件人集合。 |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | 消息正文的纯文本表示。 |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | 电子邮件消息正文的类型。 |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | 电子邮件消息的抄送（CC）收件人集合。 |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | 电子邮件消息的所有嵌入对象集合。 |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | 电子邮件消息的发件人地址。 |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | 消息正文的 HTML 表示。 |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | 电子邮件消息的主题。 |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | 电子邮件消息的收件人集合。 |

### 示例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # 添加附件
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### 另请参见
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
