---
title: "PresentationShape"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili bentuk gambar dalam dokumen PowerPoint."
type: docs
weight: 93
url: /id/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

Mewakili bentuk gambar dalam dokumen PowerPoint.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini dalam derajat. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Mengatur sudut rotasi dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini dalam derajat. |
|
|  | [getText()](#getText--) | Mendapatkan teks dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini. |
|
|  | [getShapeType()](#getShapeType--) | Mendapatkan tipe preset geometri bentuk. |
|
|  | [getImage()](#getImage--) | Mendapatkan gambar dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Mengatur gambar dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini. |
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


Mendapatkan sudut rotasi dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini dalam derajat.


**Returns:**
double - Sudut rotasi dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini dalam derajat.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Mengatur sudut rotasi dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini dalam derajat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | double | Sudut rotasi dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini dalam derajat. |
|

### getText() {#getText--}
```
public final String getText()
```


Mendapatkan teks dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini.


**Returns:**
java.lang.String - Teks dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mengatur teks dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Mendapatkan tipe preset geometri bentuk.


**Returns:**
int - Tipe preset geometri.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


Mendapatkan gambar dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


Mengatur gambar dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Gambar dari `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` ini atau null jika gambar harus dihapus. |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

