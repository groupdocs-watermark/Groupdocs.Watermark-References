---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر الفئة الأساسية المجردة للشرائح من جميع الأنواع في مستند PowerPoint."
type: docs
weight: 78
url: /ar/java/com.groupdocs.watermark.contents/presentationbaseslide/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class PresentationBaseSlide extends ContentPart
```

يوفر الفئة الأساسية المجردة للشرائح من جميع الأنواع في مستند PowerPoint.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getShapes()](#getShapes--) | يحصل على مجموعة جميع الأشكال في العرض التقديمي. |
|
|  | [getCharts()](#getCharts--) | يحصل على مجموعة جميع المخططات في العرض التقديمي. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | يحصل على إعدادات تنسيق تعبئة الصورة في العرض التقديمي. |
|
|  | [getAsposeSlidesSlide()](#getAsposeSlidesSlide--) | <br /> |

|
|  | [getWidth()](#getWidth--) | <br /> |

|
|  | [getHeight()](#getHeight--) | <br /> |

|
|  | [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | <br /> |

|
### getShapes() {#getShapes--}
```
public final PresentationShapeCollection getShapes()
```


يحصل على مجموعة جميع الأشكال في العرض التقديمي.


**Returns:**
[PresentationShapeCollection](../../com.groupdocs.watermark.contents/presentationshapecollection) - The collection of all shapes of the presentation.

### getCharts() {#getCharts--}
```
public final PresentationChartCollection getCharts()
```


يحصل على مجموعة جميع المخططات في العرض التقديمي.


**Returns:**
[PresentationChartCollection](../../com.groupdocs.watermark.contents/presentationchartcollection) - The collection of all charts on the presentation.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


يحصل على إعدادات تنسيق تعبئة الصورة في العرض التقديمي.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of the presentation.

### getAsposeSlidesSlide() {#getAsposeSlidesSlide--}
```
public final IBaseSlide getAsposeSlidesSlide()
```


<br />



**Returns:**
com.aspose.slides.IBaseSlide
### getWidth() {#getWidth--}
```
public double getWidth()
```


<br />



**Returns:**
double
### getHeight() {#getHeight--}
```
public double getHeight()
```


<br />



**Returns:**
double
### addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

