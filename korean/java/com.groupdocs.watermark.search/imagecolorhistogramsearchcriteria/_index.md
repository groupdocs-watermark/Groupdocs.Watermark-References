---
title: "ImageColorHistogramSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "콘텐츠에서 이미지를 찾기 위한 검색 기준을 나타냅니다."
type: docs
weight: 30
url: /ko/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

콘텐츠에서 이미지를 찾기 위한 검색 기준을 나타냅니다.

<br />

*** ** * ** ***

이 검색 기준은 이미지 유사성을 계산하기 위해 이미지 색상 히스토그램을 사용합니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | 지정된 파일 경로를 사용하여 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | 지정된 스트림을 사용하여 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | 색상 히스토그램을 구축하는 데 사용될 빈의 개수를 가져옵니다. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | 색상 히스토그램을 구축하는 데 사용될 빈의 개수를 설정합니다. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


지정된 파일 경로를 사용하여 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 이미지를 로드할 파일 경로. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


지정된 스트림을 사용하여 `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 이미지를 로드할 스트림. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


색상 히스토그램을 구축하는 데 사용될 빈의 개수를 가져옵니다.


**Returns:**
byte - 기본값은 10입니다.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


색상 히스토그램을 구축하는 데 사용될 빈의 개수를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | byte | 기본값은 10입니다. |
|

