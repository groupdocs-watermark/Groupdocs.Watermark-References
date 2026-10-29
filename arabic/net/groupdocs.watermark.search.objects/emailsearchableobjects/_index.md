---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحدد العلامات التي تمثل كائنات رسائل البريد الإلكتروني التي يجب تضمينها في بحث العلامة المائية."
type: docs
weight: 2520
url: /ar/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

يحدد العلامات التي تمثل كائنات رسائل البريد الإلكتروني التي يجب تضمينها في بحث العلامة المائية.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | يحدد عدم وجود كائنات بحث. |
| Subject | `1` | البحث في موضوع الرسالة. |
| PlainTextBody | `2` | البحث في نص الرسالة العادي. |
| HtmlBody | `4` | البحث في نص الرسالة بصيغة HTML. |
| AttachedImages | `8` | البحث في الصور المرفقة. |
| EmbeddedImages | `10` | البحث في الصور المدمجة. |
| All | `1F` | البحث في جميع كائنات البريد الإلكتروني. |

### انظر أيضاً

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
