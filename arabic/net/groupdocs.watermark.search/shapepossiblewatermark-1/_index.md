---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل علامة مائية شكلية في محتوى بأي تنسيق مدعوم."
type: docs
weight: 2770
url: /ar/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

يمثل علامة مائية شكلية في محتوى بأي تنسيق مدعوم.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| معامل | الوصف |
| --- | --- |
| T | نوع الشكل. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | يسترجع مجموعة مقاطع النص المنسقة للشكل. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | يسترجع ارتفاع الكائن ثنائي الأبعاد. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | يحصل أو يضبط صورة هذا [`PossibleWatermark`](../possiblewatermark). |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | يحصل على الصفحة التي وضعت عليها العلامة المائية. |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | يحصل على العنصر الأب لهذا [`PossibleWatermark`](../possiblewatermark). |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | يسترجع زاوية دوران الشكل بالدرجات. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | يسترجع أو يضبط نص الشكل. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | يسترجع وحدة قياس الكائن ثنائي الأبعاد. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | يسترجع عرض الكائن ثنائي الأبعاد. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | يسترجع إحداثي x للكائن ثنائي الأبعاد. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | يسترجع إحداثي y للكائن ثنائي الأبعاد. |

### انظر أيضاً

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
