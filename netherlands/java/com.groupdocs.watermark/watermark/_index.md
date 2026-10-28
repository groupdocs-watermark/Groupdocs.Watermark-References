---
title: "Watermerk"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een watermerk voor dat aan een document moet worden toegevoegd."
type: docs
weight: 13
url: /nl/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Stelt een watermerk voor dat aan een document moet worden toegevoegd.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Haalt op of stelt de dekking van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Haalt op of stelt de dekking van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getY()](#getY--) | Haalt de y-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setY(double value)](#setY-double-) | Stelt de y-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getX()](#getX--) | Haalt de x-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setX(double value)](#setX-double-) | Stelt de x-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Haalt de verticale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Stelt de verticale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Haalt de horizontale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Stelt de horizontale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op in graden. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Stelt de rotatiehoek van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in graden in. |
|
|  | [isBackground()](#isBackground--) | Haalt een waarde op die aangeeft of het watermerk op de achtergrond moet worden geplaatst. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Stelt een waarde in die aangeeft of het watermerk op de achtergrond moet worden geplaatst. |
|
|  | [getMargins()](#getMargins--) | Haalt de marge-instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Stelt de marge-instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Haalt de paginaconfiguratie-instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Stelt de pagina‑instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getHeight()](#getHeight--) | Haalt de gewenste hoogte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setHeight(double value)](#setHeight-double-) | Stelt de gewenste hoogte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getWidth()](#getWidth--) | Haalt de gewenste breedte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op. |
|
|  | [setWidth(double value)](#setWidth-double-) | Stelt de gewenste breedte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Haalt een waarde op die definieert hoe de watermerkgrootte afhankelijk is van de oudergrootte. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Stelt een waarde in die definieert hoe de watermerkgrootte afhankelijk is van de oudergrootte. |
|
|  | [getSizingType()](#getSizingType--) | Haalt een waarde op die een manier specificeert waarop het watermerk moet worden geschaald. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Stelt een waarde in die een manier specificeert waarop het watermerk moet worden geschaald. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Haalt een waarde op die aangeeft of de watermerkgrootte en coördinaten worden berekend |
rekening houdend met de marges van de ouder.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Stelt een waarde in die aangeeft of de watermerkgrootte en coördinaten worden berekend |
rekening houdend met de marges van de ouder.
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


Haalt op of stelt de dekking van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.

De waarde van de dekking moet tussen 0 en 1 liggen. De standaardwaarde is 1.


**Returns:**
double - De dekking van deze `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Haalt op of stelt de dekking van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.

De waarde van de dekking moet tussen 0 en 1 liggen. De standaardwaarde is 1.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De dekking van deze `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Haalt de y-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.


**Returns:**
double - De y-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Stelt de y-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De y-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Haalt de x-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.


**Returns:**
double - De x-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Stelt de x-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De x-coördinaat van deze `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Haalt de verticale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.

Standaardwaarde is `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - De `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` van deze `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Stelt de verticale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.

Standaardwaarde is `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | int | De `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` van deze `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Haalt de horizontale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.

Standaardwaarde is `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - De `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` van deze `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Stelt de horizontale uitlijning van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.

Standaardwaarde is `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | int | De `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` van deze `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Haalt de rotatiehoek van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op in graden.


**Returns:**
double - De rotatiehoek van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in graden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Stelt de rotatiehoek van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in graden in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De rotatiehoek van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in graden. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Haalt een waarde op die aangeeft of het watermerk op de achtergrond moet worden geplaatst.


**Returns:**
boolean - Als de waarde true is, wordt het watermerk onderaan geplaatst. Standaard is de waarde false, wordt het watermerk bovenaan geplaatst.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Stelt een waarde in die aangeeft of het watermerk op de achtergrond moet worden geplaatst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Als de waarde true is, wordt het watermerk onderaan geplaatst. Standaard is de waarde false, wordt het watermerk bovenaan geplaatst. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Haalt de marge-instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Stelt de marge-instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | De marge‑instellingen van dit `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Haalt de paginaconfiguratie-instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Stelt de pagina‑instellingen van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | De paginaconfiguratie‑instellingen van dit `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de gewenste hoogte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.


**Returns:**
double - De gewenste hoogte van dit `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Stelt de gewenste hoogte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.

Het instellen van deze eigenschap wijzigt ook de waarde van `#getSizingType().getSizingType()`
eigenschap naar `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De gewenste hoogte van dit `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de gewenste breedte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` op.


**Returns:**
double - De gewenste breedte van dit `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Stelt de gewenste breedte van deze `[Watermark](../../com.groupdocs.watermark/watermark)` in.

Het instellen van deze eigenschap wijzigt ook de waarde van `#getSizingType().getSizingType()`
eigenschap naar `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De gewenste breedte van dit `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Haalt een waarde op die definieert hoe de watermerkgrootte afhankelijk is van de oudergrootte.

De waarde moet tussen 0 en 1 liggen.


**Returns:**
double - De schaalfactor van dit `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Stelt een waarde in die definieert hoe de watermerkgrootte afhankelijk is van de oudergrootte.

De waarde moet tussen 0 en 1 liggen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | double | De schaalfactor van dit `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Haalt een waarde op die een manier specificeert waarop het watermerk moet worden geschaald.


**Returns:**
int - Het type van de grootte.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Stelt een waarde in die een manier specificeert waarop het watermerk moet worden geschaald.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Het type van de grootte. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Haalt een waarde op die aangeeft of de watermerkgrootte en coördinaten worden berekend
rekening houdend met de marges van de ouder.


**Returns:**
boolean - Als de waarde true is, worden de grootte en coördinaten van het watermerk berekend met inachtneming van de bovenliggende marges. Standaard is de waarde false, worden de bovenliggende marges genegeerd.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Stelt een waarde in die aangeeft of de watermerkgrootte en coördinaten worden berekend
rekening houdend met de marges van de ouder.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Als de waarde true is, worden de grootte en coördinaten van het watermerk berekend met inachtneming van de bovenliggende marges. Standaard is de waarde false, worden de bovenliggende marges genegeerd. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
