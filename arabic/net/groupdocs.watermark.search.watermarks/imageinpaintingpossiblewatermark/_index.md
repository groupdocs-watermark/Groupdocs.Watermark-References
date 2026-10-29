---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل منطقة صورة محددة يدويًا يجب تعبئتها باستخدام البكسلات المحيطة."
type: docs
weight: 2900
url: /ar/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

يمثل منطقة صورة محددة يدويًا يجب تعبئتها (ملء باستخدام البكسلات المحيطة).

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | ينشئ مثيلًا جديدًا للفئة [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | يحصل على مجموعة مقاطع النص المنسقة لهذه [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | يسترجع ارتفاع هذا [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | يحصل أو يضبط صورة هذه [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | يحصل أو يعيّن خوارزمية التلوين. القيمة الافتراضية هي PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | يحصل على الصفحة التي وضعت عليها العلامة المائية. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | يحصل على الأصل لهذا [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). دائمًا ما يُعيد `null` لأن المنطقة محددة يدويًا. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | يحصل أو يعيّن حجم الرقعة المستخدمة من قبل الخوارزمية (فردي، 5-11). القيمة الافتراضية هي 7. بالنسبة لـ Telea يُستخدم هذا كـ HalfPatchSize. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | يحصل أو يعيّن المناطق متعددة الأضلاع التي يجب تعبئتها، بوحدات بكسل الصورة. كل مضلع هو مصفوفة من الرؤوس. يجب تحديد إما [`Rectangles`](./rectangles) أو [`Polygons`](./polygons)، وليس كليهما. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | يحصل أو يعيّن المناطق المستطيلة التي يجب تعبئتها، بوحدات بكسل الصورة. يجب تحديد إما [`Rectangles`](./rectangles) أو [`Polygons`](./polygons)، وليس كليهما. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | يسترجع زاوية الدوران لهذا [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) بالدرجات. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | يسترجع أو يضبط نص هذا [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | يسترجع وحدة القياس لهذا [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | يسترجع عرض هذا [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | يسترجع إحداثي x لهذا [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | يسترجع إحداثي y لهذا [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |

### انظر أيضاً

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
