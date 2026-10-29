---
title: "FromExtension"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يقوم بربط امتداد الملف بنوع الملف."
type: docs
weight: 590
url: /ar/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

يقوم بربط امتداد الملف بنوع الملف.

```csharp
public static FileType FromExtension(string extension)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| امتداد | String | امتداد الملف (بما في ذلك النقطة "."). |

### قيمة الإرجاع

عندما يكون نوع الملف مدعومًا يُعيده، وإلا يُعيد نوع الملف الافتراضي [`Unknown`](../unknown).

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما تكون *extension* فارغة أو سلسلة نصية فارغة. |

### انظر أيضاً

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
