---
title: "Filigran"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir belgeye eklenecek filigranı temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Bir belgeye eklenecek filigranı temsil eder.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin opaklığını alır veya ayarlar. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin opaklığını alır veya ayarlar. |
|
|  | [getY()](#getY--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin y koordinatını alır. |
|
|  | [setY(double value)](#setY-double-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin y koordinatını ayarlar. |
|
|  | [getX()](#getX--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin x koordinatını alır. |
|
|  | [setX(double value)](#setX-double-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin x koordinatını ayarlar. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin dikey hizalamasını alır. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin dikey hizalamasını ayarlar. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin yatay hizalamasını alır. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin yatay hizalamasını ayarlar. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin derece cinsinden döndürme açısını alır. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin derece cinsinden döndürme açısını ayarlar. |
|
|  | [isBackground()](#isBackground--) | Filigranın arka plana yerleştirilip yerleştirilmeyeceğini belirten bir değeri alır. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Filigranın arka plana yerleştirilip yerleştirilmeyeceğini belirten bir değeri ayarlar. |
|
|  | [getMargins()](#getMargins--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin kenar boşluğu ayarlarını alır. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin kenar boşluğu ayarlarını ayarlar. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin sayfa kurulum ayarlarını alır. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin sayfa kurulum ayarlarını ayarlar. |
|
|  | [getHeight()](#getHeight--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen yüksekliğini alır. |
|
|  | [setHeight(double value)](#setHeight-double-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen yüksekliğini ayarlar. |
|
|  | [getWidth()](#getWidth--) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen genişliğini alır. |
|
|  | [setWidth(double value)](#setWidth-double-) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen genişliğini ayarlar. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Filigran boyutunun ebeveyn boyutuna nasıl bağlı olduğunu tanımlayan bir değeri alır. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Filigran boyutunun ebeveyn boyutuna nasıl bağlı olduğunu tanımlayan bir değeri ayarlar. |
|
|  | [getSizingType()](#getSizingType--) | Filigranın nasıl boyutlandırılması gerektiğini belirten bir değeri alır. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Filigranın nasıl boyutlandırılması gerektiğini belirten bir değeri ayarlar. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Filigran boyutu ve koordinatlarının hesaplanıp hesaplanmadığını gösteren bir değeri alır |
ebeveyn kenar boşlukları dikkate alınarak.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Filigran boyutu ve koordinatlarının hesaplanıp hesaplanmadığını gösteren bir değeri ayarlar |
ebeveyn kenar boşlukları dikkate alınarak.
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


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin opaklığını alır veya ayarlar.

Saydamlık değeri 0 ile 1 arasında olmalıdır. Varsayılan değer 1'dir.


**Returns:**
double - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin saydamlığı.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin opaklığını alır veya ayarlar.

Saydamlık değeri 0 ile 1 arasında olmalıdır. Varsayılan değer 1'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin saydamlığı. |
|

### getY() {#getY--}
```
public final double getY()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin y koordinatını alır.


**Returns:**
double - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin y-koordinatı.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin y koordinatını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin y-koordinatı. |
|

### getX() {#getX--}
```
public final double getX()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin x koordinatını alır.


**Returns:**
double - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin x-koordinatı.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin x koordinatını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin x-koordinatı. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin dikey hizalamasını alır.

Varsayılan değer `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` değeri.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin dikey hizalamasını ayarlar.

Varsayılan değer `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` değeri. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin yatay hizalamasını alır.

Varsayılan değer `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` değeri.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin yatay hizalamasını ayarlar.

Varsayılan değer `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` özelliği. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin derece cinsinden döndürme açısını alır.


**Returns:**
double - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin derece cinsinden döndürme açısı.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin derece cinsinden döndürme açısını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin derece cinsinden döndürme açısı. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Filigranın arka plana yerleştirilip yerleştirilmeyeceğini belirten bir değeri alır.


**Returns:**
boolean - Değer true ise, filigran alt kısma yerleştirilecektir. Varsayılan olarak, değer false ise, filigran üst kısma yerleştirilecektir.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Filigranın arka plana yerleştirilip yerleştirilmeyeceğini belirten bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Değer true ise, filigran alt kısma yerleştirilecektir. Varsayılan olarak, değer false ise, filigran üst kısma yerleştirilecektir. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin kenar boşluğu ayarlarını alır.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` nesnesinin kenar boşluğu ayarlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin kenar boşluğu ayarları. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin sayfa kurulum ayarlarını alır.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin sayfa kurulum ayarlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin sayfa ayarları. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen yüksekliğini alır.


**Returns:**
double - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen yüksekliği.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen yüksekliğini ayarlar.

Bu özelliği ayarlamak, `#getSizingType().getSizingType()` değerini de değiştirecektir.
özellik `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)` olarak.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen yüksekliği. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen genişliğini alır.


**Returns:**
double - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen genişliği.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen genişliğini ayarlar.

Bu özelliği ayarlamak, `#getSizingType().getSizingType()` değerini de değiştirecektir.
özellik `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)` olarak.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin istenen genişliği. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Filigran boyutunun ebeveyn boyutuna nasıl bağlı olduğunu tanımlayan bir değeri alır.

Değer 0 ile 1 arasında olmalıdır.


**Returns:**
double - Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin ölçek faktörü.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Filigran boyutunun ebeveyn boyutuna nasıl bağlı olduğunu tanımlayan bir değeri ayarlar.

Değer 0 ile 1 arasında olmalıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[Watermark](../../com.groupdocs.watermark/watermark)` öğesinin ölçek faktörü. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Filigranın nasıl boyutlandırılması gerektiğini belirten bir değeri alır.


**Returns:**
int - Boyutlandırma türü.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Filigranın nasıl boyutlandırılması gerektiğini belirten bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Boyutlandırma türü. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Filigran boyutu ve koordinatlarının hesaplanıp hesaplanmadığını gösteren bir değeri alır
ebeveyn kenar boşlukları dikkate alınarak.


**Returns:**
boolean - Değer true ise, filigran boyutu ve koordinatları üst (parent) kenar boşlukları dikkate alınarak hesaplanır. Varsayılan olarak, değer false ise, üst kenar boşlukları göz ardı edilir.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Filigran boyutu ve koordinatlarının hesaplanıp hesaplanmadığını gösteren bir değeri ayarlar
ebeveyn kenar boşlukları dikkate alınarak.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Değer true ise, filigran boyutu ve koordinatları üst kenar boşlukları dikkate alınarak hesaplanır. Varsayılan olarak, değer false ise, üst kenar boşlukları göz ardı edilir. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
