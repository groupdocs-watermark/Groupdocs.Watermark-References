---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Zeichnungsform in einem Word-Dokument dar."
type: docs
weight: 141
url: /de/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Stellt eine Zeichnungsform in einem Word-Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSection()](#getSection--) | Liefert den übergeordneten Abschnitt dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Liefert die übergeordnete Kopf-/Fußzeile dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (falls vorhanden). |
|
|  | [getShapeType()](#getShapeType--) | Liefert den Formtyp. |
|
|  | [isWordArt()](#isWordArt--) | Liefert einen Wert, der angibt, ob dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ein WordArt-Objekt ist. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Liefert den beschreibenden (alternativen) Text, der diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` zugeordnet ist. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Setzt den beschreibenden (alternativen) Text, der diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` zugeordnet ist. |
|
|  | [getName()](#getName--) | Liefert den Namen dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getBehindText()](#getBehindText--) | Liefert einen Wert, der angibt, ob die Form über oder hinter dem Text liegt. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Setzt einen Wert, der angibt, ob die Form über oder hinter dem Text liegt. |
|
|  | [getText()](#getText--) | Liefert den Text dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Text dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Liefert die Sammlung formatierter Textfragmente dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getImage()](#getImage--) | Liefert das Bild dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Setzt das Bild dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Liefert einen Wert, der angibt, wie die Form horizontal positioniert ist. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Liefert einen Wert, der angibt, wie die Form vertikal positioniert ist. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Liefert einen Wert, der angibt, worauf die Form horizontal ausgerichtet ist. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Liefert einen Wert, der angibt, worauf die Form vertikal ausgerichtet ist. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Liest den Hyperlink, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Setzt den Hyperlink, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist. |
|
|  | [getWidth()](#getWidth--) | Liest die Breite dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Setzt die Breite dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten. |
|
|  | [getHeight()](#getHeight--) | Liest die Höhe dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Setzt die Höhe dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Liest den Rotationswinkel dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Grad. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Setzt den Rotationswinkel dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Grad. |
|
|  | [getX()](#getX--) | Liest oder setzt den horizontalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom linken Seitenrand in Punkten. |
|
|  | [setX(double value)](#setX-double-) | Liest oder setzt den horizontalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom linken Seitenrand in Punkten. |
|
|  | [getY()](#getY--) | Liest den vertikalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom oberen Seitenrand in Punkten. |
|
|  | [setY(double value)](#setY-double-) | Setzt den vertikalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom oberen Seitenrand in Punkten. |
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


Liefert den übergeordneten Abschnitt dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Liefert die übergeordnete Kopf-/Fußzeile dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (falls vorhanden).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Liefert den Formtyp.


**Returns:**
int - Der Formtyp.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Liefert einen Wert, der angibt, ob dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ein WordArt-Objekt ist.


**Returns:**
boolean - Wahr, wenn die Form ein WordArt-Objekt ist; andernfalls falsch.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Liefert den beschreibenden (alternativen) Text, der diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` zugeordnet ist.


**Returns:**
java.lang.String - Der beschreibende (alternative) Text, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Setzt den beschreibenden (alternativen) Text, der diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` zugeordnet ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der beschreibende (alternative) Text, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist. |
|

### getName() {#getName--}
```
public final String getName()
```


Liefert den Namen dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Der Name dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Liefert einen Wert, der angibt, ob die Form über oder hinter dem Text liegt.


**Returns:**
boolean - Der Wert, der angibt, ob die Form über oder hinter dem Text liegt. Wahr, wenn die Form hinter dem Text liegt; andernfalls falsch.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Setzt einen Wert, der angibt, ob die Form über oder hinter dem Text liegt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Der Wert, der angibt, ob die Form über oder hinter dem Text liegt. Wahr, wenn die Form hinter dem Text liegt; andernfalls falsch. |
|

### getText() {#getText--}
```
public final String getText()
```


Liefert den Text dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Der Text dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Setzt den Text dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Liefert die Sammlung formatierter Textfragmente dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Liefert das Bild dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Setzt das Bild dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | Das Bild dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` oder `null`, wenn das Bild entfernt werden soll. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Liefert einen Wert, der angibt, wie die Form horizontal positioniert ist.


**Returns:**
int - Der Wert für die horizontale Ausrichtung.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Liefert einen Wert, der angibt, wie die Form vertikal positioniert ist.


**Returns:**
int - Der Wert für die vertikale Ausrichtung.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Liefert einen Wert, der angibt, worauf die Form horizontal ausgerichtet ist.


**Returns:**
int - Der Wert für die relative horizontale Position.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Liefert einen Wert, der angibt, worauf die Form vertikal ausgerichtet ist.


**Returns:**
int - Der Wert für die relative vertikale Position.

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


Liest den Hyperlink, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist.


**Returns:**
java.lang.String - Der Hyperlink, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Setzt den Hyperlink, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Hyperlink, der mit diesem `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` verknüpft ist. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Liest die Breite dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten.


**Returns:**
double - Die Breite dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Setzt die Breite dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Breite dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Liest die Höhe dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten.


**Returns:**
double - Die Höhe dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Setzt die Höhe dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Höhe dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Punkten. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Liest den Rotationswinkel dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Grad.


**Returns:**
double - Der Rotationswinkel dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Grad.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Setzt den Rotationswinkel dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Grad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der Rotationswinkel dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in Grad. |
|

### getX() {#getX--}
```
public final double getX()
```


Liest oder setzt den horizontalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom linken Seitenrand in Punkten.


**Returns:**
double - Die x-Koordinate dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Liest oder setzt den horizontalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom linken Seitenrand in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die x-Koordinate dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Liest den vertikalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom oberen Seitenrand in Punkten.


**Returns:**
double - Die y-Koordinate dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Setzt den vertikalen Versatz dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vom oberen Seitenrand in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die y-Koordinate dieses `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageData | byte[] |  |

