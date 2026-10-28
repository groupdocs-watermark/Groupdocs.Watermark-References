---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit la classe de base abstraite pour les diapositives de tous types dans un document PowerPoint."
type: docs
weight: 78
url: /fr/java/com.groupdocs.watermark.contents/presentationbaseslide/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class PresentationBaseSlide extends ContentPart
```

Fournit la classe de base abstraite pour les diapositives de tous types dans un document PowerPoint.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getShapes()](#getShapes--) | Obtient la collection de toutes les formes de la présentation. |
|
|  | [getCharts()](#getCharts--) | Obtient la collection de tous les graphiques de la présentation. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Obtient les paramètres du format de remplissage d'image de la présentation. |
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


Obtient la collection de toutes les formes de la présentation.


**Returns:**
[PresentationShapeCollection](../../com.groupdocs.watermark.contents/presentationshapecollection) - The collection of all shapes of the presentation.

### getCharts() {#getCharts--}
```
public final PresentationChartCollection getCharts()
```


Obtient la collection de tous les graphiques de la présentation.


**Returns:**
[PresentationChartCollection](../../com.groupdocs.watermark.contents/presentationchartcollection) - The collection of all charts on the presentation.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Obtient les paramètres du format de remplissage d'image de la présentation.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

