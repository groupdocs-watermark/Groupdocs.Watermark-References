---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يعرف الطرق المطلوبة للحصول على معلومات المستند الأساسية."
type: docs
weight: 70
url: /ar/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

يعرف الطرق المطلوبة للحصول على معلومات المستند الأساسية.

```csharp
public interface IDocumentInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | يحصل على وصف تنسيق الملف. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | يحصل على قيمة تشير إلى ما إذا كان المستند مشفرًا ويتطلب كلمة مرور للفتح. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | يحصل على إجمالي عدد الصفحات. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | يحصل على مجموعة أوصاف صفحات المستند. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | يحصل على حجم المستند بالبايت. |

### ملاحظات

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### أمثلة

المثال التالي يوضح كيفية استرجاع معلومات المستند العامة باستخدام [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### انظر أيضاً

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
