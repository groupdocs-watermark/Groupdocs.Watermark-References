---
title: "TextWatermark"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل علامة مائية نصية."
type: docs
weight: 18
url: /ar/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

يمثل علامة مائية نصية.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

المثال التالي يوضح كيفية تحجيم العلامة المائية النصية اعتمادًا على حجم العنصر الأصل.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermark.setSizingType(SizingType.ScaleToParentDimensions);
>    watermark.setRotateAngle(45);
>    watermark.setScaleFactor(0.4);
>
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | يقوم بإنشاء نسخة جديدة من الفئة `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` مع نص محدد وخط. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحصل على النص المستخدم كعلامة مائية. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط النص المستخدم كعلامة مائية. |
|
|  | [getFont()](#getFont--) | يحصل على خط النص. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | يضبط خط النص. |
|
|  | [getForegroundColor()](#getForegroundColor--) | يحصل على لون المقدمة للنص. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | يضبط لون المقدمة للنص. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية للنص. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | يضبط لون الخلفية للنص. |
|
|  | [getTextAlignment()](#getTextAlignment--) | يحصل على محاذاة العلامة المائية `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | يضبط محاذاة العلامة المائية `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | يحصل على إعدادات الحشو لهذا `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | يضبط إعدادات الحشو لهذا `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


يقوم بإنشاء نسخة جديدة من الفئة `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` مع نص محدد وخط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | النص المستخدم كعلامة مائية. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|

### getText() {#getText--}
```
public final String getText()
```


يحصل على النص المستخدم كعلامة مائية.


**Returns:**
java.lang.String - السلسلة التي تمثل نص العلامة المائية.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يضبط النص المستخدم كعلامة مائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | السلسلة التي تمثل نص العلامة المائية. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


يحصل على خط النص.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


يضبط خط النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | خط النص. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


يحصل على لون المقدمة للنص.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


يضبط لون المقدمة للنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | لون المقدمة للنص. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


يحصل على لون الخلفية للنص.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


يضبط لون الخلفية للنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | لون الخلفية للنص. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


يحصل على محاذاة العلامة المائية `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

القيمة الافتراضية هي `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Returns:**
int - محاذاة العلامة المائية `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


يضبط محاذاة العلامة المائية `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`.

القيمة الافتراضية هي `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | محاذاة العلامة المائية `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`. |
|

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getForegroundColorConsideringOpacity() {#getForegroundColorConsideringOpacity--}
```
public final Color getForegroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getBackgroundColorConsideringOpacity() {#getBackgroundColorConsideringOpacity--}
```
public final Color getBackgroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getPadding() {#getPadding--}
```
public final Thickness getPadding()
```


يحصل على إعدادات الحشو لهذا `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. هذه الخاصية تنطبق فقط على ملفات الصور.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


يضبط إعدادات الحشو لهذا `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. هذه الخاصية تنطبق فقط على ملفات الصور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | إعدادات الحشو لهذا `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`. |
|

### deepClone() {#deepClone--}
```
public Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
