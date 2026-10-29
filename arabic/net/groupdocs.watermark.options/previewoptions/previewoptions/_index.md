---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "ينشئ مثيلاً جديداً للفئة PreviewOptionsgroupdocs.watermark.options/previewoptions مما يؤدي إلى إغلاق تدفق الإخراج."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

ينشئ مثيلاً جديداً للفئة [`PreviewOptions`](../../previewoptions) مما يؤدي إلى إغلاق تدفق الإخراج.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |

### انظر أيضاً

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

ينشئ مثيلاً جديداً للفئة [`PreviewOptions`](../../previewoptions) مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام الإضافي.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |
| releasePageStream | ReleasePageStream | يُخطر بأن إنشاء معاينة الصفحة قد انتهى ويحصل على تدفق الإخراج. |

### انظر أيضاً

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
