---
title: "ImageDctHashSearchCriteria"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "문서에서 이미지를 찾기 위한 검색 기준을 나타냅니다."
type: docs
weight: 31
url: /ko/java/com.groupdocs.watermark.search/imagedcthashsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageDctHashSearchCriteria extends ImageSearchCriteria
```

문서에서 이미지를 찾기 위한 검색 기준을 나타냅니다.

이 검색 기준은 이미지 유사도 계산을 위해 DCT 기반 지각 이미지 해시를 사용합니다.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

다음 예제는 첨부된 파일(pdf)에서 이미지를 검색하는 방법을 보여줍니다.
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>    
>    // Specify sample image to compare document images with
>    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria("D:\\sample.png");
>    // Search for similar images
>    PossibleWatermarkCollection possibleWatermarks = watermarker.search(criteria);
>    // Remove or modify found image watermarks
>    // ...
>    
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageDctHashSearchCriteria(String filePath)](#ImageDctHashSearchCriteria-java.lang.String-) | 지정된 파일 경로를 사용하여 `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [ImageDctHashSearchCriteria(InputStream stream)](#ImageDctHashSearchCriteria-java.io.InputStream-) | 지정된 스트림을 사용하여 `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다. |
|
| [ImageDctHashSearchCriteria(System.IO.Stream stream)](#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-) |  |
### ImageDctHashSearchCriteria(String filePath) {#ImageDctHashSearchCriteria-java.lang.String-}
```
public ImageDctHashSearchCriteria(String filePath)
```


지정된 파일 경로를 사용하여 `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 이미지를 로드할 파일 경로. |
|

### ImageDctHashSearchCriteria(InputStream stream) {#ImageDctHashSearchCriteria-java.io.InputStream-}
```
public ImageDctHashSearchCriteria(InputStream stream)
```


지정된 스트림을 사용하여 `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 이미지를 로드할 스트림. |
|

### ImageDctHashSearchCriteria(System.IO.Stream stream) {#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-}
```
public ImageDctHashSearchCriteria(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | com.aspose.ms.System.IO.Stream |  |

