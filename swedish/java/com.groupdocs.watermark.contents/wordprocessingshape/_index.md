---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en ritad form i ett Word-dokument."
type: docs
weight: 141
url: /sv/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Representerar en ritad form i ett Word-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSection()](#getSection--) | Hämtar föräldraavsnittet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Hämtar föräldraheadern/foten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (om den finns). |
|
|  | [getShapeType()](#getShapeType--) | Hämtar formens typ. |
|
|  | [isWordArt()](#isWordArt--) | Hämtar ett värde som indikerar om detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` är ett WordArt-objekt. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Hämtar den beskrivande (alternativa) texten som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ställer in den beskrivande (alternativa) texten som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getName()](#getName--) | Hämtar namnet på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getBehindText()](#getBehindText--) | Hämtar ett värde som indikerar om formen ligger över eller bakom texten. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Ställer in ett värde som indikerar om formen ligger över eller bakom texten. |
|
|  | [getText()](#getText--) | Hämtar texten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ställer in texten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getImage()](#getImage--) | Hämtar bilden av detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Ställer in bilden för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Hämtar ett värde som anger hur formen är placerad horisontellt. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Hämtar ett värde som anger hur formen är placerad vertikalt. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Hämtar ett värde som anger var formen är placerad horisontellt. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Hämtar ett värde som anger var formen är placerad vertikalt. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Hämtar hyperlänken som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Ställer in hyperlänken som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ställer in bredden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ställer in höjden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i grader. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ställer in rotationsvinkeln för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i grader. |
|
|  | [getX()](#getX--) | Hämtar eller anger det horisontella avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans vänstra kant i punkter. |
|
|  | [setX(double value)](#setX-double-) | Hämtar eller anger det horisontella avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar det vertikala avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans övre kant i punkter. |
|
|  | [setY(double value)](#setY-double-) | Ställer in det vertikala avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans övre kant i punkter. |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Hämtar föräldraavsnittet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Hämtar föräldraheadern/foten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (om den finns).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Hämtar formens typ.


**Returns:**
int - Formens typ.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Hämtar ett värde som indikerar om detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` är ett WordArt-objekt.


**Returns:**
boolean - Sant om formen är ett WordArt‑objekt; annars falskt.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Hämtar den beskrivande (alternativa) texten som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Den beskrivande (alternativa) texten som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ställer in den beskrivande (alternativa) texten som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Den beskrivande (alternativa) texten som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Namnet på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Hämtar ett värde som indikerar om formen ligger över eller bakom texten.


**Returns:**
boolean - Värdet som indikerar om formen är över eller bakom texten. Sant om formen är bakom texten; annars falskt.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Ställer in ett värde som indikerar om formen ligger över eller bakom texten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Värdet som indikerar om formen är över eller bakom texten. Sant om formen är bakom texten; annars falskt. |
|

### getText() {#getText--}
```
public final String getText()
```


Hämtar texten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Texten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ställer in texten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Hämtar bilden av detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Ställer in bilden för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | Bilden av detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` eller `null` om bilden ska tas bort. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Hämtar ett värde som anger hur formen är placerad horisontellt.


**Returns:**
int - Det horisontella justeringsvärdet.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Hämtar ett värde som anger hur formen är placerad vertikalt.


**Returns:**
int - Det vertikala justeringsvärdet.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Hämtar ett värde som anger var formen är placerad horisontellt.


**Returns:**
int - Det relativa horisontella positionsvärdet.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Hämtar ett värde som anger var formen är placerad vertikalt.


**Returns:**
int - Det relativa vertikala positionsvärdet.

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Hämtar hyperlänken som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Hyperlänken som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Ställer in hyperlänken som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Hyperlänken som är associerad med detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar bredden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter.


**Returns:**
double - Bredden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ställer in bredden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Bredden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar höjden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter.


**Returns:**
double - Höjden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ställer in höjden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Höjden på detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i punkter. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Hämtar rotationsvinkeln för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i grader.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ställer in rotationsvinkeln för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i grader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Rotationsvinkeln för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` i grader. |
|

### getX() {#getX--}
```
public final double getX()
```


Hämtar eller anger det horisontella avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans vänstra kant i punkter.


**Returns:**
double - X-koordinaten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Hämtar eller anger det horisontella avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans vänstra kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | X-koordinaten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Hämtar det vertikala avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans övre kant i punkter.


**Returns:**
double - Y-koordinaten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ställer in det vertikala avståndet för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` från sidans övre kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Y-koordinaten för detta `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageData | byte[] |  |

