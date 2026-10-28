---
title: "ImageThumbnailSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "콘텐츠에서 이미지를 찾기 위한 검색 기준을 나타냅니다."
type: docs
weight: 33
url: /ko/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

콘텐츠에서 이미지를 찾기 위한 검색 기준을 나타냅니다.

<br />

*** ** * ** ***

이 검색 기준은 이미지 유사도 계산을 위해 이진화된 이미지 썸네일을 사용합니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | 지정된 파일 경로를 사용하여 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | 지정된 스트림을 사용하여 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | 썸네일 크기를 가져옵니다. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | 썸네일 크기를 설정합니다. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


지정된 파일 경로를 사용하여 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 이미지를 로드할 파일 경로. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


지정된 스트림을 사용하여 `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 이미지를 로드할 스트림. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


썸네일 크기를 가져옵니다.


**Returns:**
byte - 기본적으로 32X32 썸네일이 사용됩니다.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


썸네일 크기를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | byte | 기본적으로 32X32 썸네일이 사용됩니다. |
|

