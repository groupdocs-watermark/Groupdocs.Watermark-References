---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية شكل إلى صفحة معينة من مستند Visio."
type: docs
weight: 11
url: /ar/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية شكل إلى صفحة معينة من مستند Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

المثال التالي يوضح كيفية إضافة علامة مائية محمية إلى الصفحة الأولى من مستند Visio.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
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
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | ينشئ مثيلاً جديداً من الفئة `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | يحصل على فهرس الصفحة لإضافة العلامة المائية إليها. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | يضبط فهرس الصفحة لإضافة العلامة المائية إليها. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


ينشئ مثيلاً جديداً من الفئة `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


يحصل على فهرس الصفحة لإضافة العلامة المائية إليها.


**Returns:**
int - فهرس الصفحة لإضافة العلامة المائية إليها.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


يضبط فهرس الصفحة لإضافة العلامة المائية إليها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | فهرس الصفحة لإضافة العلامة المائية إليها. |
|

