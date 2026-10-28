---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير تسمح بالترشيح حسب تنسيق النص."
type: docs
weight: 66
url: /ar/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

يمثل معايير تسمح بالترشيح حسب تنسيق النص.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

يوضح المثال التالي كيفية إزالة العلامات المائية المحتملة ذات
تنسيق النص (بغض النظر عن نوع المستند).
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.doc");
>    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
>
>    criteria.setForegroundColorRange(new ColorRange());
>    criteria.getForegroundColorRange().setMinHue(-5);
>    criteria.getForegroundColorRange().setMaxHue(10);
>    criteria.getForegroundColorRange().setMinBrightness(0.01f);
>    criteria.getForegroundColorRange().setMaxBrightness(0.99f);
>    criteria.setBackgroundColorRange(new ColorRange());
>    criteria.getBackgroundColorRange().setEmpty(true);
>    criteria.setFontName("Arial");
>    criteria.setMinFontSize(19);
>    criteria.setMaxFontSize(42);
>    criteria.setFontBold(true);
>
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | يُنشئ مثيلاً جديدًا للفئة `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | يحصل على نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون النص الأمامي. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | يضبط نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون النص الأمامي. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | يحصل على نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون خلفية النص. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | يضبط نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون خلفية النص. |
|
|  | [getFontName()](#getFontName--) | يحصل على اسم الخط المستخدم في تنسيق النص للعلامة المائية المحتملة. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | يضبط اسم الخط المستخدم في تنسيق النص للعلامة المائية المحتملة. |
|
|  | [getMinFontSize()](#getMinFontSize--) | يحصل على القيمة الابتدائية لحجم الخط. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | يضبط القيمة الابتدائية لحجم الخط. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | يحصل على القيمة النهائية لحجم الخط. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | يضبط القيمة النهائية لحجم الخط. |
|
|  | [getFontBold()](#getFontBold--) | يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية غامقًا. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية غامقًا. |
|
|  | [getFontItalic()](#getFontItalic--) | يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مائلًا. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مائلًا. |
|
|  | [getFontUnderline()](#getFontUnderline--) | يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية تحته خط. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية تحته خط. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مشطوبًا. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مشطوبًا. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


يُنشئ مثيلاً جديدًا للفئة `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


يحصل على نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون النص الأمامي.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


يضبط نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون النص الأمامي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون النص الأمامي. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


يحصل على نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون خلفية النص.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


يضبط نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون خلفية النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون خلفية النص. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


يحصل على اسم الخط المستخدم في تنسيق النص للعلامة المائية المحتملة.


**Returns:**
java.lang.String - القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


يضبط اسم الخط المستخدم في تنسيق النص للعلامة المائية المحتملة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


يحصل على القيمة الابتدائية لحجم الخط.


**Returns:**
float - القيمة الابتدائية لحجم الخط.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


يضبط القيمة الابتدائية لحجم الخط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | القيمة الابتدائية لحجم الخط. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


يحصل على القيمة النهائية لحجم الخط.


**Returns:**
float - القيمة النهائية لحجم الخط.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


يضبط القيمة النهائية لحجم الخط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | القيمة النهائية لحجم الخط. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية غامقًا.


**Returns:**
java.lang.Boolean - القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية غامقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.Boolean | القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مائلًا.


**Returns:**
java.lang.Boolean - القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مائلًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.Boolean | القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية تحته خط.


**Returns:**
java.lang.Boolean - القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية تحته خط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.Boolean | القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


يحصل على قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مشطوبًا.


**Returns:**
java.lang.Boolean - القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الخط المستخدم في تنسيق النص للعلامة المائية مشطوبًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.Boolean | القيمة الافتراضية هي null، مما يعني أن الفلتر غير مطبق. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

