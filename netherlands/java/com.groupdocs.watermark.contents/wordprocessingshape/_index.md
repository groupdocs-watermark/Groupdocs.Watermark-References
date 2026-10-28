---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een tekenvorm in een Word-document voor."
type: docs
weight: 141
url: /nl/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Stelt een tekenvorm in een Word-document voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSection()](#getSection--) | Haalt de bovenliggende sectie van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Haalt de bovenliggende kop-/voettekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op (indien aanwezig). |
|
|  | [getShapeType()](#getShapeType--) | Haalt het vormtype op. |
|
|  | [isWordArt()](#isWordArt--) | Haalt een waarde op die aangeeft of deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` een WordArt-object is. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Haalt de beschrijvende (alternatieve) tekst op die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Stelt de beschrijvende (alternatieve) tekst in die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld. |
|
|  | [getName()](#getName--) | Haalt de naam van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op. |
|
|  | [getBehindText()](#getBehindText--) | Haalt een waarde op die aangeeft of de vorm boven of achter de tekst staat. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Stelt een waarde in die aangeeft of de vorm boven of achter de tekst staat. |
|
|  | [getText()](#getText--) | Haalt de tekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de collectie van opgemaakte tekstfragmenten van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op. |
|
|  | [getImage()](#getImage--) | Haalt de afbeelding van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Stelt de afbeelding van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Haalt een waarde op die aangeeft hoe de vorm horizontaal is gepositioneerd. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Haalt een waarde op die aangeeft hoe de vorm verticaal is gepositioneerd. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Haalt een waarde op die aangeeft ten opzichte waarvan de vorm horizontaal is gepositioneerd. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Haalt een waarde op die aangeeft ten opzichte waarvan de vorm verticaal is gepositioneerd. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Haalt de hyperlink op die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Stelt de hyperlink in die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op in punten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Stelt de breedte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten in. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte op van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Stelt de hoogte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten in. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in graden op. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Stelt de rotatiehoek van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in graden in. |
|
|  | [getX()](#getX--) | Haalt op of stelt de horizontale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ten opzichte van de linkerrand van de pagina in punten in. |
|
|  | [setX(double value)](#setX-double-) | Haalt op of stelt de horizontale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ten opzichte van de linkerrand van de pagina in punten in. |
|
|  | [getY()](#getY--) | Haalt de verticale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vanaf de bovenrand van de pagina in punten op. |
|
|  | [setY(double value)](#setY-double-) | Stelt de verticale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vanaf de bovenrand van de pagina in punten in. |
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


Haalt de bovenliggende sectie van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Haalt de bovenliggende kop-/voettekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op (indien aanwezig).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Haalt het vormtype op.


**Returns:**
int - Het type vorm.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Haalt een waarde op die aangeeft of deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` een WordArt-object is.


**Returns:**
boolean - Waar als de vorm een WordArt-object is; anders onwaar.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Haalt de beschrijvende (alternatieve) tekst op die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld.


**Returns:**
java.lang.String - De beschrijvende (alternatieve) tekst die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Stelt de beschrijvende (alternatieve) tekst in die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De beschrijvende (alternatieve) tekst die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld. |
|

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op.


**Returns:**
java.lang.String - De naam van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Haalt een waarde op die aangeeft of de vorm boven of achter de tekst staat.


**Returns:**
boolean - De waarde die aangeeft of de vorm boven of achter de tekst staat. True als de vorm achter de tekst staat; anders false.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Stelt een waarde in die aangeeft of de vorm boven of achter de tekst staat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | De waarde die aangeeft of de vorm boven of achter de tekst staat. True als de vorm achter de tekst staat; anders false. |
|

### getText() {#getText--}
```
public final String getText()
```


Haalt de tekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op.


**Returns:**
java.lang.String - De tekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Stelt de tekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de collectie van opgemaakte tekstfragmenten van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Haalt de afbeelding van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Stelt de afbeelding van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | De afbeelding van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` of `null` als de afbeelding verwijderd moet worden. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Haalt een waarde op die aangeeft hoe de vorm horizontaal is gepositioneerd.


**Returns:**
int - De horizontale uitlijningswaarde.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Haalt een waarde op die aangeeft hoe de vorm verticaal is gepositioneerd.


**Returns:**
int - De verticale uitlijningswaarde.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Haalt een waarde op die aangeeft ten opzichte waarvan de vorm horizontaal is gepositioneerd.


**Returns:**
int - De relatieve horizontale positiewaarde.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Haalt een waarde op die aangeeft ten opzichte waarvan de vorm verticaal is gepositioneerd.


**Returns:**
int - De relatieve verticale positiewaarde.

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


Haalt de hyperlink op die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld.


**Returns:**
java.lang.String - De hyperlink die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Stelt de hyperlink in die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De hyperlink die aan deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` is gekoppeld. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de breedte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` op in punten.


**Returns:**
double - De breedte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Stelt de breedte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De breedte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de hoogte op van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten.


**Returns:**
double - De hoogte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Stelt de hoogte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De hoogte van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punten. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Haalt de rotatiehoek van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in graden op.


**Returns:**
double - De rotatiehoek van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in graden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Stelt de rotatiehoek van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in graden in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De rotatiehoek van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in graden. |
|

### getX() {#getX--}
```
public final double getX()
```


Haalt op of stelt de horizontale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ten opzichte van de linkerrand van de pagina in punten in.


**Returns:**
double - De x-coördinaat van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Haalt op of stelt de horizontale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ten opzichte van de linkerrand van de pagina in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De x-coördinaat van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Haalt de verticale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vanaf de bovenrand van de pagina in punten op.


**Returns:**
double - De y-coördinaat van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Stelt de verticale offset van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` vanaf de bovenrand van de pagina in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De y-coördinaat van deze `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageData | byte[] |  |

