---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر الفئة الأساسية المجردة للأشكال من جميع الأنواع في مستند PowerPoint."
type: docs
weight: 77
url: /ar/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

يوفر الفئة الأساسية المجردة للأشكال من جميع الأنواع في مستند PowerPoint.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | يسترجع العرض الأب لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | يسترجع إعدادات تنسيق تعبئة الصورة لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getName()](#getName--) | يسترجع اسم هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | يسترجع النص الوصفي (البديل) المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يضبط النص الوصفي (البديل) المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getId()](#getId--) | يسترجع المعرف لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | يسترجع موضع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` في ترتيب z. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | يسترجع الارتباط التشعبي المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | يضبط الارتباط التشعبي المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getX()](#getX--) | يسترجع الإزاحة الأفقية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد الأيسر للعرض بالنقاط. |
|
|  | [setX(double value)](#setX-double-) | يضبط الإزاحة الأفقية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد الأيسر للعرض بالنقاط. |
|
|  | [getY()](#getY--) | يسترجع أو يضبط الإزاحة العمودية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد العلوي للعرض بالنقاط. |
|
|  | [setY(double value)](#setY-double-) | يسترجع أو يضبط الإزاحة العمودية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد العلوي للعرض بالنقاط. |
|
|  | [getWidth()](#getWidth--) | يسترجع عرض هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط. |
|
|  | [setWidth(double value)](#setWidth-double-) | يضبط عرض هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط. |
|
|  | [getHeight()](#getHeight--) | يسترجع ارتفاع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط. |
|
|  | [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


يسترجع العرض الأب لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


يسترجع إعدادات تنسيق تعبئة الصورة لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


يسترجع اسم هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - اسم هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


يسترجع النص الوصفي (البديل) المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - النص الوصفي (البديل) المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


يضبط النص الوصفي (البديل) المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | النص الوصفي (البديل) المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


يسترجع المعرف لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
long - المعرف لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


يسترجع موضع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` في ترتيب z.

الشكل ذو ترتيب z أعلى دائمًا يكون أمام الشكل ذو ترتيب z أقل.


**Returns:**
int - موضع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` في ترتيب z.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


يسترجع الارتباط التشعبي المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | actionType | int | الإجراء الذي يفعّل الارتباط التشعبي. |
|

**Returns:**
java.lang.String - عنوان URL للارتباط التشعبي الذي يتم تفعيله عند الإجراء المحدد.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


يضبط الارتباط التشعبي المرتبط بهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | actionType | int | الإجراء الذي يفعّل الارتباط التشعبي. |
|
|  | عنوان URL | java.lang.String | عنوان URL للارتباط التشعبي. |
|

### getX() {#getX--}
```
public final double getX()
```


يسترجع الإزاحة الأفقية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد الأيسر للعرض بالنقاط.


**Returns:**
double - إحداثي x لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


يضبط الإزاحة الأفقية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد الأيسر للعرض بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | إحداثي x لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


يسترجع أو يضبط الإزاحة العمودية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد العلوي للعرض بالنقاط.


**Returns:**
double - إحداثي y لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


يسترجع أو يضبط الإزاحة العمودية لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` من الحد العلوي للعرض بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | إحداثي y لهذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يسترجع عرض هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط.


**Returns:**
double - عرض هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


يضبط عرض هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | عرض هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يسترجع ارتفاع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط.


**Returns:**
double - ارتفاع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


يضبط ارتفاع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | ارتفاع هذا `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` بالنقاط. |
|

