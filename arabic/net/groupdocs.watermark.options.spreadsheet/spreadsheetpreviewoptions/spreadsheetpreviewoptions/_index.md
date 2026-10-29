---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يُنشئ مثيلًا جديدًا من الفئة SpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions مما يؤدي إلى إغلاق تدفق الإخراج."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) مما يؤدي إلى إغلاق تدفق الإخراج.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

يُنشئ مثيلًا جديدًا من الفئة [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |
| releasePageStream | ReleasePageStream | يُخطر بأن إنشاء معاينة الصفحة قد انتهى ويحصل على تدفق الإخراج. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
