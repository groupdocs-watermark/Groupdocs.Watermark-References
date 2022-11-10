---
title: PresentationBaseSlide
second_title: GroupDocs.Watermark for Java API Reference
description: Provides the abstract base class for slides of all types in a PowerPoint document.
type: docs
weight: 78
url: /java/com.groupdocs.watermark.contents/presentationbaseslide/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class PresentationBaseSlide extends ContentPart
```

Provides the abstract base class for slides of all types in a PowerPoint document.
## Methods

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Gets the collection of all shapes of the presentation. |
| [getCharts()](#getCharts--) | Gets the collection of all charts on the presentation. |
| [getImageFillFormat()](#getImageFillFormat--) | Gets the image fill format settings of the presentation. |
| [getAsposeSlidesSlide()](#getAsposeSlidesSlide--) |  |
| [getWidth()](#getWidth--) |  |
| [getHeight()](#getHeight--) |  |
| [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) |  |
### getShapes() {#getShapes--}
```
public final PresentationShapeCollection getShapes()
```


Gets the collection of all shapes of the presentation.

**Returns:**
[PresentationShapeCollection](../../com.groupdocs.watermark.contents/presentationshapecollection) - The collection of all shapes of the presentation.
### getCharts() {#getCharts--}
```
public final PresentationChartCollection getCharts()
```


Gets the collection of all charts on the presentation.

**Returns:**
[PresentationChartCollection](../../com.groupdocs.watermark.contents/presentationchartcollection) - The collection of all charts on the presentation.
### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Gets the image fill format settings of the presentation.

**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of the presentation.
### getAsposeSlidesSlide() {#getAsposeSlidesSlide--}
```
public final IBaseSlide getAsposeSlidesSlide()
```




**Returns:**
com.aspose.slides.IBaseSlide
### getWidth() {#getWidth--}
```
public double getWidth()
```




**Returns:**
double
### getHeight() {#getHeight--}
```
public double getHeight()
```




**Returns:**
double
### addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

