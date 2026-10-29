---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PowerPoint belgesindeki tüm tipteki şekiller için soyut temel sınıfı sağlar."
type: docs
weight: 77
url: /tr/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

PowerPoint belgesindeki tüm tipteki şekiller için soyut temel sınıfı sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin üst sunumunu alır. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin resim doldurma biçimi ayarlarını alır. |
|
|  | [getName()](#getName--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin adını alır. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni alır. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni ayarlar. |
|
|  | [getId()](#getId--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin tanımlayıcısını alır. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin z-sırasındaki konumunu alır. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili köprüyi alır. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili köprüyi ayarlar. |
|
|  | [getX()](#getX--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun sol kenarından puan cinsinden yatay ofsetini alır. |
|
|  | [setX(double value)](#setX-double-) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun sol kenarından puan cinsinden yatay ofsetini ayarlar. |
|
|  | [getY()](#getY--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun üst kenarından puan cinsinden dikey ofsetini alır veya ayarlar. |
|
|  | [setY(double value)](#setY-double-) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun üst kenarından puan cinsinden dikey ofsetini alır veya ayarlar. |
|
|  | [getWidth()](#getWidth--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin genişliğini puan cinsinden alır. |
|
|  | [setWidth(double value)](#setWidth-double-) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin genişliğini puan cinsinden ayarlar. |
|
|  | [getHeight()](#getHeight--) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin yüksekliğini puan cinsinden alır. |
|
|  | [setHeight(double value)](#setHeight-double-) | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin yüksekliğini puan cinsinden ayarlar. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin üst sunumunu alır.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin resim doldurma biçimi ayarlarını alır.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin adını alır.


**Returns:**
java.lang.String - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin adı.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni alır.


**Returns:**
java.lang.String - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili açıklayıcı (alternatif) metin.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili açıklayıcı (alternatif) metin. |
|

### getId() {#getId--}
```
public final long getId()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin tanımlayıcısını alır.


**Returns:**
long - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin tanımlayıcısı.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin z-sırasındaki konumunu alır.

Daha yüksek z-sırasına sahip bir şekil, her zaman daha düşük z-sırasına sahip bir şeklin önünde bulunur.


**Returns:**
int - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin z-sırasındaki konumu.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili köprüyi alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | actionType | int | Hiperlinki etkinleştiren eylem. |
|

**Returns:**
java.lang.String - Belirtilen eylemde etkinleştirilen hiperlinkin URL'si.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesiyle ilişkili köprüyi ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | actionType | int | Hiperlinki etkinleştiren eylem. |
|
|  | url | java.lang.String | Hiperlink URL'si. |
|

### getX() {#getX--}
```
public final double getX()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun sol kenarından puan cinsinden yatay ofsetini alır.


**Returns:**
double - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin x koordinatı.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun sol kenarından puan cinsinden yatay ofsetini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin x koordinatı. |
|

### getY() {#getY--}
```
public final double getY()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun üst kenarından puan cinsinden dikey ofsetini alır veya ayarlar.


**Returns:**
double - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin y koordinatı.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin sunumun üst kenarından puan cinsinden dikey ofsetini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin y koordinatı. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin puan cinsinden genişliği.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin genişliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin puan cinsinden genişliği. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin puan cinsinden yüksekliği.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin yüksekliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` öğesinin puan cinsinden yüksekliği. |
|

