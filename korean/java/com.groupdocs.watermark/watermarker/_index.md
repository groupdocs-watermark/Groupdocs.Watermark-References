---
title: "Watermarker"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "문서 내 워터마크 관리를 위한 클래스를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

문서 내 워터마크 관리를 위한 클래스를 나타냅니다.

다음 예제는 지원되는 모든 형식의 콘텐츠를 로드하고 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | 지정된 문서 경로로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | 지정된 문서 경로와 로드 옵션으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | 지정된 문서 경로와 설정으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | 지정된 문서 경로, 로드 옵션 및 설정으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | 지정된 스트림으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | 지정된 스트림과 로드 옵션으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | 지정된 스트림과 설정으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | 지정된 스트림, 로드 옵션 및 설정으로 클래스의 새 인스턴스를 초기화합니다. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | 워터마크 검색에 포함될 콘텐츠 객체를 가져옵니다. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | 워터마크 검색에 포함될 콘텐츠 객체를 설정합니다. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | 현재 인스턴스를 해제합니다. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | 로드된 문서 형식에 대한 정보를 가져옵니다. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | 로드된 문서에 워터마크를 추가합니다. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | 워터마크 옵션을 사용하여 로드된 문서에 워터마크를 추가합니다. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | 문서에서 워터마크를 제거합니다. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | 문서에서 컬렉션에 있는 모든 워터마크를 제거합니다. |
|
|  | [save(String filePath)](#save-java.lang.String-) | 지정된 파일 위치에 문서를 저장합니다. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | 지정된 스트림에 문서를 저장합니다. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | 저장 옵션을 사용하여 지정된 파일 위치에 문서를 저장합니다. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | 저장 옵션을 사용하여 지정된 스트림에 문서를 저장합니다. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | 문서에 대한 미리보기 이미지를 생성합니다. |
|
|  | [search()](#search--) | 문서에서 가능한 모든 워터마크를 검색합니다. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | 지정된 검색 기준에 따라 가능한 워터마크를 검색합니다. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | 지정된 검색 기준에 따라 이미지를 찾습니다. |
|
|  | [getImages()](#getImages--) | 문서에서 모든 이미지를 찾습니다. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | 로드된 문서에 대한 `[Content](../../com.groupdocs.watermark.contents/content)` 객체를 반환합니다. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


지정된 문서 경로로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

다음 예제는 지원되는 모든 형식의 콘텐츠를 로드하고 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서를 로드할 파일 경로입니다. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


지정된 문서 경로와 로드 옵션으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

다음 예제는 비밀번호를 사용하여 암호화된 PDF 문서를 로드하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.pdf", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서를 로드할 파일 경로입니다. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 문서를 로드할 때 사용할 추가 옵션입니다. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


지정된 문서 경로와 설정으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

다음 예제는 검색 가능한 객체를 전역적으로 설정하는 방법을 보여줍니다 (모든 문서에 대해
그 이후에 로드됩니다).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           Watermarker watermarker = new Watermarker(fileEntry.getPath(), settings);
>           PossibleWatermarkCollection watermarks = watermarker.search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서를 로드할 파일 경로입니다. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 로드된 문서를 작업할 때 사용할 추가 설정입니다. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


지정된 문서 경로, 로드 옵션 및 설정으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

다음 예제는 이메일 메시지 본문/제목에서 특정 텍스트 조각을 찾는 방법을 보여줍니다.
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker("D:\\test.msg", loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save("D:\\modified_test.msg");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서를 로드할 파일 경로입니다. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 문서를 로드할 때 사용할 추가 옵션입니다. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 로드된 문서를 작업할 때 사용할 추가 설정입니다. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


지정된 스트림으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

다음 예제는 지원되는 모든 형식의 문서를 로드하고 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    // Load a content from a stream.
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    FileOutputStream outputStream = new FileOutputStream("D:\\output.pdf");
>    Watermarker watermarker = new Watermarker(inputStream);
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서를 로드하기 위한 스트림입니다. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


지정된 스트림과 로드 옵션으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

다음 예제는 비밀번호를 사용하여 암호화된 PDF 문서를 로드하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions);
>    // ...
>
>    watermarker.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서를 로드하기 위한 스트림입니다. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 문서를 로드할 때 사용할 추가 옵션입니다. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


지정된 스트림과 설정으로 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

다음 예제는 검색 가능한 객체를 전역적으로 설정하는 방법을 보여줍니다 (모든 문서에 대해
그 이후에 로드됩니다).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           FileInputStream inputStream = new FileInputStream(fileEntry.getPath());
>           Watermarker watermarker = new Watermarker(inputStream, settings);
>           PossibleWatermarkCollection watermarks = watermarker.Search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>           inputStream.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서를 로드하기 위한 스트림입니다. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 로드된 문서를 작업할 때 사용할 추가 설정입니다. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


지정된 스트림, 로드 옵션 및 설정으로 클래스의 새 인스턴스를 초기화합니다.

문서 로드에 대해 자세히 알아보세요:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

다음 예제는 검색 가능한 객체를 전역적으로 설정하는 방법을 보여줍니다 (모든 문서에 대해
그 이후에 로드됩니다).
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    FileInputStream inputStream = new FileInputStream("D:\\test.msg");
>    FileOutputStream outputStream = new FileOutputStream("D:\\modified_test.msg");
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서를 로드하기 위한 스트림입니다. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 문서를 로드할 때 사용할 추가 옵션입니다. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 로드된 문서를 작업할 때 사용할 추가 설정입니다. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 문서 | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


워터마크 검색에 포함될 콘텐츠 객체를 가져옵니다.

이 메서드는 이미지 검색에 사용되는 콘텐츠 객체도 지정합니다.
자세한 내용은 `#search(SearchCriteria).search(SearchCriteria)`를 참조하십시오.
그리고 `#getImages().getImages()` 메서드.

워터마크 검색에 대해 자세히 알아보세요:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

다음 예제는 PDF 문서에서 모든 XObjects와 아티팩트를 제거하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The objects that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


워터마크 검색에 포함될 콘텐츠 객체를 설정합니다.

이 메서드는 이미지 검색에 사용되는 콘텐츠 객체도 지정합니다.
자세한 내용은 `#search(SearchCriteria).search(SearchCriteria)`를 참조하십시오.
그리고 `#getImages().getImages()` 메서드.
워터마크 검색에 대해 자세히 알아보세요:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

다음 예제는 PDF 문서에서 모든 XObjects와 아티팩트를 제거하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | 워터마크 검색에 포함될 객체들입니다. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


현재 인스턴스를 해제합니다.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


로드된 문서 형식에 대한 정보를 가져옵니다.

문서 정보 가져오기에 대해 자세히 알아보세요
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

다음 예제는 지원되는 모든 유형의 문서에 대한 정보를 가져오는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.ppt");
>    IDocumentInfo info = watermarker.getDocumentInfo();
>    System.out.println("File type: " + info.getFileType());
>    System.out.println("Number of pages: " + info.getPageCount());
>    System.out.println("Document size: " + info.getSize() + " bytes");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


로드된 문서에 워터마크를 추가합니다.

워터마크 추가에 대해 자세히 알아보세요:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

다음 예제는 지원되는 모든 유형의 문서에 이미지 및 텍스트 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>    textWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    textWatermark.setVerticalAlignment(VerticalAlignment.Top);
>    textWatermark.setConsiderParentMargins(true);
>    textWatermark.setForegroundColor(Color.getRed());
>    textWatermark.setBackground(true);
>    textWatermark.setOpacity(0.5);
>    watermarker.add(textWatermark);
>  
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    imageWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    imageWatermark.setVerticalAlignment(VerticalAlignment.Bottom);
>    imageWatermark.setConsiderParentMargins(true);
>    imageWatermark.setBackground(true);
>    imageWatermark.setOpacity(0.5);
>    watermarker.add(imageWatermark);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | 문서에 추가할 워터마크입니다. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


워터마크 옵션을 사용하여 로드된 문서에 워터마크를 추가합니다.

워터마크 추가에 대해 자세히 알아보세요:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

다음 예제는 PDF 문서의 특정 페이지에 이미지 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.pdf", loadOptions);
>
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>    watermarker.add(imageWatermark, options);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | 문서에 추가할 워터마크입니다. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | 워터마크를 추가할 때 사용할 추가 옵션입니다. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


문서에서 워터마크를 제거합니다.

워터마크 제거에 대해 자세히 알아보세요:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

다음 예제는 특정 내용을 포함하는 첫 번째 가능한 워터마크를 찾고 제거하는 방법을 보여줍니다.
텍스트 또는 이미지를 포함하는 워터마크를 지원되는 모든 유형의 문서에서.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    if (watermarks.getCount() > 0)
>    {
>        watermarker.remove(watermarks.get_Item(0));
>    }
>
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | 제거할 워터마크입니다. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


문서에서 컬렉션에 있는 모든 워터마크를 제거합니다.

워터마크 제거에 대해 자세히 알아보세요:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

다음 예제는 특정 내용을 포함하는 모든 가능한 워터마크를 찾고 제거하는 방법을 보여줍니다.
텍스트 또는 이미지를 포함하는 워터마크를 지원되는 모든 유형의 문서에서.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarker.remove(watermarks);
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | 제거할 워터마크 컬렉션입니다. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


지정된 파일 위치에 문서를 저장합니다.

문서 저장에 대해 자세히 알아보세요
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

다음 예제는 워터마크를 추가하고 문서를 다른 파일에 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서 데이터를 저장할 파일 경로. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


지정된 스트림에 문서를 저장합니다.

문서 저장에 대해 자세히 알아보세요
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

다음 예제는 워터마크를 추가하고 문서를 메모리 스트림에 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream);
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 문서 데이터를 저장할 스트림. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


저장 옵션을 사용하여 지정된 파일 위치에 문서를 저장합니다.

문서 저장에 대해 자세히 알아보세요
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

다음 예제는 워터마크를 추가하고 문서를 다른 파일에 저장하는 방법을 보여줍니다.
기본 `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`와 함께.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf", new SaveOptions());
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 문서 데이터를 저장할 파일 경로. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | 문서를 저장할 때 사용할 추가 옵션. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


저장 옵션을 사용하여 지정된 스트림에 문서를 저장합니다.

문서 저장에 대해 자세히 알아보세요
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

다음 예제는 워터마크를 추가하고 문서를 메모리 스트림에 저장하는 방법을 보여줍니다.
기본 `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`와 함께.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream, new SaveOptions());
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 문서 데이터를 저장할 스트림. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | 문서를 저장할 때 사용할 추가 옵션. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


문서에 대한 미리보기 이미지를 생성합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | 미리보기 이미지를 생성할 때 사용할 추가 옵션. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


문서에서 가능한 모든 워터마크를 검색합니다.

검색은 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`로 지정된 객체에서 수행됩니다.

워터마크 검색에 대해 자세히 알아보기
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

다음 예제는 지원되는 모든 유형의 문서에서 가능한 워터마크 수를 계산하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    System.out.println(watermarks.getCount());
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


지정된 검색 기준에 따라 가능한 워터마크를 검색합니다.

검색은 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`로 지정된 객체에서 수행됩니다.

워터마크 검색에 대해 자세히 알아보기
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

다음 예제는 특정 텍스트를 포함하는 모든 가능한 워터마크를 찾고 제거하는 방법을 보여줍니다.
또는 지원되는 모든 유형의 문서에서 이미지.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarks.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | 사용할 검색 기준. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


지정된 검색 기준에 따라 이미지를 찾습니다.

검색은 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`로 지정된 객체에서 수행됩니다.

워터마크 검색에 대해 자세히 알아보기
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

다음 예제는 참조와 유사한 모든 이미지를 제거하는 방법을 보여줍니다.
지원되는 모든 유형의 문서에서.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
>    WatermarkableImageCollection images = watermarker.getImages(criteria);
>    images.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | 사용할 검색 기준. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


문서에서 모든 이미지를 찾습니다.

검색은 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`로 지정된 객체에서 수행됩니다.

워터마크 검색에 대해 자세히 알아보기
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

다음 예제는 지원되는 모든 유형의 문서에 있는 모든 이미지에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>
>    // Find all images in the document.
>    WatermarkableImageCollection images = watermarker.getImages();
>
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.addWatermark(watermark);
>    }
>
>    // Save changes.
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of found images.

### <T>getContent(Class<T> contentType) {#-T-getContent-java.lang.Class-T--}
```
public final T <T>getContent(Class<T> contentType)
```


로드된 문서에 대한 `[Content](../../com.groupdocs.watermark.contents/content)` 객체를 반환합니다.

다음 예제는 추가된 워터마크와 함께 PDF 문서 페이지를 래스터화하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("input.pdf", loadOptions);
>    ImageWatermark watermark = new ImageWatermark("watermark.png")
>    watermarker.add(watermark);
>    PdfContent content = watermarker.getContent(PdfContent.class);
>    content.rasterize(300, 300, PdfImageConversionFormat.Png);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | `[Content](../../com.groupdocs.watermark.contents/content)` 객체의 요청된 유형. |
|

**Returns:**
T - 로드된 문서에 대한 `[Content](../../com.groupdocs.watermark.contents/content)` 객체.

