---
title: TextFormattingSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents criteria allowing filtering by text formatting.
type: docs
weight: 66
url: /java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Represents criteria allowing filtering by text formatting.

**Learn more:**

 *  [Searching watermarks][]

The following example demonstrates how to remove possible watermarks with a particular text formatting (regardless of document type).

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Initializes a new instance of the `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getForegroundColorRange()](#getForegroundColorRange--) | Gets the range of colors which are used to filter watermarks by text foreground color. |
| [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Sets the range of colors which are used to filter watermarks by text foreground color. |
| [getBackgroundColorRange()](#getBackgroundColorRange--) | Gets the range of colors which are used to filter watermarks by text background color. |
| [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Sets the range of colors which are used to filter watermarks by text background color. |
| [getFontName()](#getFontName--) | Gets the name of the font which is used in possible watermark text formatting. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Sets the name of the font which is used in possible watermark text formatting. |
| [getMinFontSize()](#getMinFontSize--) | Gets the starting value of the font size. |
| [setMinFontSize(float value)](#setMinFontSize-float-) | Sets the starting value of the font size. |
| [getMaxFontSize()](#getMaxFontSize--) | Gets the ending value of the font size. |
| [setMaxFontSize(float value)](#setMaxFontSize-float-) | Sets the ending value of the font size. |
| [getFontBold()](#getFontBold--) | Gets a value indicating whether the font used in watermark text formatting is bold. |
| [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Sets a value indicating whether the font used in watermark text formatting is bold. |
| [getFontItalic()](#getFontItalic--) | Gets a value indicating whether the font used in watermark text formatting is italic. |
| [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Sets a value indicating whether the font used in watermark text formatting is italic. |
| [getFontUnderline()](#getFontUnderline--) | Gets a value indicating whether the font used in watermark text formatting is underline. |
| [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Sets a value indicating whether the font used in watermark text formatting is underline. |
| [getFontStrikeout()](#getFontStrikeout--) | Gets a value indicating whether the font used in watermark text formatting is strikeout. |
| [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Sets a value indicating whether the font used in watermark text formatting is strikeout. |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Initializes a new instance of the `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` class.

### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Gets the range of colors which are used to filter watermarks by text foreground color.

**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.
### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Sets the range of colors which are used to filter watermarks by text foreground color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | The range of colors which are used to filter watermarks by text foreground color. |

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Gets the range of colors which are used to filter watermarks by text background color.

**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.
### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Sets the range of colors which are used to filter watermarks by text background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | The range of colors which are used to filter watermarks by text background color. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Gets the name of the font which is used in possible watermark text formatting.

**Returns:**
java.lang.String - The default value is null, which means that the filter is not applied.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Sets the name of the font which is used in possible watermark text formatting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The default value is null, which means that the filter is not applied. |

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Gets the starting value of the font size.

**Returns:**
float - The starting value of the font size.
### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Sets the starting value of the font size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The starting value of the font size. |

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Gets the ending value of the font size.

**Returns:**
float - The ending value of the font size.
### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Sets the ending value of the font size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The ending value of the font size. |

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Gets a value indicating whether the font used in watermark text formatting is bold.

**Returns:**
java.lang.Boolean - The default value is null, which means that the filter is not applied.
### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Sets a value indicating whether the font used in watermark text formatting is bold.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | The default value is null, which means that the filter is not applied. |

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Gets a value indicating whether the font used in watermark text formatting is italic.

**Returns:**
java.lang.Boolean - The default value is null, which means that the filter is not applied.
### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Sets a value indicating whether the font used in watermark text formatting is italic.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | The default value is null, which means that the filter is not applied. |

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Gets a value indicating whether the font used in watermark text formatting is underline.

**Returns:**
java.lang.Boolean - The default value is null, which means that the filter is not applied.
### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Sets a value indicating whether the font used in watermark text formatting is underline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | The default value is null, which means that the filter is not applied. |

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Gets a value indicating whether the font used in watermark text formatting is strikeout.

**Returns:**
java.lang.Boolean - The default value is null, which means that the filter is not applied.
### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Sets a value indicating whether the font used in watermark text formatting is strikeout.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | The default value is null, which means that the filter is not applied. |

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

