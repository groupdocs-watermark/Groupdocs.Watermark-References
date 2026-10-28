---
title: "WordProcessingContent"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示应放置水印的 Word 文档（doc、docx 等）的类。"
type: docs
weight: 129
url: /zh/java/com.groupdocs.watermark.contents/wordprocessingcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class WordProcessingContent extends Content implements IEncryptable
```

表示应放置水印的 Word 文档（doc、docx 等）的类。

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)
* [Existing objects in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+word+processing+document)
* [Locking watermark in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Locking+watermark+in+word+processing+document)
* [Protecting word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Protecting+word+processing+documents)
* [Watermarks in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+word+processing+document)

以下示例演示如何加载和保存任何受支持类型的 Word 文档。
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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordProcessingContent(StreamContainer stream, IStrategyManager strategyManager, FileFormatInfo fileFormatInfo, WordProcessingLoadOptions wordProcessingLoadOptions, WatermarkerSettings watermarkerSettings)](#WordProcessingContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.aspose.words.FileFormatInfo-com.groupdocs.watermark.options.WordProcessingLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSections()](#getSections--) | 获取此 `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)` 的所有节的集合。 |
|
| [setSections(WordProcessingSectionCollection value)](#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-) |  |
|  | [getPageCount()](#getPageCount--) | 获取文档中的页数。 |
|
| [getAsposeWordsDocument()](#getAsposeWordsDocument--) |  |
|  | [encrypt(String password)](#encrypt-java.lang.String-) | 加密文档。 |
|
|  | [decrypt()](#decrypt--) | 解密文档。 |
|
| [addWatermark(Watermark watermark, int pageNumber)](#addWatermark-com.groupdocs.watermark.Watermark-int-) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
|  | [protect(int protectionType, String password)](#protect-int-java.lang.String-) | 保护文档不被更改并设置保护密码。 |
|
|  | [unprotect()](#unprotect--) | 无论密码为何，都移除文档的保护。 |
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
| 参数 | 类型 | 描述 |
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


获取此 `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)` 的所有节的集合。


**Returns:**
[WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) - The collection of all sections of this `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`.

### setSections(WordProcessingSectionCollection value) {#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-}
```
public final void setSections(WordProcessingSectionCollection value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) |  |

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


获取文档中的页数。


**Returns:**
int - 文档中的页数。

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


加密文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 密码 | java.lang.String | 打开文档时所需的密码。 |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


解密文档。


### addWatermark(Watermark watermark, int pageNumber) {#addWatermark-com.groupdocs.watermark.Watermark-int-}
```
public final void addWatermark(Watermark watermark, int pageNumber)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| pageNumber | int |  |

### addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-}
```
public final void addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

### protect(int protectionType, String password) {#protect-int-java.lang.String-}
```
public final void protect(int protectionType, String password)
```


保护文档不被更改并设置保护密码。

要使文档内容可编辑，请使用适当的添加水印方法
`[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` 或
`[WordProcessingLockType.ReadOnlyWithEditableContent](../../com.groupdocs.watermark.options/wordprocessinglocktype#ReadOnlyWithEditableContent)` 参数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | protectionType | int | 文档的保护类型。 |
|
|  | 密码 | java.lang.String | 用于保护文档的密码。 |
|

### unprotect() {#unprotect--}
```
public final void unprotect()
```


无论密码为何，都移除文档的保护。


### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

