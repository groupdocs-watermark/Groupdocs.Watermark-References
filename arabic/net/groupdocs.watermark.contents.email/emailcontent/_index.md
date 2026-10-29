---
title: "EmailContent"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل رسالة بريد إلكتروني."
type: docs
weight: 360
url: /ar/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

يمثل رسالة بريد إلكتروني.

```csharp
public sealed class EmailContent : Content
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | يحصل على مجموعة جميع المرفقات لرسالة البريد الإلكتروني. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | يحصل على مجموعة مستلمي النسخة المخفية (BCC) لرسالة البريد الإلكتروني. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | يحصل أو يعيّن تمثيل النص العادي لجسم الرسالة. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | يحصل على نوع جسم رسالة البريد الإلكتروني. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | يحصل على مجموعة مستلمي النسخة الكربونية (CC) لرسالة البريد الإلكتروني. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | يحصل على مجموعة جميع الكائنات المدمجة في رسالة البريد الإلكتروني. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | يحصل على عنوان المرسل لرسالة البريد الإلكتروني. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | يحصل أو يعيّن تمثيل الـ HTML لجسم الرسالة. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | يحصل أو يعيّن موضوع رسالة البريد الإلكتروني. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | يحصل على مجموعة مستلمي رسالة البريد الإلكتروني. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | يتخلص من النسخة الحالية. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### ملاحظات

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### انظر أيضاً

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
