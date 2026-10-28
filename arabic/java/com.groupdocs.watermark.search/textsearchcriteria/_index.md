---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير تسمح بالترشيح حسب نص العلامة المائية."
type: docs
weight: 67
url: /ar/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

يمثل معايير تسمح بالترشيح حسب نص العلامة المائية.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

يوضح المثال التالي كيفية العثور على العلامة المائية وإزالتها باستخدام معايير البحث.
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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | ينشئ مثيلاً جديدًا لفئة `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` باستخدام تعبير نمطي محدد. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | ينشئ مثيلاً جديدًا لفئة `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` باستخدام سلسلة بحث وعلم للمقارنة. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | ينشئ مثيلاً جديدًا لفئة `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` باستخدام سلسلة بحث. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPattern()](#getPattern--) | يحصل على نمط البحث. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | يحصل على قيمة تشير إلى أنه سيتم تخطي الأحرف غير القابلة للقراءة أثناء مقارنة السلاسل. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | يضبط قيمة تشير إلى أنه سيتم تخطي الأحرف غير القابلة للقراءة أثناء مقارنة السلاسل. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


ينشئ مثيلاً جديدًا لفئة `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` باستخدام تعبير نمطي محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نمط | java.util.regex.Pattern | التعبير النمطي للمطابقة. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نمط | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


ينشئ مثيلاً جديدًا لفئة `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` باستخدام سلسلة بحث وعلم للمقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchString | java.lang.String | السلسلة الدقيقة للبحث عنها. |
|
|  | isMatchCase | boolean | `false` لتجاهل حالة الأحرف أثناء المقارنة؛ وإلا، `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


ينشئ مثيلاً جديدًا لفئة `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` باستخدام سلسلة بحث.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchString | java.lang.String | السلسلة الدقيقة للبحث عنها. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


يحصل على نمط البحث.


**Returns:**
java.util.regex.Pattern - نمط التعبير النمطي للمطابقة.

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


يحصل على قيمة تشير إلى أنه سيتم تخطي الأحرف غير القابلة للقراءة أثناء مقارنة السلاسل.


**Returns:**
boolean - قيمة تشير إلى أنه سيتم تخطي الأحرف غير القابلة للقراءة أثناء مقارنة السلاسل.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


يضبط قيمة تشير إلى أنه سيتم تخطي الأحرف غير القابلة للقراءة أثناء مقارنة السلاسل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | قيمة تشير إلى أنه سيتم تخطي الأحرف غير القابلة للقراءة أثناء مقارنة السلاسل. |
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

