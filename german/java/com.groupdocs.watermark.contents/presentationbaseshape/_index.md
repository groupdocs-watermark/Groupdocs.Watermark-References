---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die abstrakte Basisklasse für Formen aller Typen in einem PowerPoint-Dokument bereit."
type: docs
weight: 77
url: /de/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Stellt die abstrakte Basisklasse für Formen aller Typen in einem PowerPoint-Dokument bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Ermittelt die übergeordnete Präsentation dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Ermittelt die Einstellungen des Bildfüllformats dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getName()](#getName--) | Ermittelt den Namen dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ermittelt den beschreibenden (alternativen) Text, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Setzt den beschreibenden (alternativen) Text, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist. |
|
|  | [getId()](#getId--) | Ermittelt den Bezeichner dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Ermittelt die Position dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in der Z-Reihenfolge. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Ermittelt den Hyperlink, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Setzt den Hyperlink, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist. |
|
|  | [getX()](#getX--) | Ermittelt den horizontalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der linken Präsentationskante in Punkten. |
|
|  | [setX(double value)](#setX-double-) | Setzt den horizontalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der linken Präsentationskante in Punkten. |
|
|  | [getY()](#getY--) | Ermittelt oder setzt den vertikalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der oberen Präsentationskante in Punkten. |
|
|  | [setY(double value)](#setY-double-) | Ermittelt oder setzt den vertikalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der oberen Präsentationskante in Punkten. |
|
|  | [getWidth()](#getWidth--) | Ermittelt die Breite dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Setzt die Breite dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten. |
|
|  | [getHeight()](#getHeight--) | Ermittelt die Höhe dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Setzt die Höhe dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Ermittelt die übergeordnete Präsentation dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Ermittelt die Einstellungen des Bildfüllformats dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Ermittelt den Namen dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Der Name dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Ermittelt den beschreibenden (alternativen) Text, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist.


**Returns:**
java.lang.String - Der beschreibende (alternative) Text, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Setzt den beschreibenden (alternativen) Text, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der beschreibende (alternative) Text, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist. |
|

### getId() {#getId--}
```
public final long getId()
```


Ermittelt den Bezeichner dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
long - Der Bezeichner dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Ermittelt die Position dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in der Z-Reihenfolge.

Eine Form mit höherer Z-Reihenfolge steht immer vor einer Form mit niedrigerer Z-Reihenfolge.


**Returns:**
int - Die Position dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in der Z‑Reihenfolge.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Ermittelt den Hyperlink, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | actionType | int | Die Aktion, die den Hyperlink aktiviert. |
|

**Returns:**
java.lang.String - Die URL des Hyperlinks, der bei der angegebenen Aktion aktiviert wird.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Setzt den Hyperlink, der mit diesem `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | actionType | int | Die Aktion, die den Hyperlink aktiviert. |
|
|  | URL | java.lang.String | Die URL des Hyperlinks. |
|

### getX() {#getX--}
```
public final double getX()
```


Ermittelt den horizontalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der linken Präsentationskante in Punkten.


**Returns:**
double - Die x‑Koordinate dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Setzt den horizontalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der linken Präsentationskante in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die x‑Koordinate dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Ermittelt oder setzt den vertikalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der oberen Präsentationskante in Punkten.


**Returns:**
double - Die y‑Koordinate dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ermittelt oder setzt den vertikalen Versatz dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` von der oberen Präsentationskante in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die y‑Koordinate dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ermittelt die Breite dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten.


**Returns:**
double - Die Breite dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Setzt die Breite dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Breite dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ermittelt die Höhe dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten.


**Returns:**
double - Die Höhe dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Setzt die Höhe dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Höhe dieses `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` in Punkten. |
|

