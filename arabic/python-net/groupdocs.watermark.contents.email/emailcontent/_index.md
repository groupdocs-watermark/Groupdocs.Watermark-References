---
title: "فئة EmailContent"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل رسالة بريد إلكتروني."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

يمثل رسالة بريد إلكتروني.

اعرف المزيد:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

يعرض نوع EmailContent الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | يتخلص من المثيل الحالي. (موروث من [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | يبحث عن الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم البحث على الكائنات المدرجة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | مجموعة جميع المرفقات في رسالة البريد الإلكتروني. |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | مجموعة مستلمي BCC (نسخة كربونية مخفية) في رسالة البريد الإلكتروني. |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | تمثيل النص العادي لمحتوى الرسالة. |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | نوع محتوى رسالة البريد الإلكتروني. |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | مجموعة مستلمي CC (نسخة كربونية) في رسالة البريد الإلكتروني. |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | مجموعة جميع الكائنات المضمنة في رسالة البريد الإلكتروني. |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | عنوان المرسل في رسالة البريد الإلكتروني. |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | تمثيل HTML لمحتوى الرسالة. |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | موضوع رسالة البريد الإلكتروني. |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | مجموعة مستلمي رسالة البريد الإلكتروني. |

### مثال

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # إضافة مرفق
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### انظر أيضًا
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
