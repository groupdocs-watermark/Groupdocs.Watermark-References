---
title: "DiagramShape"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Visio belgesindeki bir çizim şekli temsil eder."
type: docs
weight: 24
url: /tr/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

Visio belgesindeki bir çizim şekli temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin üst sayfasını alır. |
|
|  | [getWidth()](#getWidth--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin genişliğini puan cinsinden alır. |
|
|  | [setWidth(double value)](#setWidth-double-) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin genişliğini puan cinsinden ayarlar. |
|
|  | [getHeight()](#getHeight--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin yüksekliğini puan cinsinden alır. |
|
|  | [setHeight(double value)](#setHeight-double-) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin yüksekliğini puan cinsinden ayarlar. |
|
|  | [getX()](#getX--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden alır. |
|
|  | [setX(double value)](#setX-double-) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden ayarlar. |
|
|  | [getY()](#getY--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa alt kenarından dikey ofsetini puan cinsinden alır. |
|
|  | [setY(double value)](#setY-double-) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa alt kenarından dikey ofsetini puan cinsinden ayarlar. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin döndürme açısını derece cinsinden alır veya ayarlar. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin döndürme açısını derece cinsinden alır veya ayarlar. |
|
|  | [getText()](#getText--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin metnini alır veya ayarlar. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin metnini alır veya ayarlar. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getImage()](#getImage--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin görüntüsünü alır. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin görüntüsünü ayarlar. |
|
|  | [getId()](#getId--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin tanımlayıcısını alır. |
|
|  | [getName()](#getName--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin adını alır. |
|
|  | [getHyperlinks()](#getHyperlinks--) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesine eklenmiş köprülerin koleksiyonunu alır. |
|
|  | [getAsposeShape()](#getAsposeShape--) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getPage() {#getPage--}
```
public final DiagramPage getPage()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin üst sayfasını alır.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin genişliğini puan cinsinden alır.


**Returns:**
double - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin genişliği puan cinsinden.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin genişliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin genişliği puan cinsinden. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin yüksekliğini puan cinsinden alır.


**Returns:**
double - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin yüksekliği puan cinsinden.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin yüksekliğini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin yüksekliği puan cinsinden. |
|

### getX() {#getX--}
```
public final double getX()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden alır.


**Returns:**
double - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa sol kenarından yatay ofseti puan cinsinden.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa sol kenarından yatay ofsetini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa sol kenarından yatay ofseti puan cinsinden. |
|

### getY() {#getY--}
```
public final double getY()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa alt kenarından dikey ofsetini puan cinsinden alır.


**Returns:**
double - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa alt kenarından dikey ofseti puan cinsinden.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa alt kenarından dikey ofsetini puan cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin sayfa alt kenarından dikey ofseti puan cinsinden. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin döndürme açısını derece cinsinden alır veya ayarlar.


**Returns:**
double - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin döndürme açısı derece cinsinden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin döndürme açısını derece cinsinden alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin döndürme açısı derece cinsinden. |
|

### getText() {#getText--}
```
public final String getText()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin metnini alır veya ayarlar.


**Returns:**
java.lang.String - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin metni.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin metnini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin metni. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin görüntüsünü alır.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin resmi. |
|

### getId() {#getId--}
```
public final long getId()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin tanımlayıcısını alır.


**Returns:**
long - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin tanımlayıcısı.

### getName() {#getName--}
```
public final String getName()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin adını alır.


**Returns:**
java.lang.String - Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesinin adı.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


Bu `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` öğesine eklenmiş köprülerin koleksiyonunu alır.


**Returns:**
[DiagramHyperlinkCollection](../../com.groupdocs.watermark.contents/diagramhyperlinkcollection) - The collection of hyperlinks attached to this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getAsposeShape() {#getAsposeShape--}
```
public final Shape getAsposeShape()
```


<br />



**Returns:**
com.aspose.diagram.Shape
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
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

