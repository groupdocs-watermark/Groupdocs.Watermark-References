---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt de abstracte basisklasse voor vormen van alle types in een PowerPoint-document."
type: docs
weight: 77
url: /nl/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Biedt de abstracte basisklasse voor vormen van alle types in een PowerPoint-document.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Haalt de bovenliggende presentatie van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Haalt de instellingen voor het afbeeldingsvullingsformaat van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op. |
|
|  | [getName()](#getName--) | Haalt de naam van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Haalt de beschrijvende (alternatieve) tekst op die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Stelt de beschrijvende (alternatieve) tekst in die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld. |
|
|  | [getId()](#getId--) | Haalt de identifier van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Haalt de positie van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in de z-volgorde op. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Haalt de hyperlink op die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Stelt de hyperlink in die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld. |
|
|  | [getX()](#getX--) | Haalt de horizontale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de linkerrand van de presentatie op in punten. |
|
|  | [setX(double value)](#setX-double-) | Stelt de horizontale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de linkerrand van de presentatie in punten in. |
|
|  | [getY()](#getY--) | Haalt of stelt de verticale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de bovengrens van de presentatie in punten in. |
|
|  | [setY(double value)](#setY-double-) | Haalt of stelt de verticale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de bovengrens van de presentatie in punten in. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten op. |
|
|  | [setWidth(double value)](#setWidth-double-) | Stelt de breedte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten in. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten op. |
|
|  | [setHeight(double value)](#setHeight-double-) | Stelt de hoogte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten in. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Haalt de bovenliggende presentatie van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Haalt de instellingen voor het afbeeldingsvullingsformaat van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op.


**Returns:**
java.lang.String - De naam van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Haalt de beschrijvende (alternatieve) tekst op die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld.


**Returns:**
java.lang.String - De beschrijvende (alternatieve) tekst die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Stelt de beschrijvende (alternatieve) tekst in die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De beschrijvende (alternatieve) tekst die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld. |
|

### getId() {#getId--}
```
public final long getId()
```


Haalt de identifier van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` op.


**Returns:**
long - De identifier van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Haalt de positie van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in de z-volgorde op.

Een vorm met een hogere z-volgorde staat altijd voor een vorm met een lagere z-volgorde.


**Returns:**
int - De positie van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in de z-volgorde.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Haalt de hyperlink op die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | actionType | int | De actie die de hyperlink activeert. |
|

**Returns:**
java.lang.String - De url van de hyperlink die wordt geactiveerd bij de opgegeven actie.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Stelt de hyperlink in die aan dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | actionType | int | De actie die de hyperlink activeert. |
|
|  | url | java.lang.String | De hyperlink‑url. |
|

### getX() {#getX--}
```
public final double getX()
```


Haalt de horizontale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de linkerrand van de presentatie op in punten.


**Returns:**
double - De x-coördinaat van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Stelt de horizontale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de linkerrand van de presentatie in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De x-coördinaat van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Haalt of stelt de verticale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de bovengrens van de presentatie in punten in.


**Returns:**
double - De y-coördinaat van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Haalt of stelt de verticale offset van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` ten opzichte van de bovengrens van de presentatie in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De y-coördinaat van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de breedte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten op.


**Returns:**
double - De breedte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Stelt de breedte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De breedte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de hoogte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten op.


**Returns:**
double - De hoogte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Stelt de hoogte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De hoogte van dit `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in punten. |
|

