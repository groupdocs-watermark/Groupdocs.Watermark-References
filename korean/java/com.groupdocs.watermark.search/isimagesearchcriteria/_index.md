---
title: "IsImageSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이미지 워터마크만 필터링하기 위한 검색 기준을 나타냅니다."
type: docs
weight: 34
url: /ko/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

이미지 워터마크만 필터링하기 위한 검색 기준을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


`[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


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

