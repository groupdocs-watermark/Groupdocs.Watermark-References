---
title: "PdfShape"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر الفئة الأساسية لـ XObjects Artifacts و Annotations."
type: docs
weight: 69
url: /ar/java/com.groupdocs.watermark.contents/pdfshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public abstract class PdfShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

يوفر الفئة الأساسية لـ XObjects وArtifacts وAnnotations.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحصل على نص هذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط نص هذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | يحصل على مجموعة شظايا النص المنسقة لهذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getImage()](#getImage--) | يحصل على الصورة لهذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [setImage(PdfWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-) | يضبط الصورة لهذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|
|  | [getX()](#getX--) | يحصل على الإحداثي السيني للكائن. |
|
|  | [getY()](#getY--) | يحصل على الإحداثي الصادي للكائن. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض الكائن. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع الكائن. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران للجسم بالدرجات. |
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


يحصل على نص هذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
java.lang.String - نص هذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يحصل أو يضبط نص هذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | نص هذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


يحصل على مجموعة شظايا النص المنسقة لهذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### getImage() {#getImage--}
```
public final PdfWatermarkableImage getImage()
```


يحصل على الصورة لهذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) - The image of this `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.

### setImage(PdfWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PdfWatermarkableImage-}
```
public final void setImage(PdfWatermarkableImage value)
```


يضبط الصورة لهذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage) | صورة هذا `[PdfShape](../../com.groupdocs.watermark.contents/pdfshape)`. |
|

### getX() {#getX--}
```
public abstract double getX()
```


يحصل على الإحداثي السيني للكائن.


**Returns:**
double - الإحداثي السيني للكائن.

### getY() {#getY--}
```
public abstract double getY()
```


يحصل على الإحداثي الصادي للكائن.


**Returns:**
double - الإحداثي الصادي للكائن.

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


يحصل على عرض الكائن.


**Returns:**
double - عرض الكائن.

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


يحصل على ارتفاع الكائن.


**Returns:**
double - ارتفاع الكائن.

### getRotateAngle() {#getRotateAngle--}
```
public abstract double getRotateAngle()
```


يحصل على زاوية الدوران للجسم بالدرجات.


**Returns:**
double - زاوية الدوران للجسم بالدرجات.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | byte[] |  |

