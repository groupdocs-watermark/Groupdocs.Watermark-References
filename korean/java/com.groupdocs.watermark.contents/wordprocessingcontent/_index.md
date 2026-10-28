---
title: "WordProcessingContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치해야 하는 Word 문서(doc, docx 등)를 나타내는 클래스."
type: docs
weight: 129
url: /ko/java/com.groupdocs.watermark.contents/wordprocessingcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class WordProcessingContent extends Content implements IEncryptable
```

워터마크를 배치해야 하는 Word 문서(doc, docx 등)를 나타내는 클래스입니다.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)
* [Existing objects in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+word+processing+document)
* [Locking watermark in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Locking+watermark+in+word+processing+document)
* [Protecting word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Protecting+word+processing+documents)
* [Watermarks in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+word+processing+document)

다음 예제는 지원되는 모든 유형의 Word 문서를 로드하고 저장하는 방법을 보여줍니다.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.doc", loadOptions);
>    
>    // Use add method to add watermark to a particular or all sections.
>    
>    // Save changes.
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingContent(StreamContainer stream, IStrategyManager strategyManager, FileFormatInfo fileFormatInfo, WordProcessingLoadOptions wordProcessingLoadOptions, WatermarkerSettings watermarkerSettings)](#WordProcessingContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.aspose.words.FileFormatInfo-com.groupdocs.watermark.options.WordProcessingLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSections()](#getSections--) | 이 `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`의 모든 섹션 컬렉션을 가져옵니다. |
|
| [setSections(WordProcessingSectionCollection value)](#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-) |  |
|  | [getPageCount()](#getPageCount--) | 문서의 페이지 수를 가져옵니다. |
|
| [getAsposeWordsDocument()](#getAsposeWordsDocument--) |  |
|  | [encrypt(String password)](#encrypt-java.lang.String-) | 문서를 암호화합니다. |
|
|  | [decrypt()](#decrypt--) | 문서를 복호화합니다. |
|
| [addWatermark(Watermark watermark, int pageNumber)](#addWatermark-com.groupdocs.watermark.Watermark-int-) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
|  | [protect(int protectionType, String password)](#protect-int-java.lang.String-) | 문서를 변경으로부터 보호하고 보호 비밀번호를 설정합니다. |
|
|  | [unprotect()](#unprotect--) | 비밀번호와 관계없이 문서의 보호를 해제합니다. |
|
| [performSave(String filePath)](#performSave-java.lang.String-) |  |
| [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) |  |
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) |  |
| [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) |  |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) |  |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) |  |
| [getDocumentInfo()](#getDocumentInfo--) |  |
| [getFileType()](#getFileType--) |  |
| [addWatermark(Watermark watermark)](#addWatermark-com.groupdocs.watermark.Watermark-) |  |
### WordProcessingContent(StreamContainer stream, IStrategyManager strategyManager, FileFormatInfo fileFormatInfo, WordProcessingLoadOptions wordProcessingLoadOptions, WatermarkerSettings watermarkerSettings) {#WordProcessingContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.aspose.words.FileFormatInfo-com.groupdocs.watermark.options.WordProcessingLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public WordProcessingContent(StreamContainer stream, IStrategyManager strategyManager, FileFormatInfo fileFormatInfo, WordProcessingLoadOptions wordProcessingLoadOptions, WatermarkerSettings watermarkerSettings)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | [IStrategyManager](../../com.groupdocs.watermark.internal/istrategymanager) |  |
| fileFormatInfo | com.aspose.words.FileFormatInfo |  |
| wordProcessingLoadOptions | [WordProcessingLoadOptions](../../com.groupdocs.watermark.options/wordprocessingloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSections() {#getSections--}
```
public final WordProcessingSectionCollection getSections()
```


이 `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`의 모든 섹션 컬렉션을 가져옵니다.


**Returns:**
[WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) - The collection of all sections of this `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`.

### setSections(WordProcessingSectionCollection value) {#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-}
```
public final void setSections(WordProcessingSectionCollection value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) |  |

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


문서의 페이지 수를 가져옵니다.


**Returns:**
int - 문서의 페이지 수.

### getAsposeWordsDocument() {#getAsposeWordsDocument--}
```
public final Document getAsposeWordsDocument()
```




**Returns:**
com.aspose.words.Document
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


### addWatermark(Watermark watermark, int pageNumber) {#addWatermark-com.groupdocs.watermark.Watermark-int-}
```
public final void addWatermark(Watermark watermark, int pageNumber)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| pageNumber | int |  |

### addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-}
```
public final void addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

### protect(int protectionType, String password) {#protect-int-java.lang.String-}
```
public final void protect(int protectionType, String password)
```


문서를 변경으로부터 보호하고 보호 비밀번호를 설정합니다.

문서 내용을 편집 가능하게 하려면 적절한 워터마크 추가 방법을 사용하십시오
`[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` 또는
`[WordProcessingLockType.ReadOnlyWithEditableContent](../../com.groupdocs.watermark.options/wordprocessinglocktype#ReadOnlyWithEditableContent)` 매개변수.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | protectionType | int | 문서에 대한 보호 유형입니다. |
|
|  | 비밀번호 | java.lang.String | 문서를 보호하는 데 사용할 비밀번호입니다. |
|

### unprotect() {#unprotect--}
```
public final void unprotect()
```


비밀번호와 관계없이 문서의 보호를 해제합니다.


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
### addWatermark(Watermark watermark) {#addWatermark-com.groupdocs.watermark.Watermark-}
```
public void addWatermark(Watermark watermark)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

