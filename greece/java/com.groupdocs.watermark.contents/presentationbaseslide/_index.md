---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει την αφηρημένη βασική κλάση για διαφάνειες όλων των τύπων σε ένα έγγραφο PowerPoint."
type: docs
weight: 78
url: /el/java/com.groupdocs.watermark.contents/presentationbaseslide/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class PresentationBaseSlide extends ContentPart
```

Παρέχει την αφηρημένη βασική κλάση για διαφάνειες όλων των τύπων σε ένα έγγραφο PowerPoint.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getShapes()](#getShapes--) | Λαμβάνει τη συλλογή όλων των σχημάτων της παρουσίασης. |
|
|  | [getCharts()](#getCharts--) | Λαμβάνει τη συλλογή όλων των διαγραμμάτων στην παρουσίαση. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Λαμβάνει τις ρυθμίσεις μορφής γεμίσματος εικόνας της παρουσίασης. |
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


Λαμβάνει τη συλλογή όλων των σχημάτων της παρουσίασης.


**Returns:**
[PresentationShapeCollection](../../com.groupdocs.watermark.contents/presentationshapecollection) - The collection of all shapes of the presentation.

### getCharts() {#getCharts--}
```
public final PresentationChartCollection getCharts()
```


Λαμβάνει τη συλλογή όλων των διαγραμμάτων στην παρουσίαση.


**Returns:**
[PresentationChartCollection](../../com.groupdocs.watermark.contents/presentationchartcollection) - The collection of all charts on the presentation.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Λαμβάνει τις ρυθμίσεις μορφής γεμίσματος εικόνας της παρουσίασης.


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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

