---
title: "Watermark"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en vattenstämpel som ska läggas till i ett dokument."
type: docs
weight: 13
url: /sv/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Representerar en vattenstämpel som ska läggas till i ett dokument.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Hämtar eller ställer in opaciteten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Hämtar eller ställer in opaciteten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getY()](#getY--) | Hämtar y-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setY(double value)](#setY-double-) | Ställer in y-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getX()](#getX--) | Hämtar x-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setX(double value)](#setX-double-) | Ställer in x-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Hämtar den vertikala justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Ställer in den vertikala justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Hämtar den horisontella justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Ställer in den horisontella justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för denna `[Watermark](../../com.groupdocs.watermark/watermark)` i grader. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ställer in rotationsvinkeln för denna `[Watermark](../../com.groupdocs.watermark/watermark)` i grader. |
|
|  | [isBackground()](#isBackground--) | Hämtar ett värde som indikerar om vattenmärket ska placeras i bakgrunden. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Ställer in ett värde som indikerar om vattenmärket ska placeras i bakgrunden. |
|
|  | [getMargins()](#getMargins--) | Hämtar marginalinställningarna för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Ställer in marginalinställningarna för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Hämtar sidinställningarna för denna `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Ställer in sidinställningarna för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHeight()](#getHeight--) | Hämtar önskad höjd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ställer in önskad höjd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getWidth()](#getWidth--) | Hämtar önskad bredd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ställer in önskad bredd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Hämtar ett värde som definierar hur vattenstämpelns storlek beror på förälderns storlek. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Ställer in ett värde som definierar hur vattenstämpelns storlek beror på förälderns storlek. |
|
|  | [getSizingType()](#getSizingType--) | Hämtar ett värde som specificerar hur vattenstämpeln ska storleksanpassas. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Ställer in ett värde som specificerar hur vattenstämpeln ska storleksanpassas. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Hämtar ett värde som indikerar om vattenstämpelns storlek och koordinater beräknas |
med hänsyn till föräldramarginaler.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Ställer in ett värde som indikerar om vattenstämpelns storlek och koordinater beräknas |
med hänsyn till föräldramarginaler.
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


Hämtar eller ställer in opaciteten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.

Opacitetsvärdet bör vara mellan 0 och 1. Standardvärdet är 1.


**Returns:**
double - Opaciteten för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Hämtar eller ställer in opaciteten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.

Opacitetsvärdet bör vara mellan 0 och 1. Standardvärdet är 1.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Opaciteten för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Hämtar y-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Y-koordinaten för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ställer in y-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Y-koordinaten för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Hämtar x-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - X-koordinaten för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ställer in x-koordinaten för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | X-koordinaten för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Hämtar den vertikala justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardvärdet är `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Ställer in den vertikala justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardvärdet är `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Den `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Hämtar den horisontella justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardvärdet är `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Ställer in den horisontella justeringen för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.

Standardvärdet är `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Den `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Hämtar rotationsvinkeln för denna `[Watermark](../../com.groupdocs.watermark/watermark)` i grader.


**Returns:**
double - Rotationsvinkeln för detta `[Watermark](../../com.groupdocs.watermark/watermark)` i grader.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ställer in rotationsvinkeln för denna `[Watermark](../../com.groupdocs.watermark/watermark)` i grader.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Rotationsvinkeln för detta `[Watermark](../../com.groupdocs.watermark/watermark)` i grader. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Hämtar ett värde som indikerar om vattenmärket ska placeras i bakgrunden.


**Returns:**
boolean - Om värdet är true placeras vattenstämpeln längst ner. Som standard är värdet false, vattenstämpeln placeras högst upp.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Ställer in ett värde som indikerar om vattenmärket ska placeras i bakgrunden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Om värdet är true placeras vattenstämpeln längst ner. Som standard är värdet false, vattenstämpeln placeras högst upp. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Hämtar marginalinställningarna för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Ställer in marginalinställningarna för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Marginalinställningarna för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Hämtar sidinställningarna för denna `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Ställer in sidinställningarna för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Sidinställningarna för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar önskad höjd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Den önskade höjden för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ställer in önskad höjd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

Att sätta denna egenskap kommer också att ändra värdet på `#getSizingType().getSizingType()`
egenskap till `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Den önskade höjden för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar önskad bredd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Den önskade bredden för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ställer in önskad bredd för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

Att sätta denna egenskap kommer också att ändra värdet på `#getSizingType().getSizingType()`
egenskap till `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Den önskade bredden för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Hämtar ett värde som definierar hur vattenstämpelns storlek beror på förälderns storlek.

Värdet måste vara mellan 0 och 1.


**Returns:**
double - Skalfaktorn för detta `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Ställer in ett värde som definierar hur vattenstämpelns storlek beror på förälderns storlek.

Värdet måste vara mellan 0 och 1.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Skalfaktorn för detta `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Hämtar ett värde som specificerar hur vattenstämpeln ska storleksanpassas.


**Returns:**
int - Storlekstypen.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Ställer in ett värde som specificerar hur vattenstämpeln ska storleksanpassas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Storlekstypen. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Hämtar ett värde som indikerar om vattenstämpelns storlek och koordinater beräknas
med hänsyn till föräldramarginaler.


**Returns:**
boolean - Om värdet är true beräknas vattenstämpelns storlek och koordinater med hänsyn till föräldramarginaler. Som standard är värdet false, föräldramarginaler ignoreras.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Ställer in ett värde som indikerar om vattenstämpelns storlek och koordinater beräknas
med hänsyn till föräldramarginaler.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Om värdet är true beräknas vattenstämpelns storlek och koordinater med hänsyn till föräldramarginaler. Som standard är värdet false, föräldramarginaler ignoreras. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
