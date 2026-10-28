---
title: "TextFormattingSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "텍스트 서식으로 필터링을 허용하는 기준을 나타냅니다."
type: docs
weight: 66
url: /ko/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

텍스트 서식으로 필터링을 허용하는 기준을 나타냅니다.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

다음 예제는 특정한
텍스트 서식(문서 유형에 관계없이).
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


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | 텍스트 전경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 가져옵니다. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | 텍스트 전경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 설정합니다. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | 텍스트 배경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 가져옵니다. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | 텍스트 배경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 설정합니다. |
|
|  | [getFontName()](#getFontName--) | 가능한 워터마크 텍스트 서식에 사용되는 글꼴 이름을 가져옵니다. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | 가능한 워터마크 텍스트 서식에 사용되는 글꼴 이름을 설정합니다. |
|
|  | [getMinFontSize()](#getMinFontSize--) | 글꼴 크기의 시작 값을 가져옵니다. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | 글꼴 크기의 시작 값을 설정합니다. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | 글꼴 크기의 종료 값을 가져옵니다. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | 글꼴 크기의 종료 값을 설정합니다. |
|
|  | [getFontBold()](#getFontBold--) | 워터마크 텍스트 서식에 사용되는 글꼴이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | 워터마크 텍스트 서식에 사용되는 글꼴이 굵게 표시되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getFontItalic()](#getFontItalic--) | 워터마크 텍스트 서식에 사용되는 글꼴이 이탤릭인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | 워터마크 텍스트 서식에 사용되는 글꼴이 이탤릭인지 여부를 나타내는 값을 설정합니다. |
|
|  | [getFontUnderline()](#getFontUnderline--) | 워터마크 텍스트 서식에 사용되는 글꼴이 밑줄인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | 워터마크 텍스트 서식에 사용되는 글꼴이 밑줄인지 여부를 나타내는 값을 설정합니다. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | 워터마크 텍스트 서식에 사용되는 글꼴이 취소선인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | 워터마크 텍스트 서식에 사용되는 글꼴이 취소선인지 여부를 나타내는 값을 설정합니다. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


`[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


텍스트 전경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 가져옵니다.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


텍스트 전경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | 텍스트 전경색으로 워터마크를 필터링하는 데 사용되는 색상 범위입니다. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


텍스트 배경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 가져옵니다.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


텍스트 배경색으로 워터마크를 필터링하는 데 사용되는 색상 범위를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | 텍스트 배경색으로 워터마크를 필터링하는 데 사용되는 색상 범위입니다. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


가능한 워터마크 텍스트 서식에 사용되는 글꼴 이름을 가져옵니다.


**Returns:**
java.lang.String - 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


가능한 워터마크 텍스트 서식에 사용되는 글꼴 이름을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


글꼴 크기의 시작 값을 가져옵니다.


**Returns:**
float - 글꼴 크기의 시작 값입니다.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


글꼴 크기의 시작 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 글꼴 크기의 시작 값입니다. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


글꼴 크기의 종료 값을 가져옵니다.


**Returns:**
float - 글꼴 크기의 종료 값입니다.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


글꼴 크기의 종료 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 글꼴 크기의 종료 값입니다. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


워터마크 텍스트 서식에 사용되는 글꼴이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
java.lang.Boolean - 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


워터마크 텍스트 서식에 사용되는 글꼴이 굵게 표시되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Boolean | 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


워터마크 텍스트 서식에 사용되는 글꼴이 이탤릭인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
java.lang.Boolean - 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


워터마크 텍스트 서식에 사용되는 글꼴이 이탤릭인지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Boolean | 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


워터마크 텍스트 서식에 사용되는 글꼴이 밑줄인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
java.lang.Boolean - 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


워터마크 텍스트 서식에 사용되는 글꼴이 밑줄인지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Boolean | 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


워터마크 텍스트 서식에 사용되는 글꼴이 취소선인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
java.lang.Boolean - 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


워터마크 텍스트 서식에 사용되는 글꼴이 취소선인지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Boolean | 기본값은 null이며, 이는 필터가 적용되지 않음을 의미합니다. |
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

