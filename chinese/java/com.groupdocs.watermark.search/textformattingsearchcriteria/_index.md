---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示允许按文本格式进行过滤的条件。"
type: docs
weight: 66
url: /zh/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

表示允许按文本格式进行过滤的条件。

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

以下示例演示如何使用特定的
文本格式（不考虑文档类型）。
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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | 初始化 `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | 获取用于按文本前景色过滤水印的颜色范围。 |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | 设置用于按文本前景色过滤水印的颜色范围。 |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | 获取用于按文本背景色过滤水印的颜色范围。 |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | 设置用于按文本背景色过滤水印的颜色范围。 |
|
|  | [getFontName()](#getFontName--) | 获取在可能的水印文本格式中使用的字体名称。 |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | 设置在可能的水印文本格式中使用的字体名称。 |
|
|  | [getMinFontSize()](#getMinFontSize--) | 获取字体大小的起始值。 |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | 设置字体大小的起始值。 |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | 获取字体大小的结束值。 |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | 设置字体大小的结束值。 |
|
|  | [getFontBold()](#getFontBold--) | 获取指示水印文本格式中使用的字体是否为粗体的值。 |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | 设置指示水印文本格式中使用的字体是否为粗体的值。 |
|
|  | [getFontItalic()](#getFontItalic--) | 获取指示水印文本格式中使用的字体是否为斜体的值。 |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | 设置指示水印文本格式中使用的字体是否为斜体的值。 |
|
|  | [getFontUnderline()](#getFontUnderline--) | 获取指示水印文本格式中使用的字体是否带下划线的值。 |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | 设置指示水印文本格式中使用的字体是否带下划线的值。 |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | 获取指示水印文本格式中使用的字体是否带删除线的值。 |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | 设置一个值，指示用于水印文本格式的字体是否为删除线。 |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


初始化 `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` 类的新实例。


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


获取用于按文本前景色过滤水印的颜色范围。


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


设置用于按文本前景色过滤水印的颜色范围。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | 用于按文本前景色过滤水印的颜色范围。 |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


获取用于按文本背景色过滤水印的颜色范围。


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


设置用于按文本背景色过滤水印的颜色范围。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | 用于按文本背景色过滤水印的颜色范围。 |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


获取在可能的水印文本格式中使用的字体名称。


**Returns:**
`java.lang.String` - 默认值为 null，这意味着过滤未应用。

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


设置在可能的水印文本格式中使用的字体名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 默认值为 null，这意味着过滤未应用。 |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


获取字体大小的起始值。


**Returns:**
`float` - 字体大小的起始值。

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


设置字体大小的起始值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 字体大小的起始值。 |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


获取字体大小的结束值。


**Returns:**
`float` - 字体大小的结束值。

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


设置字体大小的结束值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 字体大小的结束值。 |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


获取指示水印文本格式中使用的字体是否为粗体的值。


**Returns:**
`java.lang.Boolean` - 默认值为 null，这意味着过滤未应用。

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


设置指示水印文本格式中使用的字体是否为粗体的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | `java.lang.Boolean` | 默认值为 null，这意味着过滤未应用。 |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


获取指示水印文本格式中使用的字体是否为斜体的值。


**Returns:**
`java.lang.Boolean` - 默认值为 null，这意味着过滤未应用。

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


设置指示水印文本格式中使用的字体是否为斜体的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | `java.lang.Boolean` | 默认值为 null，这意味着过滤未应用。 |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


获取指示水印文本格式中使用的字体是否带下划线的值。


**Returns:**
`java.lang.Boolean` - 默认值为 null，这意味着过滤未应用。

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


设置指示水印文本格式中使用的字体是否带下划线的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | `java.lang.Boolean` | 默认值为 null，这意味着过滤未应用。 |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


获取指示水印文本格式中使用的字体是否带删除线的值。


**Returns:**
`java.lang.Boolean` - 默认值为 null，这意味着过滤未应用。

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


设置一个值，指示用于水印文本格式的字体是否为删除线。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | `java.lang.Boolean` | 默认值为 null，这意味着过滤未应用。 |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

