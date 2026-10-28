---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een tekenvorm in een Excel‑document voor."
type: docs
weight: 117
url: /nl/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Stelt een tekenvorm in een Excel‑document voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Haalt het bovenliggende werkblad op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Haalt het type autoshape op. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Haalt het mso-teken type op. |
|
|  | [getText()](#getText--) | Haalt de tekst op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de verzameling van opgemaakte tekstfragmenten op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | Haalt de afbeelding op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Stelt de afbeelding in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Haalt de instellingen voor het opvulformaat van de afbeelding op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | Haalt de identifier op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Haalt de beschrijvende (alternatieve) tekst op die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Stelt de beschrijvende (alternatieve) tekst in die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld. |
|
|  | [isWordArt()](#isWordArt--) | Haalt een waarde op die aangeeft of deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` een WordArt-object is. |
|
|  | [getName()](#getName--) | Haalt de naam op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Haalt de hyperlink op die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Stelt de hyperlink in die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld. |
|
|  | [getX()](#getX--) | Haalt de horizontale offset op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de linkerrand van het werkblad in punten. |
|
|  | [setX(double value)](#setX-double-) | Stelt de horizontale offset in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de linkerrand van het werkblad in punten. |
|
|  | [getY()](#getY--) | Haalt de verticale offset op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de bovengrens van het werkblad in punten. |
|
|  | [setY(double value)](#setY-double-) | Stelt de verticale offset in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de bovengrens van het werkblad in punten. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` op in punten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Stelt de breedte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten in. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` op in punten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Stelt de hoogte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten in. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt of stelt de rotatiehoek van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in graden in. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Haalt of stelt de rotatiehoek van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in graden in. |
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


Haalt het bovenliggende werkblad op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Haalt het type autoshape op.


**Returns:**
int - Het type autoshape.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Haalt het mso-teken type op.


**Returns:**
int - Het mso-teken type.

### getText() {#getText--}
```
public final String getText()
```


Haalt de tekst op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - De tekst van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Stelt de tekst in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de verzameling van opgemaakte tekstfragmenten op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Haalt de afbeelding op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Stelt de afbeelding in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | De afbeelding van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` of null als de afbeelding moet worden verwijderd. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Haalt de instellingen voor het opvulformaat van de afbeelding op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Haalt de identifier op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - De identificatie van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Haalt de beschrijvende (alternatieve) tekst op die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld.


**Returns:**
java.lang.String - De beschrijvende (alternatieve) tekst die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Stelt de beschrijvende (alternatieve) tekst in die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De beschrijvende (alternatieve) tekst die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Haalt een waarde op die aangeeft of deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` een WordArt-object is.


**Returns:**
boolean - Waar als de vorm een WordArt-object is; anders onwaar.

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - De naam van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

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


Haalt de hyperlink op die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld.


**Returns:**
java.lang.String - De hyperlink die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Stelt de hyperlink in die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De hyperlink die aan deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` is gekoppeld. |
|

### getX() {#getX--}
```
public final double getX()
```


Haalt de horizontale offset op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de linkerrand van het werkblad in punten.


**Returns:**
double - De x-coördinaat van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Stelt de horizontale offset in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de linkerrand van het werkblad in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De x-coördinaat van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Haalt de verticale offset op van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de bovengrens van het werkblad in punten.


**Returns:**
double - De y-coördinaat van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Stelt de verticale offset in van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ten opzichte van de bovengrens van het werkblad in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De y-coördinaat van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de breedte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` op in punten.


**Returns:**
double - De breedte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Stelt de breedte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De breedte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de hoogte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` op in punten.


**Returns:**
double - De hoogte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Stelt de hoogte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De hoogte van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in punten. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Haalt of stelt de rotatiehoek van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in graden in.


**Returns:**
double - De rotatiehoek van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in graden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Haalt of stelt de rotatiehoek van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in graden in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De rotatiehoek van deze `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in graden. |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

