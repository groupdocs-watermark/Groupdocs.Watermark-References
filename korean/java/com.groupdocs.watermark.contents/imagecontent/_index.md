---
title: "ImageContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 이미지를 나타냅니다."
type: docs
weight: 38
url: /ko/java/com.groupdocs.watermark.contents/imagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public class ImageContent extends Content
```

워터마크를 배치할 수 있는 이미지를 나타냅니다.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)](#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getHeight()](#getHeight--) | 이 `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)`의 높이를 픽셀 단위로 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)`의 너비를 픽셀 단위로 가져옵니다. |
|
|  | [getAsposeImageContainer()](#getAsposeImageContainer--) | 기본을 가져옵니다 |
GroupDocs.Watermark.Internal.AsposeImageContainer
.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | 지정된 스트림에 콘텐츠를 저장합니다. |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | 지정된 스트림에 콘텐츠를 저장합니다. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings) {#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| fileType | [FileType](../../com.groupdocs.watermark.common/filetype) |  |
| imageLoadOptions | [ImageLoadOptions](../../com.groupdocs.watermark.options/imageloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


이 `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)`의 높이를 픽셀 단위로 가져옵니다.

멀티프레임 이미지의 활성 프레임 높이를 반환합니다.


**Returns:**
int - 이 `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)`의 높이(픽셀 단위).

### getWidth() {#getWidth--}
```
public final int getWidth()
```


이 `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)`의 너비를 픽셀 단위로 가져옵니다.

멀티프레임 이미지의 활성 프레임 너비를 반환합니다.


**Returns:**
int - 이 `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)`의 너비(픽셀 단위).

### getAsposeImageContainer() {#getAsposeImageContainer--}
```
public final AsposeImageContainer getAsposeImageContainer()
```


기본을 가져옵니다
GroupDocs.Watermark.Internal.AsposeImageContainer
.


**Returns:**
[AsposeImageContainer](../../com.groupdocs.watermark.contents/asposeimagecontainer)
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


지정된 스트림에 콘텐츠를 저장합니다.

<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


지정된 스트림에 콘텐츠를 저장합니다.

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

