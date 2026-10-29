---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى مستند Visio."
type: docs
weight: 1750
url: /ar/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى مستند Visio.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | ينشئ مثيلًا جديدًا من الفئة [`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان تحرير الشكل في Visio محظورًا. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | يحصل أو يعيّن قيمة تحدد إلى أي صفحات يجب إضافة العلامة المائية. |

### ملاحظات

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### أمثلة

إضافة علامة مائية محمية إلى جميع صفحات مستند Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
