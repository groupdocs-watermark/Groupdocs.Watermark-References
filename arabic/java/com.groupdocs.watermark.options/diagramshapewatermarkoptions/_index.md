---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية شكل إلى مستند Visio."
type: docs
weight: 14
url: /ar/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية شكل إلى مستند Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

المثال التالي يوضح كيفية إضافة علامة مائية محمية إلى جميع صفحات مستند Visio.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | ينشئ مثيلاً جديداً للفئة `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | يحصل على قيمة تحدد إلى أي صفحات يجب إضافة العلامة المائية. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | يحصل أو يضبط قيمة تحدد إلى أي صفحات يجب إضافة العلامة المائية. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


ينشئ مثيلاً جديداً للفئة `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)`.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


يحصل على قيمة تحدد إلى أي صفحات يجب إضافة العلامة المائية.


**Returns:**
int - الـ `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`، الذي يحدد إلى أي صفحات يجب إضافة العلامة المائية.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


يحصل أو يضبط قيمة تحدد إلى أي صفحات يجب إضافة العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | الـ `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`، الذي يحدد إلى أي صفحات يجب إضافة العلامة المائية. |
|

