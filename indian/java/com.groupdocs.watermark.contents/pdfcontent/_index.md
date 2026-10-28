---
title: "PdfContent"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक PDF दस्तावेज़ का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।"
type: docs
weight: 60
url: /hi/java/com.groupdocs.watermark.contents/pdfcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PdfContent extends Content implements IEncryptable
```

एक PDF दस्तावेज़ का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document)
* [Rasterize document or page](../https://docs.groupdocs.com/display/watermarkjava/Rasterize+document+or+page)
* [Watermarks in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+PDF+document)

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)](#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPages()](#getPages--) | इस `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` की सभी पृष्ठों का संग्रह प्राप्त करता है। |
|
|  | [getAttachments()](#getAttachments--) | इस `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` के सभी अटैचमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getPageMarginType()](#getPageMarginType--) | वॉटरमार्क जोड़ते समय उपयोग किए जाने वाले PDF पृष्ठ मार्जिन प्राप्त करता है। |
|
|  | [setPageMarginType(int value)](#setPageMarginType-int-) | वॉटरमार्क जोड़ते समय उपयोग किए जाने वाले PDF पृष्ठ मार्जिन सेट करता है। |
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
|  | [encrypt(String password)](#encrypt-java.lang.String-) | दस्तावेज़ को उपयोगकर्ता पासवर्ड और मालिक पासवर्ड के समान पासवर्ड का उपयोग करके एन्क्रिप्ट करता है। |
|
|  | [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | सामग्री को एन्क्रिप्ट करता है। |
|
|  | [decrypt()](#decrypt--) | सामग्री को डिक्रिप्ट करता है। |
|
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | सभी सामग्री पृष्ठों को छवियों में परिवर्तित करता है। |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | दस्तावेज़ डेटा को निर्दिष्ट स्ट्रीम में सहेजता है। |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | दस्तावेज़ डेटा को निर्दिष्ट स्ट्रीम में सहेजता है। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| pdfLoadOptions | [PdfLoadOptions](../../com.groupdocs.watermark.options/pdfloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getPages() {#getPages--}
```
public final PdfPageCollection getPages()
```


इस `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` की सभी पृष्ठों का संग्रह प्राप्त करता है।


**Returns:**
[PdfPageCollection](../../com.groupdocs.watermark.contents/pdfpagecollection) - The collection of all pages of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getAttachments() {#getAttachments--}
```
public final PdfAttachmentCollection getAttachments()
```


इस `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` के सभी अटैचमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[PdfAttachmentCollection](../../com.groupdocs.watermark.contents/pdfattachmentcollection) - The collection of all attachments of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getPageMarginType() {#getPageMarginType--}
```
public final int getPageMarginType()
```


वॉटरमार्क जोड़ते समय उपयोग किए जाने वाले PDF पृष्ठ मार्जिन प्राप्त करता है।

यह प्रॉपर्टी केवल तब काम करती है जब `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
सही है। यदि `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` गलत है,
जब PDF CropBox को वॉटरमार्किंग क्षेत्र के रूप में उपयोग किया जाता है।

डिफ़ॉल्ट मान `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)` है।


**Returns:**
int
### setPageMarginType(int value) {#setPageMarginType-int-}
```
public final void setPageMarginType(int value)
```


वॉटरमार्क जोड़ते समय उपयोग किए जाने वाले PDF पृष्ठ मार्जिन सेट करता है।

यह प्रॉपर्टी केवल तब काम करती है जब `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
सही पर सेट है। यदि `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` गलत है,
जब PDF CropBox को वॉटरमार्किंग क्षेत्र के रूप में उपयोग किया जाता है।

डिफ़ॉल्ट मान `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)` है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


दस्तावेज़ को उपयोगकर्ता पासवर्ड और मालिक पासवर्ड के समान पासवर्ड का उपयोग करके एन्क्रिप्ट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पासवर्ड | java.lang.String | उपयोगकर्ता और मालिक पासवर्ड। |
|

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public final void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


सामग्री को एन्क्रिप्ट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | userPassword | java.lang.String | उपयोगकर्ता पासवर्ड। |
|
|  | ownerPassword | java.lang.String | मालिक पासवर्ड। |
|
|  | अनुमतियाँ | int | सामग्री अनुमतियाँ। |
|
|  | cryptoAlgorithm | int | क्रिप्टोग्राफिक एल्गोरिदम। |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


सामग्री को डिक्रिप्ट करता है।


### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public final void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


सभी सामग्री पृष्ठों को छवियों में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | horizontalResolution | int | क्षैतिज छवि रिज़ॉल्यूशन। |
|
|  | verticalResolution | int | ऊर्ध्वाधर छवि रिज़ॉल्यूशन। |
|
|  | imageFormat | int | छवि प्रारूप। |
|

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


दस्तावेज़ डेटा को निर्दिष्ट स्ट्रीम में सहेजता है।

<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.OutputStream | सामग्री डेटा को सहेजने के लिए स्ट्रीम। |
|

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


दस्तावेज़ डेटा को निर्दिष्ट स्ट्रीम में सहेजता है।

<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.OutputStream | सामग्री डेटा को सहेजने के लिए स्ट्रीम। |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | सामग्री डेटा को सहेजते समय उपयोग किए जाने वाले विकल्प। |
|

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

