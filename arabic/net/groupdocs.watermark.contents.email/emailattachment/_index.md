---
title: "EmailAttachment"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل ملفًا مرفقًا برسالة بريد إلكتروني."
type: docs
weight: 320
url: /ar/net/groupdocs.watermark.contents.email/emailattachment/
---
## EmailAttachment class

يمثل ملفًا مرفقًا برسالة بريد إلكتروني.

```csharp
public class EmailAttachment : EmailAttachmentBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | يسترجع أو يعيّن محتوى الملف المرفق. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | يحصل على معرف المحتوى لهذا [`EmailAttachmentBase`](../emailattachmentbase). |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | يحصل على نوع الوسائط لهذا [`EmailAttachmentBase`](../emailattachmentbase). |
| [Name](../../groupdocs.watermark.contents.email/emailattachment/name) { get; set; } | يحصل أو يضبط اسم الملف المرفق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | يحمّل محتوىً من الملف المرفق. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | يحمّل محتوىً من الملف المرفق مع خيارات التحميل المحددة. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | يحمّل محتوىً من الملف المرفق مع خيارات التحميل المحددة والإعدادات. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | يسترجع المعلومات حول مستند مخزن في الملف المرفق. |

### انظر أيضاً

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
