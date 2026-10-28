---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Zeichnungsform in einem Excel-Dokument dar."
type: docs
weight: 117
url: /de/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Stellt eine Zeichnungsform in einem Excel-Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Ermittelt das übergeordnete Arbeitsblatt dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Ermittelt den AutoShape-Typ. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Ermittelt den MSO-Zeichnungstyp. |
|
|  | [getText()](#getText--) | Ermittelt den Text dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Text dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ermittelt die Sammlung formatierter Textfragmente dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | Ermittelt das Bild dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Setzt das Bild dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Ermittelt die Einstellungen des Bildfüllungsformats dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | Ermittelt die Kennung dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ermittelt den beschreibenden (alternativen) Text, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Setzt den beschreibenden (alternativen) Text, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist. |
|
|  | [isWordArt()](#isWordArt--) | Ermittelt einen Wert, der angibt, ob dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ein WordArt-Objekt ist. |
|
|  | [getName()](#getName--) | Ermittelt den Namen dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Ermittelt den Hyperlink, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Setzt den Hyperlink, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist. |
|
|  | [getX()](#getX--) | Ermittelt den horizontalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der linken Arbeitsblattkante in Punkten. |
|
|  | [setX(double value)](#setX-double-) | Legt den horizontalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der linken Arbeitsblattkante in Punkten fest. |
|
|  | [getY()](#getY--) | Ermittelt den vertikalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der oberen Arbeitsblattkante in Punkten. |
|
|  | [setY(double value)](#setY-double-) | Legt den vertikalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der oberen Arbeitsblattkante in Punkten fest. |
|
|  | [getWidth()](#getWidth--) | Ermittelt die Breite dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Legt die Breite dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten fest. |
|
|  | [getHeight()](#getHeight--) | Ermittelt die Höhe dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Legt die Höhe dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten fest. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ermittelt oder legt den Drehwinkel dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Grad fest. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ermittelt oder legt den Drehwinkel dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Grad fest. |
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


Ermittelt das übergeordnete Arbeitsblatt dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Ermittelt den AutoShape-Typ.


**Returns:**
int - Der AutoShape-Typ.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Ermittelt den MSO-Zeichnungstyp.


**Returns:**
int - Der MSO-Zeichnungstyp.

### getText() {#getText--}
```
public final String getText()
```


Ermittelt den Text dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Der Text dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Setzt den Text dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Ermittelt die Sammlung formatierter Textfragmente dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Ermittelt das Bild dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Setzt das Bild dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Das Bild dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` oder null, wenn das Bild entfernt werden soll. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Ermittelt die Einstellungen des Bildfüllungsformats dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Ermittelt die Kennung dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - Der Bezeichner dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Ermittelt den beschreibenden (alternativen) Text, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist.


**Returns:**
java.lang.String - Der beschreibende (alternative) Text, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Setzt den beschreibenden (alternativen) Text, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der beschreibende (alternative) Text, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Ermittelt einen Wert, der angibt, ob dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ein WordArt-Objekt ist.


**Returns:**
boolean - Wahr, wenn die Form ein WordArt-Objekt ist; andernfalls falsch.

### getName() {#getName--}
```
public final String getName()
```


Ermittelt den Namen dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Der Name dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

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


Ermittelt den Hyperlink, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist.


**Returns:**
java.lang.String - Der Hyperlink, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Setzt den Hyperlink, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Hyperlink, der mit diesem `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` verknüpft ist. |
|

### getX() {#getX--}
```
public final double getX()
```


Ermittelt den horizontalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der linken Arbeitsblattkante in Punkten.


**Returns:**
double - Die x-Koordinate dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Legt den horizontalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der linken Arbeitsblattkante in Punkten fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die x-Koordinate dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Ermittelt den vertikalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der oberen Arbeitsblattkante in Punkten.


**Returns:**
double - Die y-Koordinate dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Legt den vertikalen Versatz dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` von der oberen Arbeitsblattkante in Punkten fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die y-Koordinate dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ermittelt die Breite dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten.


**Returns:**
double - Die Breite dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Legt die Breite dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Breite dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ermittelt die Höhe dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten.


**Returns:**
double - Die Höhe dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Legt die Höhe dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Höhe dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Punkten. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Ermittelt oder legt den Drehwinkel dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Grad fest.


**Returns:**
double - Der Rotationswinkel dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Grad.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ermittelt oder legt den Drehwinkel dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Grad fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der Rotationswinkel dieses `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` in Grad. |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

