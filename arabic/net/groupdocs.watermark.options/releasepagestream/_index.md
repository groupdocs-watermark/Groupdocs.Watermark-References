---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل طريقة تُفرج عن الدفق الذي تم إنشاؤه بواسطة المفوض CreatePageStream./createpagestream."
type: docs
weight: 2160
url: /ar/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

يمثل طريقة تُفرج عن الدفق الذي تم إنشاؤه بواسطة المفوض [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| معامل | Type | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة لمعاينة صفحة مُولَّدة. |
| pageStream | Stream | الدفق الذي يحتوي على معاينة الصفحة المُولَّدة. |

### انظر أيضاً

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
