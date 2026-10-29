---
title: "PresentationShape"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PowerPoint belgesindeki bir çizim şekli temsil eder."
type: docs
weight: 93
url: /tr/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

PowerPoint belgesindeki bir çizim şekli temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın döndürme açısını derece cinsinden alır. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın döndürme açısını derece cinsinden ayarlar. |
|
|  | [getText()](#getText--) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın metnini ayarlar. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getShapeType()](#getShapeType--) | Şekil geometri ön ayar tipini alır. |
|
|  | [getImage()](#getImage--) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın görüntüsünü alır. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın görüntüsünü ayarlar. |
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
### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın döndürme açısını derece cinsinden alır.


**Returns:**
double - Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın döndürme açısı derece cinsinden.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın döndürme açısını derece cinsinden ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | double | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın döndürme açısı derece cinsinden. |
|

### getText() {#getText--}
```
public final String getText()
```


Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın metnini alır.


**Returns:**
java.lang.String - Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` öğesinin metni.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın metnini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` öğesinin metni. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Şekil geometri ön ayar tipini alır.


**Returns:**
int - Geometri ön ayar türü.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın görüntüsünü alır.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`'ın görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Bu `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` öğesinin resmi veya resim kaldırılacaksa null. |
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

