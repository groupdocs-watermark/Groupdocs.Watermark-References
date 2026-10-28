---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示允许按水印文本进行过滤的条件。"
type: docs
weight: 67
url: /zh/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

表示允许按水印文本进行过滤的条件。

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

以下示例演示如何使用搜索条件查找并移除水印。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
>    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
>    TextSearchCriteria textCriteria = new TextSearchCriteria(Pattern.compile("^Test watermark$"));
>
>    PossibleWatermarkCollection watermarks = watermarker.search(textCriteria.and(widthRange.or(rotateAngle)));
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
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | 使用指定的正则表达式初始化 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 类的新实例。 |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | 使用搜索字符串和比较标志初始化 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 类的新实例。 |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | 使用搜索字符串初始化 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPattern()](#getPattern--) | 获取搜索模式。 |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | 获取一个值，指示在字符串比较期间将跳过不可读字符。 |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | 设置一个值，指示在字符串比较期间将跳过不可读字符。 |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


使用指定的正则表达式初始化 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pattern | java.util.regex.Pattern | 用于匹配的正则表达式。 |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pattern | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


使用搜索字符串和比较标志初始化 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | searchString | java.lang.String | 要搜索的精确字符串。 |
|
|  | isMatchCase | boolean | `false` 表示在比较期间忽略大小写；否则为 `true`。 |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


使用搜索字符串初始化 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | searchString | java.lang.String | 要搜索的精确字符串。 |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


获取搜索模式。


**Returns:**
java.util.regex.Pattern - 用于匹配的正则表达式模式。

### getPatternInternal() {#getPatternInternal--}
```
public final System.Text.RegularExpressions.Regex getPatternInternal()
```




**Returns:**
com.aspose.ms.System.Text.RegularExpressions.Regex
### getSkipUnreadableCharacters() {#getSkipUnreadableCharacters--}
```
public final boolean getSkipUnreadableCharacters()
```


获取一个值，指示在字符串比较期间将跳过不可读字符。


**Returns:**
boolean - 表示在字符串比较期间将跳过不可读字符的值。

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


设置一个值，指示在字符串比较期间将跳过不可读字符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 表示在字符串比较期间将跳过不可读字符的值。 |
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

