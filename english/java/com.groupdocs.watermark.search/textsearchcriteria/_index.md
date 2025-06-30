---
title: TextSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents criteria allowing filtering by watermark text.
type: docs
weight: 67
url: /java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Represents criteria allowing filtering by watermark text.

**Learn more:**

 *  [Searching watermarks][]

The following example demonstrates how to find and remove watermark using search criteria.

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks
## Constructors

| Constructor | Description |
| --- | --- |
| [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Initializes a new instance of the `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` class with a specified regular expression. |
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
| [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Initializes a new instance of the `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` class with a search string and a flag for comparison. |
| [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Initializes a new instance of the `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` class with a search string. |
## Methods

| Method | Description |
| --- | --- |
| [getPattern()](#getPattern--) | Gets the search pattern. |
| [getPatternInternal()](#getPatternInternal--) |  |
| [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Gets a value indicating that unreadable characters will be skipped during string comparison. |
| [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Sets a value indicating that unreadable characters will be skipped during string comparison. |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Initializes a new instance of the `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` class with a specified regular expression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern | java.util.regex.Pattern | The regular expression to match. |

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Initializes a new instance of the `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` class with a search string and a flag for comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| searchString | java.lang.String | The exact string to search for. |
| isMatchCase | boolean | `false` to ignore case during the comparison; otherwise, `true`. |

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Initializes a new instance of the `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` class with a search string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| searchString | java.lang.String | The exact string to search for. |

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Gets the search pattern.

**Returns:**
java.util.regex.Pattern - The regular expression pattern to match.
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


Gets a value indicating that unreadable characters will be skipped during string comparison.

**Returns:**
boolean - A value indicating that unreadable characters will be skipped during string comparison.
### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Sets a value indicating that unreadable characters will be skipped during string comparison.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating that unreadable characters will be skipped during string comparison. |

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

