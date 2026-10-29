---
title: "PageMarginType"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحصل على أو يضبط هوامش صفحة pdf التي ستُستخدم أثناء إضافة العلامة المائية."
type: docs
weight: 20
url: /ar/net/groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype/
---
## PdfContent.PageMarginType property

يحصل على أو يضبط هوامش صفحة pdf التي ستُستخدم أثناء إضافة العلامة المائية.

```csharp
public PdfPageMarginType PageMarginType { get; set; }
```

### Property Value

هوامش صفحة PDF التي سيتم استخدامها أثناء إضافة العلامة المائية.

### ملاحظات

هذه الخاصية تعمل فقط عندما يتم تعيين [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) إلى true. إذا كان [`ConsiderParentMargins`](../../../groupdocs.watermark/watermark/considerparentmargins) false، يتم استخدام CropBox في PDF كمنطقة للعلامة المائية.

القيمة الافتراضية هي TrimBox.

### انظر أيضاً

* enum [PdfPageMarginType](../../pdfpagemargintype)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
