---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحدد العلامات التي تمثل كائنات محتوى PDF التي يجب تضمينها في بحث العلامة المائية."
type: docs
weight: 2530
url: /ar/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

يحدد العلامات التي تمثل كائنات محتوى PDF التي يجب تضمينها في بحث العلامة المائية.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | يحدد عدم وجود كائنات بحث. |
| XObjects | `1` | البحث في XObjects. |
| Artifacts | `2` | البحث في القطع الأثرية. |
| Annotations | `4` | البحث في التعليقات التوضيحية. |
| Text | `8` | البحث في نص المحتوى. |
| Hyperlinks | `10` | البحث في الروابط التشعبية. |
| AttachedImages | `20` | البحث في الصور المرفقة. |
| Vector | `40` | البحث في المشغلات. |
| All | `7F` | البحث في جميع كائنات المحتوى. |

### انظر أيضاً

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
