---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يقوم بإنشاء نسخة جديدة من الفئة PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions مما يؤدي إلى إغلاق تدفق الإخراج."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

يقوم بإنشاء نسخة جديدة من الفئة [`PdfPreviewOptions`](../../pdfpreviewoptions) مما يؤدي إلى إغلاق تدفق الإخراج.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

يقوم بإنشاء نسخة جديدة من الفئة [`PdfPreviewOptions`](../../pdfpreviewoptions) مما يجعل تدفق الإخراج يُعاد إلى العميل للاستخدام لاحقًا.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |
| releasePageStream | ReleasePageStream | يُخطر بأن إنشاء معاينة الصفحة قد انتهى ويحصل على تدفق الإخراج. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
