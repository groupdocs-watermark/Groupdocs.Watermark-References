---
title: "PdfShape"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "XObjects, Artifacts ve Annotations için temel sınıf sağlar."
type: docs
weight: 69
url: /tr/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

XObjects, Artifacts ve Annotations için temel sınıf sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin metnini alır veya ayarlar. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getImage()](#getImage--) | Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin görüntüsünü alır. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin görüntüsünü ayarlar. |
|
|  | [getX()](#getX--) | Nesnenin x koordinatını alır. |
|
|  | [getY()](#getY--) | Nesnenin y koordinatını alır. |
|
|  | [getWidth()](#getWidth--) | Nesnenin genişliğini alır. |
|
|  | [getHeight()](#getHeight--) | Nesnenin yüksekliğini alır. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Nesnenin döndürme açısını derece cinsinden alır. |
|
|  | [getOuterForm()](#getOuterForm--) | <br /> |

|
|  | [extractImageAppearance()](#extractImageAppearance--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
### getText() {#getText--}
```
public String getText()
```


Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin metnini alır.


**Returns:**
java.lang.String - Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin metni.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin metnini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin metni. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin görüntüsünü alır.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | Bu `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)` öğesinin görüntüsü. |
|

### getX() {#getX--}
```
public abstract double getX()
```


Nesnenin x koordinatını alır.


**Returns:**
double - Nesnenin x koordinatı.

### getY() {#getY--}
```
public abstract double getY()
```


Nesnenin y koordinatını alır.


**Returns:**
double - Nesnenin y koordinatı.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Nesnenin genişliğini alır.


**Returns:**
double - Nesnenin genişliği.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Nesnenin yüksekliğini alır.


**Returns:**
double - Nesnenin yüksekliği.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


Nesnenin döndürme açısını derece cinsinden alır.


**Returns:**
double - Nesnenin derece cinsinden döndürme açısı.

### getOuterForm() {#getOuterForm--}
```
public abstract XForm getOuterForm()
```


<br />



**Returns:**
com.aspose.pdf.XForm
### extractImageAppearance() {#extractImageAppearance--}
```
public PdfXImageAppearance extractImageAppearance()
```


<br />



**Returns:**
[PdfXImageAppearance](../../com.groupdocs.watermark.internal/pdfximageappearance)
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

