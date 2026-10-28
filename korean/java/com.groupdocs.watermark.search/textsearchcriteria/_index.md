---
title: "TextSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크 텍스트로 필터링을 허용하는 기준을 나타냅니다."
type: docs
weight: 67
url: /ko/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

워터마크 텍스트로 필터링을 허용하는 기준을 나타냅니다.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

다음 예제는 검색 기준을 사용하여 워터마크를 찾고 제거하는 방법을 보여줍니다.
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


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | 지정된 정규 표현식을 사용하여 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | 검색 문자열과 비교 플래그를 사용하여 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | 검색 문자열을 사용하여 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPattern()](#getPattern--) | 검색 패턴을 가져옵니다. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | 문자열 비교 중에 읽을 수 없는 문자를 건너뛸지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | 문자열 비교 중에 읽을 수 없는 문자를 건너뛸지 여부를 나타내는 값을 설정합니다. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


지정된 정규 표현식을 사용하여 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pattern | java.util.regex.Pattern | 일치시킬 정규 표현식. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pattern | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


검색 문자열과 비교 플래그를 사용하여 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | searchString | java.lang.String | 검색할 정확한 문자열. |
|
|  | isMatchCase | boolean | `false`는 비교 중 대소문자를 무시하도록; 그렇지 않으면 `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


검색 문자열을 사용하여 `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | searchString | java.lang.String | 검색할 정확한 문자열. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


검색 패턴을 가져옵니다.


**Returns:**
java.util.regex.Pattern - 일치시킬 정규식 패턴.

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


문자열 비교 중에 읽을 수 없는 문자를 건너뛸지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 문자열 비교 중 읽을 수 없는 문자를 건너뛸지 여부를 나타내는 값.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


문자열 비교 중에 읽을 수 없는 문자를 건너뛸지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 문자열 비교 중 읽을 수 없는 문자를 건너뛸지 여부를 나타내는 값. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

