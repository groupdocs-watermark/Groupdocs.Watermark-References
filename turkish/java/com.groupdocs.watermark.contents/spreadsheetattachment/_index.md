---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesine eklenmiş bir dosyayı temsil eder."
type: docs
weight: 101
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Excel belgesine eklenmiş bir dosyayı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getContent()](#getContent--) | Ekli dosya içeriğini alır. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ekli dosya içeriğini ayarlar. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Ekli dosyanın önizleme görüntüsünü bayt dizisi olarak alır. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Ekli dosyanın önizleme görüntüsünü bayt dizisi olarak ayarlar. |
|
|  | [isLink()](#isLink--) | İçeriğin yalnızca dosyaya bir bağlantı içerip içermediğini gösteren bir değeri alır. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Ekli dosyanın tam adını alır. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ekli dosyayla ilişkili açıklayıcı (alternatif) metni alır. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ekli dosyayla ilişkili açıklayıcı (alternatif) metni ayarlar. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Ek dosya çerçevesinin çalışma sayfasının sol kenarından nokta cinsinden yatay ofsetini alır. |
|
|  | [setX(double value)](#setX-double-) | Ek dosya çerçevesinin çalışma sayfasının sol kenarından nokta cinsinden yatay ofsetini ayarlar. |
|
|  | [getY()](#getY--) | Ek dosya çerçevesinin çalışma sayfasının üst kenarından nokta cinsinden dikey ofsetini alır. |
|
|  | [setY(double value)](#setY-double-) | Ek dosya çerçevesinin çalışma sayfasının üst kenarından nokta cinsinden dikey ofsetini ayarlar. |
|
|  | [getWidth()](#getWidth--) | Ek dosya çerçevesinin genişliğini nokta cinsinden alır. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ek dosya çerçevesinin genişliğini nokta cinsinden ayarlar. |
|
|  | [getHeight()](#getHeight--) | Ek dosya çerçevesinin yüksekliğini nokta cinsinden alır. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ek dosya çerçevesinin yüksekliğini nokta cinsinden ayarlar. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Ekli dosya içeriğini alır.


**Returns:**
byte[] - Ekli dosya içeriği.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ekli dosya içeriğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte[] | Ekli dosya içeriği. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Ekli dosyanın önizleme görüntüsünü bayt dizisi olarak alır.


**Returns:**
byte[] - Ekli dosyanın önizleme görüntüsü bayt dizisi olarak.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Ekli dosyanın önizleme görüntüsünü bayt dizisi olarak ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte[] | Ekli dosyanın önizleme görüntüsü bayt dizisi olarak. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


İçeriğin yalnızca dosyaya bir bağlantı içerip içermediğini gösteren bir değeri alır.


**Returns:**
boolean - Ekli dosya bir bağlantı ile referans gösteriliyorsa doğru (içerik ekli dosya içeriği içermez); aksi takdirde yanlış.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Ekli dosyanın tam adını alır.


**Returns:**
java.lang.String - Ekli dosyanın tam adı.

<br />

*** ** * ** ***

Uzantı, dosyayı açmak için uygun uygulamayı belirlemek amacıyla kullanılır.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Ekli dosyayla ilişkili açıklayıcı (alternatif) metni alır.


**Returns:**
java.lang.String - Ekli dosyayla ilişkili açıklayıcı (alternatif) metin.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ekli dosyayla ilişkili açıklayıcı (alternatif) metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Ekli dosyayla ilişkili açıklayıcı (alternatif) metin. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


Ek dosya çerçevesinin çalışma sayfasının sol kenarından nokta cinsinden yatay ofsetini alır.


**Returns:**
double - Eklenti çerçevesinin x koordinatı.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ek dosya çerçevesinin çalışma sayfasının sol kenarından nokta cinsinden yatay ofsetini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Eklenti çerçevesinin x koordinatı. |
|

### getY() {#getY--}
```
public final double getY()
```


Ek dosya çerçevesinin çalışma sayfasının üst kenarından nokta cinsinden dikey ofsetini alır.


**Returns:**
double - Eklenti çerçevesinin y koordinatı.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ek dosya çerçevesinin çalışma sayfasının üst kenarından nokta cinsinden dikey ofsetini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Eklenti çerçevesinin y koordinatı. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ek dosya çerçevesinin genişliğini nokta cinsinden alır.


**Returns:**
double - Eklenti çerçevesinin nokta cinsinden genişliği.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ek dosya çerçevesinin genişliğini nokta cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Eklenti çerçevesinin nokta cinsinden genişliği. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ek dosya çerçevesinin yüksekliğini nokta cinsinden alır.


**Returns:**
double - Eklenti çerçevesinin nokta cinsinden yüksekliği.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ek dosya çerçevesinin yüksekliğini nokta cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Eklenti çerçevesinin nokta cinsinden yüksekliği. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



