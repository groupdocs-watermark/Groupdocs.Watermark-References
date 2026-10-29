---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller den abstrakta basklassen för bilder av alla typer i ett PowerPoint-dokument."
type: docs
weight: 78
url: /sv/java/com.groupdocs.watermark.contents/presentationbaseslide/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class PresentationBaseSlide extends ContentPart
```

Tillhandahåller den abstrakta basklassen för bilder av alla typer i ett PowerPoint-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getShapes()](#getShapes--) | Hämtar samlingen av alla former i presentationen. |
|
|  | [getCharts()](#getCharts--) | Hämtar samlingen av alla diagram i presentationen. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Hämtar inställningarna för bildfyllningsformatet i presentationen. |
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


Hämtar samlingen av alla former i presentationen.


**Returns:**
[PresentationShapeCollection](../../com.groupdocs.watermark.contents/presentationshapecollection) - The collection of all shapes of the presentation.

### getCharts() {#getCharts--}
```
public final PresentationChartCollection getCharts()
```


Hämtar samlingen av alla diagram i presentationen.


**Returns:**
[PresentationChartCollection](../../com.groupdocs.watermark.contents/presentationchartcollection) - The collection of all charts on the presentation.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Hämtar inställningarna för bildfyllningsformatet i presentationen.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

