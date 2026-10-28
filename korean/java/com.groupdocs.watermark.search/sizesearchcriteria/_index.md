---
title: "SizeSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크 크기로 필터링을 허용하는 기준을 나타냅니다."
type: docs
weight: 57
url: /ko/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

워터마크 크기로 필터링을 허용하는 기준을 나타냅니다.

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
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | 지정된 차원, 시작 값 및 종료 값을 사용하여 `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | 시작 값을 가져옵니다. |
|
|  | [getMaximum()](#getMaximum--) | 종료 값을 가져옵니다. |
|
|  | [getDimension()](#getDimension--) | 검색할 워터마크의 차원을 가져옵니다. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


지정된 차원, 시작 값 및 종료 값을 사용하여 `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | dimension | int | 검색할 워터마크의 차원 `[Dimension](../../com.groupdocs.watermark.common/dimension)`. |
|
|  | min | double | 시작 값. |
|
|  | max | double | 끝 값. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


시작 값을 가져옵니다.


**Returns:**
double - 시작 값.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


종료 값을 가져옵니다.


**Returns:**
double - 끝 값.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


검색할 워터마크의 차원을 가져옵니다.


**Returns:**
int - 검색에 사용할 워터마크 차원.

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

