---
title: "PresentationContent"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक PowerPoint दस्तावेज़ का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।"
type: docs
weight: 81
url: /hi/java/com.groupdocs.watermark.contents/presentationcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PresentationContent extends Content implements IEncryptable
```

एक PowerPoint दस्तावेज़ का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](../https://docs.groupdocs.com/display/watermarkjava/Working+with+slide+backgrounds)

निम्न उदाहरण दर्शाता है कि किसी भी समर्थित प्रकार के PowerPoint दस्तावेज़ को कैसे लोड और सहेजा जाए।
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


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PresentationContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PresentationLoadOptions presentationLoadOptions, IPresentationInfo presentationInfo, WatermarkerSettings watermarkerSettings)](#PresentationContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PresentationLoadOptions-com.aspose.slides.IPresentationInfo-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSlideWidth()](#getSlideWidth--) | स्लाइड की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getSlideHeight()](#getSlideHeight--) | स्लाइड की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getNotesSlideWidth()](#getNotesSlideWidth--) | नोट्स स्लाइड की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getNotesSlideHeight()](#getNotesSlideHeight--) | नोट्स स्लाइड की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [getSlides()](#getSlides--) | इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी स्लाइड्स का संग्रह प्राप्त करता है। |
|
|  | [getMasterSlides()](#getMasterSlides--) | इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी मास्टर स्लाइड्स का संग्रह प्राप्त करता है। |
|
|  | [getLayoutSlides()](#getLayoutSlides--) | इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी लेआउट स्लाइड्स का संग्रह प्राप्त करता है। |
|
|  | [getMasterNotesSlide()](#getMasterNotesSlide--) | इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी नोट्स स्लाइड्स के लिए मास्टर स्लाइड प्राप्त करता है। |
|
|  | [getMasterHandoutSlide()](#getMasterHandoutSlide--) | इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की मास्टर हैंडआउट स्लाइड प्राप्त करता है। |
|
|  | [getAsposeSlidesPresentation()](#getAsposeSlidesPresentation--) | <br /> |

|
|  | [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | दस्तावेज़ को एन्क्रिप्ट करता है। |
|
|  | [decrypt()](#decrypt--) | दस्तावेज़ को डिक्रिप्ट करता है। |
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
| पैरामीटर | प्रकार | विवरण |
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


स्लाइड की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - स्लाइड की चौड़ाई पॉइंट्स में।

### getSlideHeight() {#getSlideHeight--}
```
public final double getSlideHeight()
```


स्लाइड की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - स्लाइड की ऊँचाई पॉइंट्स में।

### getNotesSlideWidth() {#getNotesSlideWidth--}
```
public final double getNotesSlideWidth()
```


नोट्स स्लाइड की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - नोट्स स्लाइड की चौड़ाई पॉइंट्स में।

### getNotesSlideHeight() {#getNotesSlideHeight--}
```
public final double getNotesSlideHeight()
```


नोट्स स्लाइड की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - नोट्स स्लाइड की ऊँचाई पॉइंट्स में।

### getSlides() {#getSlides--}
```
public final PresentationSlideCollection getSlides()
```


इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी स्लाइड्स का संग्रह प्राप्त करता है।


**Returns:**
[PresentationSlideCollection](../../com.groupdocs.watermark.contents/presentationslidecollection) - The collection of all slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterSlides() {#getMasterSlides--}
```
public final PresentationMasterSlideCollection getMasterSlides()
```


इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी मास्टर स्लाइड्स का संग्रह प्राप्त करता है।


**Returns:**
[PresentationMasterSlideCollection](../../com.groupdocs.watermark.contents/presentationmasterslidecollection) - The collection of all master slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getLayoutSlides() {#getLayoutSlides--}
```
public final PresentationLayoutSlideCollection getLayoutSlides()
```


इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी लेआउट स्लाइड्स का संग्रह प्राप्त करता है।


**Returns:**
[PresentationLayoutSlideCollection](../../com.groupdocs.watermark.contents/presentationlayoutslidecollection) - The collection of all layout slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public final PresentationMasterNotesSlide getMasterNotesSlide()
```


इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की सभी नोट्स स्लाइड्स के लिए मास्टर स्लाइड प्राप्त करता है।


**Returns:**
[PresentationMasterNotesSlide](../../com.groupdocs.watermark.contents/presentationmasternotesslide) - The master slide for all notes slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public final PresentationMasterHandoutSlide getMasterHandoutSlide()
```


इस `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` की मास्टर हैंडआउट स्लाइड प्राप्त करता है।


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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

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


### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पासवर्ड | java.lang.String |  |

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

