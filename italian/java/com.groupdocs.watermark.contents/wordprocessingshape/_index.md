---
title: "WordProcessingShape"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una forma di disegno in un documento Word."
type: docs
weight: 141
url: /it/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Rappresenta una forma di disegno in un documento Word.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSection()](#getSection--) | Ottiene la sezione padre di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Ottiene l'intestazione/piè di pagina padre di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (se presente). |
|
|  | [getShapeType()](#getShapeType--) | Ottiene il tipo di forma. |
|
|  | [isWordArt()](#isWordArt--) | Ottiene un valore che indica se questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` è un oggetto WordArt. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ottiene il testo descrittivo (alternativo) associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Imposta il testo descrittivo (alternativo) associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getName()](#getName--) | Ottiene il nome di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getBehindText()](#getBehindText--) | Ottiene un valore che indica se la forma è sopra o dietro il testo. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Imposta un valore che indica se la forma è sopra o dietro il testo. |
|
|  | [getText()](#getText--) | Ottiene il testo di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Imposta il testo di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ottiene la collezione di frammenti di testo formattato di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getImage()](#getImage--) | Ottiene l'immagine di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Imposta l'immagine di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Ottiene un valore che specifica come la forma è posizionata orizzontalmente. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Ottiene un valore che specifica come la forma è posizionata verticalmente. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Ottiene un valore che specifica rispetto a cosa la forma è posizionata orizzontalmente. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Ottiene un valore che specifica rispetto a cosa la forma è posizionata verticalmente. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Ottiene il collegamento ipertestuale associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Imposta il collegamento ipertestuale associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti. |
|
|  | [setWidth(double value)](#setWidth-double-) | Imposta la larghezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti. |
|
|  | [setHeight(double value)](#setHeight-double-) | Imposta l'altezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in gradi. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Imposta l'angolo di rotazione di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in gradi. |
|
|  | [getX()](#getX--) | Ottiene o imposta lo spostamento orizzontale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo sinistro della pagina in punti. |
|
|  | [setX(double value)](#setX-double-) | Ottiene o imposta lo spostamento orizzontale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo sinistro della pagina in punti. |
|
|  | [getY()](#getY--) | Ottiene lo spostamento verticale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo superiore della pagina in punti. |
|
|  | [setY(double value)](#setY-double-) | Imposta lo spostamento verticale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo superiore della pagina in punti. |
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


Ottiene la sezione padre di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Ottiene l'intestazione/piè di pagina padre di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (se presente).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Ottiene il tipo di forma.


**Returns:**
int - Il tipo di forma.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Ottiene un valore che indica se questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` è un oggetto WordArt.


**Returns:**
boolean - True se la forma è un oggetto WordArt; altrimenti, false.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Ottiene il testo descrittivo (alternativo) associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Il testo descrittivo (alternativo) associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Imposta il testo descrittivo (alternativo) associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo descrittivo (alternativo) associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Il nome di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Ottiene un valore che indica se la forma è sopra o dietro il testo.


**Returns:**
boolean - Il valore che indica se la forma è sopra o dietro il testo. True se la forma è dietro il testo; altrimenti, false.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Imposta un valore che indica se la forma è sopra o dietro il testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Il valore che indica se la forma è sopra o dietro il testo. True se la forma è dietro il testo; altrimenti, false. |
|

### getText() {#getText--}
```
public final String getText()
```


Ottiene il testo di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Il testo di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Imposta il testo di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | Il testo di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Ottiene la collezione di frammenti di testo formattato di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Ottiene l'immagine di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Imposta l'immagine di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | L'immagine di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` o `null` se l'immagine deve essere rimossa. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Ottiene un valore che specifica come la forma è posizionata orizzontalmente.


**Returns:**
int - Il valore di allineamento orizzontale.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Ottiene un valore che specifica come la forma è posizionata verticalmente.


**Returns:**
int - Il valore di allineamento verticale.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Ottiene un valore che specifica rispetto a cosa la forma è posizionata orizzontalmente.


**Returns:**
int - Il valore della posizione orizzontale relativa.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Ottiene un valore che specifica rispetto a cosa la forma è posizionata verticalmente.


**Returns:**
int - Il valore della posizione verticale relativa.

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


Ottiene il collegamento ipertestuale associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - L'collegamento ipertestuale associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Imposta il collegamento ipertestuale associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | java.lang.String | L'collegamento ipertestuale associato a questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ottiene la larghezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti.


**Returns:**
double - La larghezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Imposta la larghezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La larghezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ottiene l'altezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti.


**Returns:**
double - L'altezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Imposta l'altezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'altezza di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in punti. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in gradi.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Imposta l'angolo di rotazione di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in gradi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'angolo di rotazione di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` in gradi. |
|

### getX() {#getX--}
```
public final double getX()
```


Ottiene o imposta lo spostamento orizzontale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo sinistro della pagina in punti.


**Returns:**
double - La coordinata x di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ottiene o imposta lo spostamento orizzontale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo sinistro della pagina in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata x di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Ottiene lo spostamento verticale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo superiore della pagina in punti.


**Returns:**
double - La coordinata y di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Imposta lo spostamento verticale di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` dal bordo superiore della pagina in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata y di questo `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageData | byte[] |  |

