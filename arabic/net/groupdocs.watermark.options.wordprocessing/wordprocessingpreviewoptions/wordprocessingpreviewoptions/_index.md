---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يقوم بإنشاء نسخة جديدة من الفئة WordProcessingPreviewOptionsgroupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions مما يؤدي إلى إغلاق تدفق الإخراج."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions(CreatePageStream) {#constructor}

يقوم بإنشاء نسخة جديدة من الفئة [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) مما يؤدي إلى إغلاق تدفق الإخراج.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

---

## WordProcessingPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

يقوم بإنشاء نسخة جديدة من الفئة [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |
| releasePageStream | ReleasePageStream | يُخطر بأن إنشاء معاينة الصفحة قد انتهى ويحصل على تدفق الإخراج. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
