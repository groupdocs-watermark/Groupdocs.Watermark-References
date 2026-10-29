---
title: "SizingType"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحدد كيفية حساب حجم العلامة المائية."
type: docs
weight: 3300
url: /ar/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

يحدد كيفية حساب حجم العلامة المائية.

```csharp
public enum SizingType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | يجب أن يتم ضبط حجم العلامة المائية تلقائيًا وفقًا لمحتواها. |
| Absolute | `1` | يجب أن يكون حجم العلامة المائية بدقة [`Width`](../../groupdocs.watermark/watermark/width) و[`Height`](../../groupdocs.watermark/watermark/height). |
| ScaleToParentDimensions | `2` | يجب أن يتم تحجيم العلامة المائية نسبةً إلى أبعاد العنصر الأصل باستخدام [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) المحدد. |
| ScaleToParentArea | `3` | يجب أن يتم تحجيم العلامة المائية نسبةً إلى مساحة العنصر الأصل باستخدام [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) المحدد. |

### انظر أيضاً

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
