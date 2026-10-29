---
title: "PossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir belgede bulunan olası filigranı temsil eder."
type: docs
weight: 45
url: /tr/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Bir belgede bulunan olası filigranı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getParent()](#getParent--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin üst öğesini alır. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin genişliğini alır. |
|
|  | [getHeight()](#getHeight--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin yüksekliğini alır. |
|
|  | [getX()](#getX--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin x koordinatını alır. |
|
|  | [getY()](#getY--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin y koordinatını alır. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin derece cinsinden döndürme açısını alır. |
|
|  | [getText()](#getText--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin metnini ayarlar. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getImageData()](#getImageData--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin görüntüsünü alır veya ayarlar. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin ölçü birimini `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` alır. |
|
| [getCollection()](#getCollection--) |  |
| [setCollection(PossibleWatermarkCollection value)](#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-) |  |
| [getImageSize()](#getImageSize--) |  |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PossibleWatermark() {#PossibleWatermark--}
```
public PossibleWatermark()
```




### getParent() {#getParent--}
```
public abstract ContentPart getParent()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin üst öğesini alır.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getWidth() {#getWidth--}
```
public double getWidth()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin genişliğini alır.


**Returns:**
double - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin genişliği.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin yüksekliğini alır.


**Returns:**
double - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin yüksekliği.

### getX() {#getX--}
```
public double getX()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin x koordinatını alır.


**Returns:**
double - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin x-koordinatı.

### getY() {#getY--}
```
public double getY()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin y koordinatını alır.


**Returns:**
double - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin y-koordinatı.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin derece cinsinden döndürme açısını alır.


**Returns:**
double - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin döndürme açısı.

### getText() {#getText--}
```
public String getText()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin metnini alır.


**Returns:**
java.lang.String - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin metni.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin metnini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin metni. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin görüntüsünü alır veya ayarlar.


**Returns:**
byte[] - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin resmi veya filigranın resmi yoksa null.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin ölçü birimini `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` alır.


**Returns:**
int - Bu `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` öğesinin `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` ölçü birimi.

### getCollection() {#getCollection--}
```
public final PossibleWatermarkCollection getCollection()
```




**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### setCollection(PossibleWatermarkCollection value) {#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void setCollection(PossibleWatermarkCollection value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public abstract void remove()
```




