---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "ينشئ مثيلاً جديدًا لفئة DiagramPreviewOptionsgroupdocs.watermark.options.diagram/diagrampreviewoptions مما يؤدي إلى إغلاق تدفق الإخراج."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/diagrampreviewoptions/
---
## DiagramPreviewOptions(CreatePageStream) {#constructor}

ينشئ مثيلاً جديدًا لفئة [`DiagramPreviewOptions`](../../diagrampreviewoptions) مما يؤدي إلى إغلاق تدفق الإخراج.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

---

## DiagramPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

ينشئ مثيلاً جديدًا لفئة [`DiagramPreviewOptions`](../../diagrampreviewoptions) مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل لاستخدامه لاحقًا.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |
| releasePageStream | ReleasePageStream | يُخطر بأن إنشاء معاينة الصفحة قد انتهى ويحصل على تدفق الإخراج. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
