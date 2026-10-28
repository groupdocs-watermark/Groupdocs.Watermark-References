---
title: "PresentationContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 PowerPoint 문서를 나타냅니다."
type: docs
weight: 81
url: /ko/java/com.groupdocs.watermark.contents/presentationcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PresentationContent extends Content implements IEncryptable
```

워터마크를 배치할 수 있는 PowerPoint 문서를 나타냅니다.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](../https://docs.groupdocs.com/display/watermarkjava/Working+with+slide+backgrounds)

다음 예제는 지원되는 모든 유형의 PowerPoint 문서를 로드하고 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.ppt", loadOptions);
>  
>    // Use add method to add watermark to a particular slide or all slides.
>  
>    // Save changes.
>    watermarker.save("D:\\output.ppt");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PresentationLoadOptions presentationLoadOptions, IPresentationInfo presentationInfo, WatermarkerSettings watermarkerSettings)](#PresentationContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PresentationLoadOptions-com.aspose.slides.IPresentationInfo-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSlideWidth()](#getSlideWidth--) | 슬라이드의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getSlideHeight()](#getSlideHeight--) | 슬라이드의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getNotesSlideWidth()](#getNotesSlideWidth--) | 노트 슬라이드의 너비를 포인트 단위로 가져옵니다. |
|
|  | [getNotesSlideHeight()](#getNotesSlideHeight--) | 노트 슬라이드의 높이를 포인트 단위로 가져옵니다. |
|
|  | [getSlides()](#getSlides--) | 이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 슬라이드 컬렉션을 가져옵니다. |
|
|  | [getMasterSlides()](#getMasterSlides--) | 이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 마스터 슬라이드 컬렉션을 가져옵니다. |
|
|  | [getLayoutSlides()](#getLayoutSlides--) | 이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 레이아웃 슬라이드 컬렉션을 가져옵니다. |
|
|  | [getMasterNotesSlide()](#getMasterNotesSlide--) | 이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 노트 슬라이드에 대한 마스터 슬라이드를 가져옵니다. |
|
|  | [getMasterHandoutSlide()](#getMasterHandoutSlide--) | 이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 마스터 핸드아웃 슬라이드를 가져옵니다. |
|
|  | [getAsposeSlidesPresentation()](#getAsposeSlidesPresentation--) | <br /> |

|
|  | [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | 문서를 암호화합니다. |
|
|  | [decrypt()](#decrypt--) | 문서를 복호화합니다. |
|
|  | [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | <br /> |

|
|  | [removeWriteProtection()](#removeWriteProtection--) | <br /> |

|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | <br /> |

|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### PresentationContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PresentationLoadOptions presentationLoadOptions, IPresentationInfo presentationInfo, WatermarkerSettings watermarkerSettings) {#PresentationContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PresentationLoadOptions-com.aspose.slides.IPresentationInfo-com.groupdocs.watermark.WatermarkerSettings-}
```
public PresentationContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PresentationLoadOptions presentationLoadOptions, IPresentationInfo presentationInfo, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| presentationLoadOptions | [PresentationLoadOptions](../../com.groupdocs.watermark.options/presentationloadoptions) |  |
| presentationInfo | com.aspose.slides.IPresentationInfo |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSlideWidth() {#getSlideWidth--}
```
public final double getSlideWidth()
```


슬라이드의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 슬라이드의 너비(포인트).

### getSlideHeight() {#getSlideHeight--}
```
public final double getSlideHeight()
```


슬라이드의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 슬라이드의 높이(포인트).

### getNotesSlideWidth() {#getNotesSlideWidth--}
```
public final double getNotesSlideWidth()
```


노트 슬라이드의 너비를 포인트 단위로 가져옵니다.


**Returns:**
double - 노트 슬라이드의 너비(포인트).

### getNotesSlideHeight() {#getNotesSlideHeight--}
```
public final double getNotesSlideHeight()
```


노트 슬라이드의 높이를 포인트 단위로 가져옵니다.


**Returns:**
double - 노트 슬라이드의 높이(포인트).

### getSlides() {#getSlides--}
```
public final PresentationSlideCollection getSlides()
```


이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 슬라이드 컬렉션을 가져옵니다.


**Returns:**
[PresentationSlideCollection](../../com.groupdocs.watermark.contents/presentationslidecollection) - The collection of all slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterSlides() {#getMasterSlides--}
```
public final PresentationMasterSlideCollection getMasterSlides()
```


이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 마스터 슬라이드 컬렉션을 가져옵니다.


**Returns:**
[PresentationMasterSlideCollection](../../com.groupdocs.watermark.contents/presentationmasterslidecollection) - The collection of all master slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getLayoutSlides() {#getLayoutSlides--}
```
public final PresentationLayoutSlideCollection getLayoutSlides()
```


이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 레이아웃 슬라이드 컬렉션을 가져옵니다.


**Returns:**
[PresentationLayoutSlideCollection](../../com.groupdocs.watermark.contents/presentationlayoutslidecollection) - The collection of all layout slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public final PresentationMasterNotesSlide getMasterNotesSlide()
```


이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 모든 노트 슬라이드에 대한 마스터 슬라이드를 가져옵니다.


**Returns:**
[PresentationMasterNotesSlide](../../com.groupdocs.watermark.contents/presentationmasternotesslide) - The master slide for all notes slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public final PresentationMasterHandoutSlide getMasterHandoutSlide()
```


이 `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`의 마스터 핸드아웃 슬라이드를 가져옵니다.


**Returns:**
[PresentationMasterHandoutSlide](../../com.groupdocs.watermark.contents/presentationmasterhandoutslide) - The master handout slide of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getAsposeSlidesPresentation() {#getAsposeSlidesPresentation--}
```
public final Presentation getAsposeSlidesPresentation()
```


<br />



**Returns:**
com.aspose.slides.Presentation
### addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


문서를 암호화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 비밀번호 | java.lang.String | 문서를 열 때 필요한 비밀번호입니다. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


문서를 복호화합니다.


### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 비밀번호 | java.lang.String |  |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


<br />



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


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

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

