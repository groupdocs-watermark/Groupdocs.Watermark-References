---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesindeki bir çizim şekli temsil eder."
type: docs
weight: 117
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Excel belgesindeki bir çizim şekli temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin üst çalışma sayfasını alır. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Otomatik şekil türünü alır. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | mso çizim türünü alır. |
|
|  | [getText()](#getText--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin metnini ayarlar. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getImage()](#getImage--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin görüntüsünü alır. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin görüntüsünü ayarlar. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin görüntü doldurma biçim ayarlarını alır. |
|
|  | [getId()](#getId--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin tanımlayıcısını alır. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni alır. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni ayarlar. |
|
|  | [isWordArt()](#isWordArt--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin WordArt nesnesi olup olmadığını gösteren bir değeri alır. |
|
|  | [getName()](#getName--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin adını alır. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili köprüyi alır. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili köprüyi ayarlar. |
|
|  | [getX()](#getX--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının sol kenarından puan cinsinden yatay ofsetini alır. |
|
|  | [setX(double value)](#setX-double-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının sol kenarından puan cinsinden yatay ofsetini ayarlar. |
|
|  | [getY()](#getY--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının üst kenarından puan cinsinden dikey ofsetini alır. |
|
|  | [setY(double value)](#setY-double-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının üst kenarından puan cinsinden dikey ofsetini ayarlar. |
|
|  | [getWidth()](#getWidth--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin genişliğini puan cinsinden alır. |
|
|  | [setWidth(double value)](#setWidth-double-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin genişliğini puan cinsinden ayarlar. |
|
|  | [getHeight()](#getHeight--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin yüksekliğini puan cinsinden alır. |
|
|  | [setHeight(double value)](#setHeight-double-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin yüksekliğini puan cinsinden ayarlar. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin döndürme açısını derece cinsinden alır veya ayarlar. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin döndürme açısını derece cinsinden alır veya ayarlar. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin üst çalışma sayfasını alır.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Otomatik şekil türünü alır.


**Returns:**
int - Otomatik şekil türü.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


mso çizim türünü alır.


**Returns:**
int - mso çizim türü.

### getText() {#getText--}
```
public final String getText()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin metnini alır.


**Returns:**
java.lang.String - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` metni.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin metnini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` metni. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin görüntüsünü alır.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` görüntüsü veya görüntünün kaldırılması gerekiyorsa null. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin görüntü doldurma biçim ayarlarını alır.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin tanımlayıcısını alır.


**Returns:**
int - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` tanımlayıcısı.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni alır.


**Returns:**
java.lang.String - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ile ilişkili açıklayıcı (alternatif) metin.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili açıklayıcı (alternatif) metni ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ile ilişkili açıklayıcı (alternatif) metin. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin WordArt nesnesi olup olmadığını gösteren bir değeri alır.


**Returns:**
boolean - Şekil bir WordArt nesnesiyse true; aksi takdirde false.

### getName() {#getName--}
```
public final String getName()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin adını alır.


**Returns:**
java.lang.String - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` adı.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili köprüyi alır.


**Returns:**
java.lang.String - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ile ilişkili köprü.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesiyle ilişkili köprüyi ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ile ilişkili köprü. |
|

### getX() {#getX--}
```
public final double getX()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının sol kenarından puan cinsinden yatay ofsetini alır.


**Returns:**
double - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` x-koordinatı.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının sol kenarından puan cinsinden yatay ofsetini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` x-koordinatı. |
|

### getY() {#getY--}
```
public final double getY()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının üst kenarından puan cinsinden dikey ofsetini alır.


**Returns:**
double - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` y-koordinatı.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin çalışma sayfasının üst kenarından puan cinsinden dikey ofsetini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin y koordinatı. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin genişliği nokta cinsinden.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin genişliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin genişliği nokta cinsinden. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin yüksekliği nokta cinsinden.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin yüksekliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin yüksekliği nokta cinsinden. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin döndürme açısını derece cinsinden alır veya ayarlar.


**Returns:**
double - Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin döndürme açısı derece cinsinden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` nesnesinin döndürme açısını derece cinsinden alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` öğesinin döndürme açısı derece cinsinden. |
|

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageData | byte[] |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

