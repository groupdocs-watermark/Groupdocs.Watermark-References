---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en ritningsform i ett Excel-dokument."
type: docs
weight: 117
url: /sv/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Representerar en ritningsform i ett Excel-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Hämtar föräldraarbetsbladet för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Hämtar auto shape‑typen. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Hämtar MSO‑ritningstypen. |
|
|  | [getText()](#getText--) | Hämtar texten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ställer in texten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | Hämtar bilden för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Ställer in bilden för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Hämtar inställningarna för bildens fyllningsformat för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | Hämtar identifieraren för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Hämtar den beskrivande (alternativa) texten som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ställer in den beskrivande (alternativa) texten som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [isWordArt()](#isWordArt--) | Hämtar ett värde som indikerar om detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` är ett WordArt‑objekt. |
|
|  | [getName()](#getName--) | Hämtar namnet på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Hämtar hyperlänken som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Ställer in hyperlänken som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets vänstra kant i punkter. |
|
|  | [setX(double value)](#setX-double-) | Ställer in den horisontella förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar den vertikala förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets övre kant i punkter. |
|
|  | [setY(double value)](#setY-double-) | Ställer in den vertikala förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets övre kant i punkter. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ställer in bredden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ställer in höjden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar eller ställer in rotationsvinkeln för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i grader. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Hämtar eller ställer in rotationsvinkeln för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i grader. |
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
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Hämtar föräldraarbetsbladet för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Hämtar auto shape‑typen.


**Returns:**
int - Autoshapetypen.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Hämtar MSO‑ritningstypen.


**Returns:**
int - MSO-ritningstypen.

### getText() {#getText--}
```
public final String getText()
```


Hämtar texten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Texten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ställer in texten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Hämtar bilden för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Ställer in bilden för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Bilden för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` eller null om bilden ska tas bort. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Hämtar inställningarna för bildens fyllningsformat för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Hämtar identifieraren för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - Identifieraren för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Hämtar den beskrivande (alternativa) texten som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Den beskrivande (alternativa) texten som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ställer in den beskrivande (alternativa) texten som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Den beskrivande (alternativa) texten som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Hämtar ett värde som indikerar om detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` är ett WordArt‑objekt.


**Returns:**
boolean - Sant om formen är ett WordArt‑objekt; annars falskt.

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Namnet på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Hämtar hyperlänken som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Hyperlänken som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Ställer in hyperlänken som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Hyperlänken som är associerad med detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Hämtar den horisontella förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets vänstra kant i punkter.


**Returns:**
double - X-koordinaten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ställer in den horisontella förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets vänstra kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | X-koordinaten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Hämtar den vertikala förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets övre kant i punkter.


**Returns:**
double - Y-koordinaten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ställer in den vertikala förskjutningen för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` från kalkylbladets övre kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Y-koordinaten för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar bredden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter.


**Returns:**
double - Bredden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ställer in bredden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Bredden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar höjden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter.


**Returns:**
double - Höjden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ställer in höjden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Höjden på detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i punkter. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Hämtar eller ställer in rotationsvinkeln för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i grader.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Hämtar eller ställer in rotationsvinkeln för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i grader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Rotationsvinkeln för detta `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` i grader. |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

