---
title: "License"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 1680
url: /ar/net/groupdocs.watermark/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public sealed class License
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license)() | ينشئ مثيلًا جديدًا من الفئة [`License`](../license). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | يرخص المكوّن. |

### ملاحظات

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### أمثلة

يوضح هذا المثال كيفية إعداد الترخيص من الملف المحلي.

```csharp
// تهيئة فئة License.
License license = new License();

// حدد المسار إلى ملف .lic.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### انظر أيضاً

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
