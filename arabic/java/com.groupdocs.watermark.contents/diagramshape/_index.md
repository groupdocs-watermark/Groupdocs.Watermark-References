---
title: "DiagramShape"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل شكل رسم في مستند Visio."
type: docs
weight: 24
url: /ar/java/com.groupdocs.watermark.contents/diagramshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject)
```
public class DiagramShape extends ShapeSearchAdapter implements IRotatableTwoDObject
```

يمثل شكل رسم في مستند Visio.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
|  | [getPage()](#getPage--) | يسترجع الصفحة الأصلية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getWidth()](#getWidth--) | يسترجع عرض هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط. |
|
|  | [setWidth(double value)](#setWidth-double-) | يضبط عرض هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يسترجع ارتفاع هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط. |
|
|  | [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط. |
|
|  | [getX()](#getX--) | يسترجع الإزاحة الأفقية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد الأيسر للصفحة بالنقاط. |
|
|  | [setX(double value)](#setX-double-) | يضبط الإزاحة الأفقية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد الأيسر للصفحة بالنقاط. |
|
|  | [getY()](#getY--) | يسترجع الإزاحة العمودية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد السفلي للصفحة بالنقاط. |
|
|  | [setY(double value)](#setY-double-) | يضبط الإزاحة العمودية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد السفلي للصفحة بالنقاط. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يسترجع أو يضبط زاوية الدوران لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالدرجات. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | يسترجع أو يضبط زاوية الدوران لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالدرجات. |
|
|  | [getText()](#getText--) | يسترجع أو يضبط نص هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يسترجع أو يضبط نص هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | يسترجع مجموعة شظايا النص المنسقة لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getImage()](#getImage--) | يسترجع صورة هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [setImage(DiagramWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-) | يضبط صورة هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getId()](#getId--) | يسترجع معرف هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getName()](#getName--) | يسترجع اسم هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|
|  | [getHyperlinks()](#getHyperlinks--) | يسترجع مجموعة الروابط التشعبية المرفقة بهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
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


يسترجع الصفحة الأصلية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramPage](../../com.groupdocs.watermark.contents/diagrampage) - The parent page of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يسترجع عرض هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط.


**Returns:**
double - عرض هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


يضبط عرض هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | عرض هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يسترجع ارتفاع هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط.


**Returns:**
double - ارتفاع هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


يضبط ارتفاع هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | ارتفاع هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالنقاط. |
|

### getX() {#getX--}
```
public final double getX()
```


يسترجع الإزاحة الأفقية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد الأيسر للصفحة بالنقاط.


**Returns:**
double - الإزاحة الأفقية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد الأيسر للصفحة بالنقاط.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


يضبط الإزاحة الأفقية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد الأيسر للصفحة بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإزاحة الأفقية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد الأيسر للصفحة بالنقاط. |
|

### getY() {#getY--}
```
public final double getY()
```


يسترجع الإزاحة العمودية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد السفلي للصفحة بالنقاط.


**Returns:**
double - الإزاحة العمودية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد السفلي للصفحة بالنقاط.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


يضبط الإزاحة العمودية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد السفلي للصفحة بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإزاحة العمودية لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` من الحد السفلي للصفحة بالنقاط. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


يسترجع أو يضبط زاوية الدوران لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالدرجات.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


يسترجع أو يضبط زاوية الدوران لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالدرجات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | زاوية الدوران لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)` بالدرجات. |
|

### getText() {#getText--}
```
public final String getText()
```


يسترجع أو يضبط نص هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - نص هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يسترجع أو يضبط نص هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | نص هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


يسترجع مجموعة شظايا النص المنسقة لهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getImage() {#getImage--}
```
public final DiagramWatermarkableImage getImage()
```


يسترجع صورة هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
[DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) - The image of this `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### setImage(DiagramWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.DiagramWatermarkableImage-}
```
public final void setImage(DiagramWatermarkableImage value)
```


يضبط صورة هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [DiagramWatermarkableImage](../../com.groupdocs.watermark.contents/diagramwatermarkableimage) | صورة هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


يسترجع معرف هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
long - معرف هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getName() {#getName--}
```
public final String getName()
```


يسترجع اسم هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


**Returns:**
java.lang.String - اسم هذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.

### getHyperlinks() {#getHyperlinks--}
```
public final DiagramHyperlinkCollection getHyperlinks()
```


يسترجع مجموعة الروابط التشعبية المرفقة بهذا `[DiagramShape](../../com.groupdocs.watermark.contents/diagramshape)`.


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
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

