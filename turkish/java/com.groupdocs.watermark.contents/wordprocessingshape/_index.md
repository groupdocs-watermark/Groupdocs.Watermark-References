---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Word belgesindeki çizim şekli temsil eder."
type: docs
weight: 141
url: /tr/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Bir Word belgesindeki çizim şekli temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSection()](#getSection--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin üst bölümünü alır. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin üstbilgi/altbilgi öğesini alır (varsa). |
|
|  | [getShapeType()](#getShapeType--) | Şekil tipini alır. |
|
|  | [isWordArt()](#isWordArt--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin WordArt nesnesi olup olmadığını gösteren bir değer alır. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni alır. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni ayarlar. |
|
|  | [getName()](#getName--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin adını alır. |
|
|  | [getBehindText()](#getBehindText--) | Şeklin metnin üzerinde mi yoksa arkasında mı olduğunu gösteren bir değer alır. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Şeklin metnin üzerinde mi yoksa arkasında mı olduğunu gösteren bir değer ayarlar. |
|
|  | [getText()](#getText--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin metnini ayarlar. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getImage()](#getImage--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin görüntüsünü alır. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin görüntüsünü ayarlar. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Şeklin yatay olarak nasıl konumlandırıldığını belirten bir değer alır. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Şeklin dikey olarak nasıl konumlandırıldığını belirten bir değer alır. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Şeklin yatay olarak nereye konumlandırıldığını belirten bir değer alır. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Şeklin dikey olarak nereye konumlandırıldığını belirten bir değer alır. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili hiperbağlantıyı alır. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili hiperbağlantıyı ayarlar. |
|
|  | [getWidth()](#getWidth--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` genişliğini puan cinsinden alır. |
|
|  | [setWidth(double value)](#setWidth-double-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` genişliğini puan cinsinden ayarlar. |
|
|  | [getHeight()](#getHeight--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` yüksekliğini puan cinsinden alır. |
|
|  | [setHeight(double value)](#setHeight-double-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` yüksekliğini puan cinsinden ayarlar. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` döndürme açısını derece cinsinden alır. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` döndürme açısını derece cinsinden ayarlar. |
|
|  | [getX()](#getX--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa sol kenarından yatay ofseti puan cinsinden alır veya ayarlar. |
|
|  | [setX(double value)](#setX-double-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa sol kenarından yatay ofseti puan cinsinden alır veya ayarlar. |
|
|  | [getY()](#getY--) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa üst kenarından dikey ofseti puan cinsinden alır. |
|
|  | [setY(double value)](#setY-double-) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa üst kenarından dikey ofseti puan cinsinden ayarlar. |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin üst bölümünü alır.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin üstbilgi/altbilgi öğesini alır (varsa).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Şekil tipini alır.


**Returns:**
int - Şekil türü.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin WordArt nesnesi olup olmadığını gösteren bir değer alır.


**Returns:**
boolean - Şekil bir WordArt nesnesiyse true; aksi takdirde false.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni alır.


**Returns:**
java.lang.String - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili açıklayıcı (alternatif) metin.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili açıklayıcı (alternatif) metin. |
|

### getName() {#getName--}
```
public final String getName()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin adını alır.


**Returns:**
java.lang.String - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` adını.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Şeklin metnin üzerinde mi yoksa arkasında mı olduğunu gösteren bir değer alır.


**Returns:**
boolean - Şeklin metnin üzerinde mi yoksa arkasında mı olduğunu gösteren değer. Şekil metnin arkasındaysa true; aksi takdirde false.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Şeklin metnin üzerinde mi yoksa arkasında mı olduğunu gösteren bir değer ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Şeklin metnin üzerinde mi yoksa arkasında mı olduğunu gösteren değer. Şekil metnin arkasındaysa true; aksi takdirde false. |
|

### getText() {#getText--}
```
public final String getText()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin metnini alır.


**Returns:**
java.lang.String - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` metni.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin metnini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` metni. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin görüntüsünü alır.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` öğesinin görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` görüntüsü veya görüntünün kaldırılması gerekiyorsa `null`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Şeklin yatay olarak nasıl konumlandırıldığını belirten bir değer alır.


**Returns:**
int - Yatay hizalama değeri.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Şeklin dikey olarak nasıl konumlandırıldığını belirten bir değer alır.


**Returns:**
int - Dikey hizalama değeri.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Şeklin yatay olarak nereye konumlandırıldığını belirten bir değer alır.


**Returns:**
int - Göreceli yatay konum değeri.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Şeklin dikey olarak nereye konumlandırıldığını belirten bir değer alır.


**Returns:**
int - Göreceli dikey konum değeri.

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili hiperbağlantıyı alır.


**Returns:**
java.lang.String - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili hiperbağlantı.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili hiperbağlantıyı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ile ilişkili hiperbağlantı. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` genişliği nokta cinsinden.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` genişliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` genişliği nokta cinsinden. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` yüksekliği nokta cinsinden.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` yüksekliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` yüksekliği nokta cinsinden. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` döndürme açısını derece cinsinden alır.


**Returns:**
double - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` döndürme açısı derece cinsinden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` döndürme açısını derece cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` döndürme açısı derece cinsinden. |
|

### getX() {#getX--}
```
public final double getX()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa sol kenarından yatay ofseti puan cinsinden alır veya ayarlar.


**Returns:**
double - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`'ın x koordinatı.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa sol kenarından yatay ofseti puan cinsinden alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`'ın x koordinatı. |
|

### getY() {#getY--}
```
public final double getY()
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa üst kenarından dikey ofseti puan cinsinden alır.


**Returns:**
double - Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`'ın y koordinatı.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` sayfa üst kenarından dikey ofseti puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`'ın y koordinatı. |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageData | byte[] |  |

