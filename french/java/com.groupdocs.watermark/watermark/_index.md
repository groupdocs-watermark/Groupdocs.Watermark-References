---
title: "Filigrane"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un filigrane à ajouter à un document."
type: docs
weight: 13
url: /fr/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Représente un filigrane à ajouter à un document.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Obtient ou définit l'opacité de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Obtient ou définit l'opacité de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getY()](#getY--) | Obtient la coordonnée y de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setY(double value)](#setY-double-) | Définit la coordonnée y de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getX()](#getX--) | Obtient la coordonnée x de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setX(double value)](#setX-double-) | Définit la coordonnée x de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Obtient l'alignement vertical de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Définit l'alignement vertical de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Obtient l'alignement horizontal de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Définit l'alignement horizontal de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de ce `[Watermark](../../com.groupdocs.watermark/watermark)` en degrés. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Définit l'angle de rotation de ce `[Watermark](../../com.groupdocs.watermark/watermark)` en degrés. |
|
|  | [isBackground()](#isBackground--) | Obtient une valeur indiquant si le filigrane doit être placé en arrière-plan. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Définit une valeur indiquant si le filigrane doit être placé en arrière-plan. |
|
|  | [getMargins()](#getMargins--) | Obtient les paramètres de marge de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Définit les paramètres de marge de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Obtient les paramètres de configuration des pages de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Définit les paramètres de configuration des pages de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHeight(double value)](#setHeight-double-) | Définit la hauteur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setWidth(double value)](#setWidth-double-) | Définit la largeur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Obtient une valeur qui définit comment la taille du filigrane dépend de la taille du parent. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Définit une valeur qui définit comment la taille du filigrane dépend de la taille du parent. |
|
|  | [getSizingType()](#getSizingType--) | Obtient une valeur spécifiant la façon dont le filigrane doit être dimensionné. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Définit une valeur spécifiant la façon dont le filigrane doit être dimensionné. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Obtient une valeur indiquant si la taille et les coordonnées du filigrane sont calculées |
en tenant compte des marges du parent.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Définit une valeur indiquant si la taille et les coordonnées du filigrane sont calculées |
en tenant compte des marges du parent.
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


Obtient ou définit l'opacité de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La valeur d'opacité doit être comprise entre 0 et 1. La valeur par défaut est 1.


**Returns:**
double - L'opacité de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Obtient ou définit l'opacité de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La valeur d'opacité doit être comprise entre 0 et 1. La valeur par défaut est 1.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | L'opacité de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtient la coordonnée y de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La coordonnée y de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Définit la coordonnée y de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée y de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtient la coordonnée x de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La coordonnée x de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Définit la coordonnée x de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée x de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Obtient l'alignement vertical de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La valeur par défaut est `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - Le `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Définit l'alignement vertical de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La valeur par défaut est `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | int | Le `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Obtient l'alignement horizontal de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La valeur par défaut est `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - Le `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Définit l'alignement horizontal de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La valeur par défaut est `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | int | Le `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtient l'angle de rotation de ce `[Watermark](../../com.groupdocs.watermark/watermark)` en degrés.


**Returns:**
double - L'angle de rotation de ce `[Watermark](../../com.groupdocs.watermark/watermark)` en degrés.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Définit l'angle de rotation de ce `[Watermark](../../com.groupdocs.watermark/watermark)` en degrés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | L'angle de rotation de ce `[Watermark](../../com.groupdocs.watermark/watermark)` en degrés. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Obtient une valeur indiquant si le filigrane doit être placé en arrière-plan.


**Returns:**
boolean - Si la valeur est vraie, le filigrane sera placé en bas. Par défaut, la valeur est fausse, le filigrane sera placé en haut.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Définit une valeur indiquant si le filigrane doit être placé en arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Si la valeur est vraie, le filigrane sera placé en bas. Par défaut, la valeur est fausse, le filigrane sera placé en haut. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Obtient les paramètres de marge de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Définit les paramètres de marge de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Les paramètres de marge de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Obtient les paramètres de configuration des pages de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Définit les paramètres de configuration des pages de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Les paramètres de configuration des pages de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtient la hauteur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La hauteur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Définit la hauteur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La définition de cette propriété modifiera également la valeur de `#getSizingType().getSizingType()`
propriété à `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La hauteur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtient la largeur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - La largeur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Définit la largeur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

La définition de cette propriété modifiera également la valeur de `#getSizingType().getSizingType()`
propriété à `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La largeur souhaitée de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Obtient une valeur qui définit comment la taille du filigrane dépend de la taille du parent.

La valeur doit être comprise entre 0 et 1.


**Returns:**
double - Le facteur d'échelle de ce `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Définit une valeur qui définit comment la taille du filigrane dépend de la taille du parent.

La valeur doit être comprise entre 0 et 1.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | Le facteur d'échelle de ce `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Obtient une valeur spécifiant la façon dont le filigrane doit être dimensionné.


**Returns:**
int - Le type de dimensionnement.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Définit une valeur spécifiant la façon dont le filigrane doit être dimensionné.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Le type de dimensionnement. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Obtient une valeur indiquant si la taille et les coordonnées du filigrane sont calculées
en tenant compte des marges du parent.


**Returns:**
boolean - Si la valeur est vraie, la taille et les coordonnées du filigrane sont calculées en tenant compte des marges du parent. Par défaut, la valeur est fausse, les marges du parent sont ignorées.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Définit une valeur indiquant si la taille et les coordonnées du filigrane sont calculées
en tenant compte des marges du parent.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Si la valeur est vraie, la taille et les coordonnées du filigrane sont calculées en tenant compte des marges du parent. Par défaut, la valeur est fausse, les marges du parent sont ignorées. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
