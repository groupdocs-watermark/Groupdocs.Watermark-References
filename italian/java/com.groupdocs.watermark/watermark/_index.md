---
title: "Watermark"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un watermark da aggiungere a un documento."
type: docs
weight: 13
url: /it/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Rappresenta un watermark da aggiungere a un documento.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Ottiene o imposta l'opacità di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Ottiene o imposta l'opacità di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getY()](#getY--) | Ottiene la coordinata y di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setY(double value)](#setY-double-) | Imposta la coordinata y di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getX()](#getX--) | Ottiene la coordinata x di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setX(double value)](#setX-double-) | Imposta la coordinata x di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Ottiene l'allineamento verticale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Imposta l'allineamento verticale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Ottiene l'allineamento orizzontale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Imposta l'allineamento orizzontale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ottiene l'angolo di rotazione di questo `[Watermark](../../com.groupdocs.watermark/watermark)` in gradi. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Imposta l'angolo di rotazione di questo `[Watermark](../../com.groupdocs.watermark/watermark)` in gradi. |
|
|  | [isBackground()](#isBackground--) | Ottiene un valore che indica se il watermark deve essere posizionato sullo sfondo. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Imposta un valore che indica se il watermark deve essere posizionato sullo sfondo. |
|
|  | [getMargins()](#getMargins--) | Ottiene le impostazioni del margine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Imposta le impostazioni del margine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Ottiene le impostazioni di configurazione delle pagine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Imposta le impostazioni di configurazione delle pagine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHeight(double value)](#setHeight-double-) | Imposta l'altezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setWidth(double value)](#setWidth-double-) | Imposta la larghezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Ottiene un valore che definisce come la dimensione della filigrana dipende dalla dimensione del genitore. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Imposta un valore che definisce come la dimensione della filigrana dipende dalla dimensione del genitore. |
|
|  | [getSizingType()](#getSizingType--) | Ottiene un valore che specifica il modo in cui la filigrana dovrebbe essere dimensionata. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Imposta un valore che specifica il modo in cui la filigrana dovrebbe essere dimensionata. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Ottiene un valore che indica se la dimensione e le coordinate della filigrana sono calcolate |
considerando i margini del genitore.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Imposta un valore che indica se la dimensione e le coordinate della filigrana sono calcolate |
considerando i margini del genitore.
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


Ottiene o imposta l'opacità di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Il valore di opacità deve essere compreso tra 0 e 1. Il valore predefinito è 1.


**Returns:**
double - L'opacità di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Ottiene o imposta l'opacità di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Il valore di opacità deve essere compreso tra 0 e 1. Il valore predefinito è 1.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'opacità di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Ottiene la coordinata y di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La coordinata y di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Imposta la coordinata y di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata y di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Ottiene la coordinata x di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La coordinata x di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Imposta la coordinata x di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La coordinata x di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Ottiene l'allineamento verticale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Il valore predefinito è `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - Il `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Imposta l'allineamento verticale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Il valore predefinito è `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | int | Il `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Ottiene l'allineamento orizzontale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Il valore predefinito è `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - Il `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Imposta l'allineamento orizzontale di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Il valore predefinito è `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | int | Il `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Ottiene l'angolo di rotazione di questo `[Watermark](../../com.groupdocs.watermark/watermark)` in gradi.


**Returns:**
double - L'angolo di rotazione di questo `[Watermark](../../com.groupdocs.watermark/watermark)` in gradi.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Imposta l'angolo di rotazione di questo `[Watermark](../../com.groupdocs.watermark/watermark)` in gradi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'angolo di rotazione di questo `[Watermark](../../com.groupdocs.watermark/watermark)` in gradi. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Ottiene un valore che indica se il watermark deve essere posizionato sullo sfondo.


**Returns:**
boolean - Se il valore è true, il watermark verrà posizionato in basso. Per impostazione predefinita, il valore è false, il watermark verrà posizionato in alto.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Imposta un valore che indica se il watermark deve essere posizionato sullo sfondo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Se il valore è true, il watermark verrà posizionato in basso. Per impostazione predefinita, il valore è false, il watermark verrà posizionato in alto. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Ottiene le impostazioni del margine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Imposta le impostazioni del margine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Le impostazioni del margine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Ottiene le impostazioni di configurazione delle pagine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Imposta le impostazioni di configurazione delle pagine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Le impostazioni di configurazione delle pagine di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ottiene l'altezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - L'altezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Imposta l'altezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Impostare questa proprietà cambierà anche il valore di `#getSizingType().getSizingType()`
proprietà a `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | L'altezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ottiene la larghezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La larghezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Imposta la larghezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

Impostare questa proprietà cambierà anche il valore di `#getSizingType().getSizingType()`
proprietà a `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | La larghezza desiderata di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Ottiene un valore che definisce come la dimensione della filigrana dipende dalla dimensione del genitore.

Il valore deve essere compreso tra 0 e 1.


**Returns:**
double - Il fattore di scala di questo `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Imposta un valore che definisce come la dimensione della filigrana dipende dalla dimensione del genitore.

Il valore deve essere compreso tra 0 e 1.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | double | Il fattore di scala di questo `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Ottiene un valore che specifica il modo in cui la filigrana dovrebbe essere dimensionata.


**Returns:**
int - Il tipo di dimensionamento.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Imposta un valore che specifica il modo in cui la filigrana dovrebbe essere dimensionata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il tipo di dimensionamento. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Ottiene un valore che indica se la dimensione e le coordinate della filigrana sono calcolate
considerando i margini del genitore.


**Returns:**
boolean - Se il valore è true, la dimensione e le coordinate del watermark vengono calcolate considerando i margini del genitore. Per impostazione predefinita, il valore è false, i margini del genitore sono ignorati.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Imposta un valore che indica se la dimensione e le coordinate della filigrana sono calcolate
considerando i margini del genitore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Se il valore è true, la dimensione e le coordinate del watermark vengono calcolate considerando i margini del genitore. Per impostazione predefinita, il valore è false, i margini del genitore sono ignorati. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
