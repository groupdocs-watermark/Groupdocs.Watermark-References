---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller den abstrakta basklassen för former av alla typer i ett PowerPoint-dokument."
type: docs
weight: 77
url: /sv/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Tillhandahåller den abstrakta basklassen för former av alla typer i ett PowerPoint-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Hämtar föräldrapresentationen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Hämtar bildfyllnadsformatinställningarna för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getName()](#getName--) | Hämtar namnet på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Hämtar den beskrivande (alternativa) texten som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ställer in den beskrivande (alternativa) texten som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getId()](#getId--) | Hämtar identifieraren för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Hämtar positionen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i z-ordningen. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Hämtar hyperlänken som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Ställer in hyperlänken som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens vänstra kant i punkter. |
|
|  | [setX(double value)](#setX-double-) | Ställer in den horisontella förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar eller ställer in den vertikala förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens övre kant i punkter. |
|
|  | [setY(double value)](#setY-double-) | Hämtar eller ställer in den vertikala förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens övre kant i punkter. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ställer in bredden för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ställer in höjden på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Hämtar föräldrapresentationen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Hämtar bildfyllnadsformatinställningarna för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Namnet på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Hämtar den beskrivande (alternativa) texten som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Den beskrivande (alternativa) texten som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ställer in den beskrivande (alternativa) texten som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Den beskrivande (alternativa) texten som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Hämtar identifieraren för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
long - Identifieraren för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Hämtar positionen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i z-ordningen.

En form med högre z-ordning är alltid framför en form med lägre z-ordning.


**Returns:**
int - Positionen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i z-ordningen.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Hämtar hyperlänken som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | actionType | int | Åtgärden som aktiverar hyperlänken. |
|

**Returns:**
java.lang.String - URL:en för hyperlänken som aktiveras vid angiven åtgärd.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Ställer in hyperlänken som är associerad med detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | actionType | int | Åtgärden som aktiverar hyperlänken. |
|
|  | url | java.lang.String | Hyperlänkens URL. |
|

### getX() {#getX--}
```
public final double getX()
```


Hämtar den horisontella förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens vänstra kant i punkter.


**Returns:**
double - X-koordinaten för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ställer in den horisontella förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens vänstra kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | X-koordinaten för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Hämtar eller ställer in den vertikala förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens övre kant i punkter.


**Returns:**
double - Y-koordinaten för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Hämtar eller ställer in den vertikala förskjutningen för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` från presentationens övre kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Y-koordinaten för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar bredden för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter.


**Returns:**
double - Bredden på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ställer in bredden för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Bredden på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar höjden för detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter.


**Returns:**
double - Höjden på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ställer in höjden på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Höjden på detta `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` i punkter. |
|

