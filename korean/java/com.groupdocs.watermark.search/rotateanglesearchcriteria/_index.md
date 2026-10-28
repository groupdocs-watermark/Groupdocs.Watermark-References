---
title: "RotateAngleSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크 회전 각도로 필터링을 허용하는 기준을 나타냅니다."
type: docs
weight: 52
url: /ko/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

워터마크 회전 각도로 필터링을 허용하는 기준을 나타냅니다.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | 시작 각도와 종료 각도를 사용하여 `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | 시작 각도를 도 단위로 가져옵니다. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | 종료 각도를 도 단위로 가져옵니다. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


시작 각도와 종료 각도를 사용하여 `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | minAngle | double | 시작 각도(도). |
|
|  | maxAngle | double | 종료 각도(도). |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


시작 각도를 도 단위로 가져옵니다.


**Returns:**
double - 시작 각도.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


종료 각도를 도 단위로 가져옵니다.


**Returns:**
double - 종료 각도.

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

