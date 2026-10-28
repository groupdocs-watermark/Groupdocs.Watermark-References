---
title: "PdfContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 pdf 문서를 나타냅니다."
type: docs
weight: 60
url: /ko/java/com.groupdocs.watermark.contents/pdfcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PdfContent extends Content implements IEncryptable
```

워터마크를 배치할 수 있는 pdf 문서를 나타냅니다.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document)
* [Rasterize document or page](../https://docs.groupdocs.com/display/watermarkjava/Rasterize+document+or+page)
* [Watermarks in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+PDF+document)

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)](#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPages()](#getPages--) | 이 `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`의 모든 페이지 컬렉션을 가져옵니다. |
|
|  | [getAttachments()](#getAttachments--) | 이 `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`의 모든 첨부 파일 컬렉션을 가져옵니다. |
|
|  | [getPageMarginType()](#getPageMarginType--) | 워터마크 추가 중에 사용할 PDF 페이지 여백을 가져옵니다. |
|
|  | [setPageMarginType(int value)](#setPageMarginType-int-) | 워터마크 추가 중에 사용할 PDF 페이지 여백을 설정합니다. |
|
|  | [getAsposePdfDocument()](#getAsposePdfDocument--) | <br /> |

|
|  | [addArtifactWatermark(Watermark watermark)](#addArtifactWatermark-com.groupdocs.watermark.Watermark-) | <br /> |

|
|  | [addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)](#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | 사용자 비밀번호와 소유자 비밀번호와 동일한 비밀번호를 사용하여 문서를 암호화합니다. |
|
|  | [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | 콘텐츠를 암호화합니다. |
|
|  | [decrypt()](#decrypt--) | 콘텐츠를 복호화합니다. |
|
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | 모든 콘텐츠 페이지를 이미지로 변환합니다. |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | 지정된 스트림에 문서 데이터를 저장합니다. |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | 지정된 스트림에 문서 데이터를 저장합니다. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings) {#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| pdfLoadOptions | [PdfLoadOptions](../../com.groupdocs.watermark.options/pdfloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getPages() {#getPages--}
```
public final PdfPageCollection getPages()
```


이 `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`의 모든 페이지 컬렉션을 가져옵니다.


**Returns:**
[PdfPageCollection](../../com.groupdocs.watermark.contents/pdfpagecollection) - The collection of all pages of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getAttachments() {#getAttachments--}
```
public final PdfAttachmentCollection getAttachments()
```


이 `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`의 모든 첨부 파일 컬렉션을 가져옵니다.


**Returns:**
[PdfAttachmentCollection](../../com.groupdocs.watermark.contents/pdfattachmentcollection) - The collection of all attachments of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getPageMarginType() {#getPageMarginType--}
```
public final int getPageMarginType()
```


워터마크 추가 중에 사용할 PDF 페이지 여백을 가져옵니다.

이 속성은 `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`가 true일 때만 작동합니다.
true입니다. `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`가 false인 경우,
PDF CropBox가 워터마크 영역으로 사용될 때.

기본값은 `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`입니다.


**Returns:**
int
### setPageMarginType(int value) {#setPageMarginType-int-}
```
public final void setPageMarginType(int value)
```


워터마크 추가 중에 사용할 PDF 페이지 여백을 설정합니다.

이 속성은 `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`가 true일 때만 작동합니다.
true 로 설정됩니다. 만약 `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` 가 false이면,
PDF CropBox가 워터마크 영역으로 사용될 때.

기본값은 `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getAsposePdfDocument() {#getAsposePdfDocument--}
```
public final Document getAsposePdfDocument()
```


<br />



**Returns:**
com.aspose.pdf.Document
### addArtifactWatermark(Watermark watermark) {#addArtifactWatermark-com.groupdocs.watermark.Watermark-}
```
public final void addArtifactWatermark(Watermark watermark)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```


<br />



**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


사용자 비밀번호와 소유자 비밀번호와 동일한 비밀번호를 사용하여 문서를 암호화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 비밀번호 | java.lang.String | 사용자 및 소유자 비밀번호. |
|

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public final void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


콘텐츠를 암호화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | userPassword | java.lang.String | 사용자 비밀번호. |
|
|  | ownerPassword | java.lang.String | 소유자 비밀번호. |
|
|  | permissions | int | 콘텐츠 권한. |
|
|  | cryptoAlgorithm | int | 암호화 알고리즘. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


콘텐츠를 복호화합니다.


### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public final void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


모든 콘텐츠 페이지를 이미지로 변환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | horizontalResolution | int | 수평 이미지 해상도. |
|
|  | verticalResolution | int | 수직 이미지 해상도. |
|
|  | imageFormat | int | 이미지 형식. |
|

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


지정된 스트림에 문서 데이터를 저장합니다.

<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.OutputStream | 콘텐츠 데이터를 저장할 스트림. |
|

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


지정된 스트림에 문서 데이터를 저장합니다.

<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.OutputStream | 콘텐츠 데이터를 저장할 스트림. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | 콘텐츠 데이터를 저장할 때 사용해야 하는 옵션. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

