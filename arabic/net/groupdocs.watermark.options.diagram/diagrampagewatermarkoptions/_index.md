---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى صفحة معينة من مستند Visio."
type: docs
weight: 1720
url: /ar/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى صفحة معينة من مستند Visio.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | يُنشئ مثيلاً جديدًا من الفئة [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان تحرير الشكل في Visio محظورًا. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | يحصل أو يعيّن فهرس الصفحة لإضافة العلامة المائية إليها. |

### ملاحظات

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### أمثلة

إضافة علامة مائية محمية إلى الصفحة الأولى من مستند Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
