---
title: "Wasserzeichen"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Wasserzeichen dar, das zu einem Dokument hinzugefügt wird."
type: docs
weight: 13
url: /de/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Stellt ein Wasserzeichen dar, das zu einem Dokument hinzugefügt wird.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Liest oder setzt die Deckkraft dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Liest oder setzt die Deckkraft dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getY()](#getY--) | Liest die y-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setY(double value)](#setY-double-) | Setzt die y-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getX()](#getX--) | Liest die x-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setX(double value)](#setX-double-) | Setzt die x-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Liest die vertikale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Setzt die vertikale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Liest die horizontale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Setzt die horizontale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Liest den Rotationswinkel dieses `[Watermark](../../com.groupdocs.watermark/watermark)` in Grad. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Setzt den Rotationswinkel dieses `[Watermark](../../com.groupdocs.watermark/watermark)` in Grad. |
|
|  | [isBackground()](#isBackground--) | Liest einen Wert, der angibt, ob das Wasserzeichen im Hintergrund platziert werden soll. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Setzt einen Wert, der angibt, ob das Wasserzeichen im Hintergrund platziert werden soll. |
|
|  | [getMargins()](#getMargins--) | Liest die Rand-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Setzt die Rand-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Liest die Seiteneinrichtungs-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Legt die Seiteneinrichtungseinstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)` fest. |
|
|  | [getHeight()](#getHeight--) | Ermittelt die gewünschte Höhe dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHeight(double value)](#setHeight-double-) | Legt die gewünschte Höhe dieses `[Watermark](../../com.groupdocs.watermark/watermark)` fest. |
|
|  | [getWidth()](#getWidth--) | Ermittelt die gewünschte Breite dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setWidth(double value)](#setWidth-double-) | Legt die gewünschte Breite dieses `[Watermark](../../com.groupdocs.watermark/watermark)` fest. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Ermittelt einen Wert, der definiert, wie die watermark-Größe von der übergeordneten Größe abhängt. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Legt einen Wert fest, der definiert, wie die watermark-Größe von der übergeordneten Größe abhängt. |
|
|  | [getSizingType()](#getSizingType--) | Ermittelt einen Wert, der angibt, wie das watermark dimensioniert werden soll. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Legt einen Wert fest, der angibt, wie das watermark dimensioniert werden soll. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Ermittelt einen Wert, der angibt, ob die watermark-Größe und -Koordinaten berechnet werden |
unter Berücksichtigung der übergeordneten Ränder.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Legt einen Wert fest, der angibt, ob die watermark-Größe und -Koordinaten berechnet werden |
unter Berücksichtigung der übergeordneten Ränder.
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Liest oder setzt die Deckkraft dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

Der Wert für die Deckkraft sollte zwischen 0 und 1 liegen. Der Standardwert ist 1.


**Returns:**
double - Die Deckkraft dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Liest oder setzt die Deckkraft dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

Der Wert für die Deckkraft sollte zwischen 0 und 1 liegen. Der Standardwert ist 1.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die Deckkraft dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Liest die y-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Die y‑Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Setzt die y-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die y‑Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Liest die x-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Die x‑Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Setzt die x-Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die x‑Koordinate dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Liest die vertikale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardwert ist `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - Die `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Setzt die vertikale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardwert ist `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Liest die horizontale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardwert ist `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - Die `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Setzt die horizontale Ausrichtung dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardwert ist `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Liest den Rotationswinkel dieses `[Watermark](../../com.groupdocs.watermark/watermark)` in Grad.


**Returns:**
double - Der Rotationswinkel dieses `[Watermark](../../com.groupdocs.watermark/watermark)` in Grad.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Setzt den Rotationswinkel dieses `[Watermark](../../com.groupdocs.watermark/watermark)` in Grad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der Rotationswinkel dieses `[Watermark](../../com.groupdocs.watermark/watermark)` in Grad. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Liest einen Wert, der angibt, ob das Wasserzeichen im Hintergrund platziert werden soll.


**Returns:**
boolean - Wenn der Wert true ist, wird das Wasserzeichen unten platziert. Standardmäßig ist der Wert false, das Wasserzeichen wird oben platziert.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Setzt einen Wert, der angibt, ob das Wasserzeichen im Hintergrund platziert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wenn der Wert true ist, wird das Wasserzeichen unten platziert. Standardmäßig ist der Wert false, das Wasserzeichen wird oben platziert. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Liest die Rand-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Setzt die Rand-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Die Rand-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Liest die Seiteneinrichtungs-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Legt die Seiteneinrichtungseinstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)` fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Die Seiteneinrichtungs-Einstellungen dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ermittelt die gewünschte Höhe dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Die gewünschte Höhe dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Legt die gewünschte Höhe dieses `[Watermark](../../com.groupdocs.watermark/watermark)` fest.

Das Setzen dieser Eigenschaft ändert auch den Wert von `#getSizingType().getSizingType()`.
Eigenschaft zu `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die gewünschte Höhe dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ermittelt die gewünschte Breite dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Die gewünschte Breite dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Legt die gewünschte Breite dieses `[Watermark](../../com.groupdocs.watermark/watermark)` fest.

Das Setzen dieser Eigenschaft ändert auch den Wert von `#getSizingType().getSizingType()`.
Eigenschaft zu `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Die gewünschte Breite dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Ermittelt einen Wert, der definiert, wie die watermark-Größe von der übergeordneten Größe abhängt.

Der Wert muss zwischen 0 und 1 liegen.


**Returns:**
double - Der Skalierungsfaktor dieses `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Legt einen Wert fest, der definiert, wie die watermark-Größe von der übergeordneten Größe abhängt.

Der Wert muss zwischen 0 und 1 liegen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | double | Der Skalierungsfaktor dieses `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Ermittelt einen Wert, der angibt, wie das watermark dimensioniert werden soll.


**Returns:**
int - Der Größenanpassungstyp.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Legt einen Wert fest, der angibt, wie das watermark dimensioniert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Größenanpassungstyp. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Ermittelt einen Wert, der angibt, ob die watermark-Größe und -Koordinaten berechnet werden
unter Berücksichtigung der übergeordneten Ränder.


**Returns:**
boolean - Wenn der Wert true ist, werden Wasserzeichengröße und -koordinaten unter Berücksichtigung der übergeordneten Ränder berechnet. Standardmäßig ist der Wert false, übergeordnete Ränder werden ignoriert.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Legt einen Wert fest, der angibt, ob die watermark-Größe und -Koordinaten berechnet werden
unter Berücksichtigung der übergeordneten Ränder.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Wenn der Wert true ist, werden Wasserzeichengröße und -koordinaten unter Berücksichtigung der übergeordneten Ränder berechnet. Standardmäßig ist der Wert false, übergeordnete Ränder werden ignoriert. |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
