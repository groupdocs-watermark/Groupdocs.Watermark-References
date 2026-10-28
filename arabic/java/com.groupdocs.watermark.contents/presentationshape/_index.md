---
title: "PresentationShape"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل شكل رسم في مستند PowerPoint."
type: docs
weight: 93
url: /ar/java/com.groupdocs.watermark.contents/presentationshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter), [com.groupdocs.watermark.contents.PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class PresentationShape extends PresentationBaseShape implements IRotatableTwoDObject
```

يمثل شكل رسم في مستند PowerPoint.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` بالدرجات. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | يضبط زاوية الدوران لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` بالدرجات. |
|
|  | [getText()](#getText--) | يحصل على النص لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط النص لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | يحصل على مجموعة مقاطع النص المنسقة لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [getShapeType()](#getShapeType--) | يحصل على نوع الشكل الهندسي المسبق. |
|
|  | [getImage()](#getImage--) | يحصل على الصورة لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|
|  | [setImage(PresentationWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | يضبط الصورة لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
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


يحصل على زاوية الدوران لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` بالدرجات.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


يضبط زاوية الدوران لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` بالدرجات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | زاوية الدوران لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` بالدرجات. |
|

### getText() {#getText--}
```
public final String getText()
```


يحصل على النص لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
java.lang.String - النص لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يضبط النص لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | النص لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


يحصل على مجموعة مقاطع النص المنسقة لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


يحصل على نوع الشكل الهندسي المسبق.


**Returns:**
int - نوع الإعداد المسبق للهندسة.

### getImage() {#getImage--}
```
public final PresentationWatermarkableImage getImage()
```


يحصل على الصورة لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The image of this `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` or null if the shape has no image.

### setImage(PresentationWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public final void setImage(PresentationWatermarkableImage value)
```


يضبط الصورة لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | الصورة لهذا `[PresentationShape](../../com.groupdocs.watermark.contents/presentationshape)` أو null إذا كان يجب إزالة الصورة. |
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
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

