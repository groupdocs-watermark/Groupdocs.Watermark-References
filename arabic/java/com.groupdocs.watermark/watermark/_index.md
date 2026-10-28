---
title: "علامة مائية"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل علامة مائية لإضافتها إلى مستند."
type: docs
weight: 13
url: /ar/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

يمثل علامة مائية لإضافتها إلى مستند.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | يحصل أو يضبط شفافية هذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | يحصل أو يضبط شفافية هذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getY()](#getY--) | يحصل على الإحداثي ص لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setY(double value)](#setY-double-) | يضبط الإحداثي ص لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getX()](#getX--) | يحصل على الإحداثي س لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setX(double value)](#setX-double-) | يضبط الإحداثي س لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | يحصل على المحاذاة العمودية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | يضبط المحاذاة العمودية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | يحصل على المحاذاة الأفقية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | يضبط المحاذاة الأفقية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية الدوران لهذا `[Watermark](../../com.groupdocs.watermark/watermark)` بالدرجات. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | يضبط زاوية الدوران لهذا `[Watermark](../../com.groupdocs.watermark/watermark)` بالدرجات. |
|
|  | [isBackground()](#isBackground--) | يحصل على قيمة تشير إلى ما إذا كان يجب وضع العلامة المائية في الخلفية. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب وضع العلامة المائية في الخلفية. |
|
|  | [getMargins()](#getMargins--) | يحصل على إعدادات الهوامش لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | يضبط إعدادات الهوامش لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getPagesSetup()](#getPagesSetup--) | يحصل على إعدادات إعداد الصفحات لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | يضبط إعدادات إعداد الصفحات لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHeight()](#getHeight--) | يحصل على الارتفاع المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHeight(double value)](#setHeight-double-) | يضبط الارتفاع المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getWidth()](#getWidth--) | يحصل على العرض المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setWidth(double value)](#setWidth-double-) | يضبط العرض المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getScaleFactor()](#getScaleFactor--) | يحصل على قيمة تحدد كيفية اعتماد حجم العلامة المائية على حجم العنصر الأصلي. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | يضبط قيمة تحدد كيفية اعتماد حجم العلامة المائية على حجم العنصر الأصلي. |
|
|  | [getSizingType()](#getSizingType--) | يحصل على قيمة تحدد طريقة قياس حجم العلامة المائية. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | يضبط قيمة تحدد طريقة قياس حجم العلامة المائية. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | يحصل على قيمة تشير إلى ما إذا كان يتم حساب حجم العلامة المائية والإحداثيات |
مع مراعاة هوامش العنصر الأصلي.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم حساب حجم العلامة المائية والإحداثيات |
مع مراعاة هوامش العنصر الأصلي.
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


يحصل أو يضبط شفافية هذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

يجب أن تكون قيمة الشفافية بين 0 و 1. القيمة الافتراضية هي 1.


**Returns:**
double - شفافية هذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


يحصل أو يضبط شفافية هذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

يجب أن تكون قيمة الشفافية بين 0 و 1. القيمة الافتراضية هي 1.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | شفافية هذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


يحصل على الإحداثي ص لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - الإحداثي ص لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


يضبط الإحداثي ص لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإحداثي ص لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


يحصل على الإحداثي س لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - الإحداثي س لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


يضبط الإحداثي س لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الإحداثي س لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


يحصل على المحاذاة العمودية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

القيمة الافتراضية هي `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - الـ`[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


يضبط المحاذاة العمودية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

القيمة الافتراضية هي `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | الـ`[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


يحصل على المحاذاة الأفقية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

القيمة الافتراضية هي `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - الـ`[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


يضبط المحاذاة الأفقية لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

القيمة الافتراضية هي `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | الـ `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


يحصل على زاوية الدوران لهذا `[Watermark](../../com.groupdocs.watermark/watermark)` بالدرجات.


**Returns:**
double - زاوية الدوران لهذا `[Watermark](../../com.groupdocs.watermark/watermark)` بالدرجات.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


يضبط زاوية الدوران لهذا `[Watermark](../../com.groupdocs.watermark/watermark)` بالدرجات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | زاوية الدوران لهذا `[Watermark](../../com.groupdocs.watermark/watermark)` بالدرجات. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


يحصل على قيمة تشير إلى ما إذا كان يجب وضع العلامة المائية في الخلفية.


**Returns:**
boolean - إذا كانت القيمة true، سيتم وضع العلامة المائية في الأسفل. بشكل افتراضي، القيمة false، سيتم وضع العلامة المائية في الأعلى.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب وضع العلامة المائية في الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | إذا كانت القيمة true، سيتم وضع العلامة المائية في الأسفل. بشكل افتراضي، القيمة false، سيتم وضع العلامة المائية في الأعلى. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


يحصل على إعدادات الهوامش لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


يضبط إعدادات الهوامش لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | إعدادات الهوامش لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


يحصل على إعدادات إعداد الصفحات لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


يضبط إعدادات إعداد الصفحات لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | إعدادات صفحات هذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


يحصل على الارتفاع المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - الارتفاع المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


يضبط الارتفاع المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

ضبط هذه الخاصية سيغير أيضًا قيمة `#getSizingType().getSizingType()`.
خاصية إلى `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الارتفاع المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


يحصل على العرض المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - العرض المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


يضبط العرض المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

ضبط هذه الخاصية سيغير أيضًا قيمة `#getSizingType().getSizingType()`.
خاصية إلى `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | العرض المطلوب لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


يحصل على قيمة تحدد كيفية اعتماد حجم العلامة المائية على حجم العنصر الأصلي.

يجب أن تكون القيمة بين 0 و 1.


**Returns:**
double - معامل التحجيم لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


يضبط قيمة تحدد كيفية اعتماد حجم العلامة المائية على حجم العنصر الأصلي.

يجب أن تكون القيمة بين 0 و 1.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | معامل التحجيم لهذا `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


يحصل على قيمة تحدد طريقة قياس حجم العلامة المائية.


**Returns:**
int - نوع التحجيم.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


يضبط قيمة تحدد طريقة قياس حجم العلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | نوع التحجيم. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


يحصل على قيمة تشير إلى ما إذا كان يتم حساب حجم العلامة المائية والإحداثيات
مع مراعاة هوامش العنصر الأصلي.


**Returns:**
boolean - إذا كانت القيمة true، يتم حساب حجم العلامة المائية والإحداثيات مع مراعاة هوامش الأصل. بشكل افتراضي، القيمة false، يتم تجاهل هوامش الأصل.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يتم حساب حجم العلامة المائية والإحداثيات
مع مراعاة هوامش العنصر الأصلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | إذا كانت القيمة true، يتم حساب حجم العلامة المائية والإحداثيات مع مراعاة هوامش الأصل. بشكل افتراضي، القيمة false، يتم تجاهل هوامش الأصل. |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
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
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
