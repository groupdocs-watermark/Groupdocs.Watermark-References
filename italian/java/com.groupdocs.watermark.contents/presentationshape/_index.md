---
title: "PresentationShape"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una forma di disegno in un documento PowerPoint."
type: docs
weight: 93
url: /it/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Rappresenta una forma di disegno in un documento PowerPoint.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in gradi. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Imposta l'angolo di rotazione di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in gradi. |
|
|  | [getText()](#getText--) | Ottiene il testo di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ottiene la collezione di frammenti di testo formattato di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getShapeType()](#getShapeType--) | Ottiene il tipo predefinito di geometria della forma. |
|
|  | [getImage()](#getImage--) | Ottiene l'immagine di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Imposta l'immagine di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in gradi.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Imposta l'angolo di rotazione di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in gradi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'angolo di rotazione di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` in gradi. |
|

### getText() {#getText--}
```
public final String getText()
```


Ottiene il testo di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
java.lang.String - Il testo di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Imposta il testo di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Ottiene la collezione di frammenti di testo formattato di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Ottiene il tipo predefinito di geometria della forma.


**Returns:**
int - Il tipo predefinito di geometria.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Ottiene l'immagine di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Imposta l'immagine di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | L'immagine di questo `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` o null se l'immagine deve essere rimossa. |
|

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageData | byte[] |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

