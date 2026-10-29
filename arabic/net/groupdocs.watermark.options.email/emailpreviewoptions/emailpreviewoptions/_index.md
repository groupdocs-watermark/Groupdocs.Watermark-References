---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "ينشئ مثلاً جديداً لفئة EmailPreviewOptionsgroupdocs.watermark.options.email/emailpreviewoptions مما يؤدي إلى إغلاق تدفق الإخراج."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark.options.email/emailpreviewoptions/emailpreviewoptions/
---
## EmailPreviewOptions(CreatePageStream) {#constructor}

يُنشئ مثيلاً جديدًا من الفئة [`EmailPreviewOptions`](../../emailpreviewoptions) مما يؤدي إلى إغلاق تدفق الإخراج.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

---

## EmailPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

يُنشئ مثيلاً جديدًا من الفئة [`EmailPreviewOptions`](../../emailpreviewoptions) مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | ينشئ تدفقًا لمعاينة صفحة محددة. |
| releasePageStream | ReleasePageStream | يُخطر بأن إنشاء معاينة الصفحة قد انتهى ويحصل على تدفق الإخراج. |

### انظر أيضاً

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
