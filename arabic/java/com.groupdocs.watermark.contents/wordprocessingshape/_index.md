---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل شكل رسم في مستند Word."
type: docs
weight: 141
url: /ar/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

يمثل شكل رسم في مستند Word.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSection()](#getSection--) | يحصل على القسم الأب لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | يحصل على رأس/تذييل الأب لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (إذا كان موجودًا). |
|
|  | [getShapeType()](#getShapeType--) | يحصل على نوع الشكل. |
|
|  | [isWordArt()](#isWordArt--) | يحصل على قيمة تشير إلى ما إذا كان هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` كائن WordArt. |
|
|  | [getAlternativeText()](#getAlternativeText--) | يحصل على النص الوصفي (البديل) المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يضبط النص الوصفي (البديل) المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getName()](#getName--) | يحصل على اسم هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getBehindText()](#getBehindText--) | يحصل على قيمة تشير إلى ما إذا كان الشكل فوق النص أو خلفه. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | يضبط قيمة تشير إلى ما إذا كان الشكل فوق النص أو خلفه. |
|
|  | [getText()](#getText--) | يحصل على نص هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط نص هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | يحصل على مجموعة مقاطع النص المنسقة لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getImage()](#getImage--) | يحصل على صورة هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | يضبط صورة هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | يحصل على قيمة تحدد كيفية تموضع الشكل أفقيًا. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | يحصل على قيمة تحدد كيفية تموضع الشكل عموديًا. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | يحصل على قيمة تحدد إلى أين يتموضع الشكل أفقيًا. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | يحصل على قيمة تحدد إلى أين يتموضع الشكل عموديًا. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | يحصل على الارتباط التشعبي المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | يضبط الارتباط التشعبي المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط. |
|
|  | [setWidth(double value)](#setWidth-double-) | يضبط عرض هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط. |
|
|  | [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالدرجات. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | يضبط زاوية الدوران لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالدرجات. |
|
|  | [getX()](#getX--) | يحصل أو يضبط الإزاحة الأفقية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد الأيسر للصفحة بالنقاط. |
|
|  | [setX(double value)](#setX-double-) | يحصل أو يضبط الإزاحة الأفقية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد الأيسر للصفحة بالنقاط. |
|
|  | [getY()](#getY--) | يحصل على الإزاحة العمودية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد العلوي للصفحة بالنقاط. |
|
|  | [setY(double value)](#setY-double-) | يضبط الإزاحة العمودية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد العلوي للصفحة بالنقاط. |
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


يحصل على القسم الأب لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


يحصل على رأس/تذييل الأب لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (إذا كان موجودًا).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


يحصل على نوع الشكل.


**Returns:**
int - نوع الشكل.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` كائن WordArt.


**Returns:**
boolean - صحيح إذا كان الشكل كائن WordArt؛ وإلا، خطأ.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


يحصل على النص الوصفي (البديل) المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - النص الوصفي (البديل) المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


يضبط النص الوصفي (البديل) المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | النص الوصفي (البديل) المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - اسم هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل فوق النص أو خلفه.


**Returns:**
boolean - القيمة التي تشير إلى ما إذا كان الشكل فوق النص أو خلفه. True إذا كان الشكل خلف النص؛ وإلا false.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الشكل فوق النص أو خلفه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | القيمة التي تشير إلى ما إذا كان الشكل فوق النص أو خلفه. True إذا كان الشكل خلف النص؛ وإلا false. |
|

### getText() {#getText--}
```
public final String getText()
```


يحصل على نص هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - نص هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يضبط نص هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | نص هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


يحصل على مجموعة مقاطع النص المنسقة لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


يحصل على صورة هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


يضبط صورة هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | صورة هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` أو `null` إذا كان يجب إزالة الصورة. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


يحصل على قيمة تحدد كيفية تموضع الشكل أفقيًا.


**Returns:**
int - قيمة المحاذاة الأفقية.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


يحصل على قيمة تحدد كيفية تموضع الشكل عموديًا.


**Returns:**
int - قيمة المحاذاة العمودية.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


يحصل على قيمة تحدد إلى أين يتموضع الشكل أفقيًا.


**Returns:**
int - قيمة الموضع الأفقي النسبي.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


يحصل على قيمة تحدد إلى أين يتموضع الشكل عموديًا.


**Returns:**
int - قيمة الموضع العمودي النسبي.

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


يحصل على الارتباط التشعبي المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - الارتباط التشعبي المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


يضبط الارتباط التشعبي المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | الارتباط التشعبي المرتبط بهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يحصل على عرض هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط.


**Returns:**
double - عرض هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


يضبط عرض هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | عرض هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يحصل على ارتفاع هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط.


**Returns:**
double - ارتفاع هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


يضبط ارتفاع هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | ارتفاع هذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالنقاط. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


يحصل على زاوية الدوران لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالدرجات.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


يضبط زاوية الدوران لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالدرجات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | زاوية الدوران لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` بالدرجات. |
|

### getX() {#getX--}
```
public final double getX()
```


يحصل أو يضبط الإزاحة الأفقية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد الأيسر للصفحة بالنقاط.


**Returns:**
double - إحداثي X لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


يحصل أو يضبط الإزاحة الأفقية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد الأيسر للصفحة بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | إحداثي X لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


يحصل على الإزاحة العمودية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد العلوي للصفحة بالنقاط.


**Returns:**
double - إحداثي Y لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


يضبط الإزاحة العمودية لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` من الحد العلوي للصفحة بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | إحداثي Y لهذا `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | byte[] |  |

