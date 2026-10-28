---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل شكل رسم في مستند Excel."
type: docs
weight: 117
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

يمثل شكل رسم في مستند Excel.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | يحصل على ورقة العمل الأصلية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | يحصل على نوع الشكل التلقائي. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | يحصل على نوع الرسم mso. |
|
|  | [getText()](#getText--) | يحصل على النص لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط النص لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | يحصل على مجموعة مقاطع النص المنسقة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | يحصل على الصورة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | يضبط الصورة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | يحصل على إعدادات تنسيق تعبئة الصورة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | يحصل على المعرف لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | يحصل على النص الوصفي (البديل) المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يضبط النص الوصفي (البديل) المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [isWordArt()](#isWordArt--) | يحصل على قيمة تشير إلى ما إذا كان هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` كائن WordArt. |
|
|  | [getName()](#getName--) | يحصل على اسم هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | يحصل على الارتباط التشعبي المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | يضبط الارتباط التشعبي المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getX()](#getX--) | يحصل على الإزاحة الأفقية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد الأيسر للورقة في النقاط. |
|
|  | [setX(double value)](#setX-double-) | يضبط الإزاحة الأفقية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد الأيسر للورقة في النقاط. |
|
|  | [getY()](#getY--) | يحصل على الإزاحة العمودية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد العلوي للورقة في النقاط. |
|
|  | [setY(double value)](#setY-double-) | يضبط الإزاحة العمودية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد العلوي للورقة في النقاط. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط. |
|
|  | [setWidth(double value)](#setWidth-double-) | يضبط عرض هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط. |
|
|  | [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل أو يضبط زاوية الدوران لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالدرجات. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | يحصل أو يضبط زاوية الدوران لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالدرجات. |
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


يحصل على ورقة العمل الأصلية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


يحصل على نوع الشكل التلقائي.


**Returns:**
int - نوع الشكل التلقائي.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


يحصل على نوع الرسم mso.


**Returns:**
int - نوع رسم mso.

### getText() {#getText--}
```
public final String getText()
```


يحصل على النص لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - نص هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يضبط النص لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | نص هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


يحصل على مجموعة مقاطع النص المنسقة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


يحصل على الصورة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


يضبط الصورة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | صورة هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` أو null إذا كان يجب إزالة الصورة. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


يحصل على إعدادات تنسيق تعبئة الصورة لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


يحصل على المعرف لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - معرف هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


يحصل على النص الوصفي (البديل) المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - النص الوصفي (البديل) المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


يضبط النص الوصفي (البديل) المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | النص الوصفي (البديل) المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` كائن WordArt.


**Returns:**
boolean - صحيح إذا كان الشكل كائن WordArt؛ وإلا، خطأ.

### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - اسم هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

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


يحصل على الارتباط التشعبي المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - الارتباط التشعبي المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


يضبط الارتباط التشعبي المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | الارتباط التشعبي المرتبط بهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getX() {#getX--}
```
public final double getX()
```


يحصل على الإزاحة الأفقية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد الأيسر للورقة في النقاط.


**Returns:**
double - إحداثي x لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


يضبط الإزاحة الأفقية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد الأيسر للورقة في النقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | إحداثي x لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


يحصل على الإزاحة العمودية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد العلوي للورقة في النقاط.


**Returns:**
double - إحداثي y لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


يضبط الإزاحة العمودية لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` من الحد العلوي للورقة في النقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإحداثي ص لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يحصل على عرض هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط.


**Returns:**
double - عرض هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


يضبط عرض هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | عرض هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يحصل على ارتفاع هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط.


**Returns:**
double - ارتفاع هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


يضبط ارتفاع هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | ارتفاع هذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالنقاط. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


يحصل أو يضبط زاوية الدوران لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالدرجات.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


يحصل أو يضبط زاوية الدوران لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالدرجات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | زاوية الدوران لهذا `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` بالدرجات. |
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

