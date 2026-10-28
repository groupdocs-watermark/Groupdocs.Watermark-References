---
title: "WordProcessingContent"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वर्ड दस्तावेज़ (doc, docx आदि) को दर्शाने वाली क्लास जहाँ वॉटरमार्क रखा जाना चाहिए।"
type: docs
weight: 129
url: /hi/java/com.groupdocs.watermark.contents/wordprocessingcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class WordProcessingContent extends Content implements IEncryptable
```

वॉटरमार्क रखने वाले Word दस्तावेज़ (doc, docx आदि) को दर्शाने वाली क्लास।

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)
* [Existing objects in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+word+processing+document)
* [Locking watermark in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Locking+watermark+in+word+processing+document)
* [Protecting word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Protecting+word+processing+documents)
* [Watermarks in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+word+processing+document)

निम्न उदाहरण दर्शाता है कि किसी भी समर्थित प्रकार के वर्ड दस्तावेज़ को कैसे लोड और सहेजा जाए।
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


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [WordProcessingContent(StreamContainer stream, IStrategyManager strategyManager, FileFormatInfo fileFormatInfo, WordProcessingLoadOptions wordProcessingLoadOptions, WatermarkerSettings watermarkerSettings)](#WordProcessingContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.aspose.words.FileFormatInfo-com.groupdocs.watermark.options.WordProcessingLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSections()](#getSections--) | इस `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)` के सभी अनुभागों का संग्रह प्राप्त करता है। |
|
| [setSections(WordProcessingSectionCollection value)](#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-) |  |
|  | [getPageCount()](#getPageCount--) | दस्तावेज़ में पृष्ठों की संख्या प्राप्त करता है। |
|
| [getAsposeWordsDocument()](#getAsposeWordsDocument--) |  |
|  | [encrypt(String password)](#encrypt-java.lang.String-) | दस्तावेज़ को एन्क्रिप्ट करता है। |
|
|  | [decrypt()](#decrypt--) | दस्तावेज़ को डिक्रिप्ट करता है। |
|
| [addWatermark(Watermark watermark, int pageNumber)](#addWatermark-com.groupdocs.watermark.Watermark-int-) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
|  | [protect(int protectionType, String password)](#protect-int-java.lang.String-) | दस्तावेज़ को परिवर्तन से सुरक्षित करता है और एक सुरक्षा पासवर्ड सेट करता है। |
|
|  | [unprotect()](#unprotect--) | पासवर्ड की परवाह किए बिना दस्तावेज़ से सुरक्षा हटाता है। |
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
| पैरामीटर | प्रकार | विवरण |
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


इस `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)` के सभी अनुभागों का संग्रह प्राप्त करता है।


**Returns:**
[WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) - The collection of all sections of this `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`.

### setSections(WordProcessingSectionCollection value) {#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-}
```
public final void setSections(WordProcessingSectionCollection value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) |  |

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


दस्तावेज़ में पृष्ठों की संख्या प्राप्त करता है।


**Returns:**
int - दस्तावेज़ में पृष्ठों की संख्या।

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


दस्तावेज़ को एन्क्रिप्ट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पासवर्ड | java.lang.String | दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड। |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


दस्तावेज़ को डिक्रिप्ट करता है।


### addWatermark(Watermark watermark, int pageNumber) {#addWatermark-com.groupdocs.watermark.Watermark-int-}
```
public final void addWatermark(Watermark watermark, int pageNumber)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| pageNumber | int |  |

### addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-}
```
public final void addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

### protect(int protectionType, String password) {#protect-int-java.lang.String-}
```
public final void protect(int protectionType, String password)
```


दस्तावेज़ को परिवर्तन से सुरक्षित करता है और एक सुरक्षा पासवर्ड सेट करता है।

दस्तावेज़ की सामग्री को संपादन योग्य बनाने के लिए उचित वॉटरमार्क जोड़ने की विधि का उपयोग करें जिसमें
`[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` या
`[WordProcessingLockType.ReadOnlyWithEditableContent](../../com.groupdocs.watermark.options/wordprocessinglocktype#ReadOnlyWithEditableContent)` पैरामीटर।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | protectionType | int | दस्तावेज़ के लिए सुरक्षा प्रकार। |
|
|  | पासवर्ड | java.lang.String | दस्तावेज़ को सुरक्षित करने के लिए पासवर्ड। |
|

### unprotect() {#unprotect--}
```
public final void unprotect()
```


पासवर्ड की परवाह किए बिना दस्तावेज़ से सुरक्षा हटाता है।


### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

