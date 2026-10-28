---
title: "WordProcessingContent"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Classe che rappresenta documenti Word (doc, docx, ecc.) dove dovrebbe essere posizionato il watermark."
type: docs
weight: 129
url: /it/java/com.groupdocs.watermark.contents/wordprocessingcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class WordProcessingContent extends Content implements IEncryptable
```

Classe che rappresenta un documento Word (doc, docx ecc.) in cui dovrebbe essere posizionata la filigrana.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)
* [Existing objects in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+word+processing+document)
* [Locking watermark in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Locking+watermark+in+word+processing+document)
* [Protecting word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Protecting+word+processing+documents)
* [Watermarks in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+word+processing+document)

Il seguente esempio dimostra come caricare e salvare un documento Word di qualsiasi tipo supportato.
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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingContent(StreamContainer stream, IStrategyManager strategyManager, FileFormatInfo fileFormatInfo, WordProcessingLoadOptions wordProcessingLoadOptions, WatermarkerSettings watermarkerSettings)](#WordProcessingContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.aspose.words.FileFormatInfo-com.groupdocs.watermark.options.WordProcessingLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSections()](#getSections--) | Restituisce la collezione di tutte le sezioni di questo `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`. |
|
| [setSections(WordProcessingSectionCollection value)](#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-) |  |
|  | [getPageCount()](#getPageCount--) | Restituisce il numero di pagine nel documento. |
|
| [getAsposeWordsDocument()](#getAsposeWordsDocument--) |  |
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Cifra il documento. |
|
|  | [decrypt()](#decrypt--) | Decifra il documento. |
|
| [addWatermark(Watermark watermark, int pageNumber)](#addWatermark-com.groupdocs.watermark.Watermark-int-) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
|  | [protect(int protectionType, String password)](#protect-int-java.lang.String-) | Protegge il documento dalle modifiche e imposta una password di protezione. |
|
|  | [unprotect()](#unprotect--) | Rimuove la protezione dal documento indipendentemente dalla password. |
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
| Parametro | Tipo | Descrizione |
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


Restituisce la collezione di tutte le sezioni di questo `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`.


**Returns:**
[WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) - The collection of all sections of this `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`.

### setSections(WordProcessingSectionCollection value) {#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-}
```
public final void setSections(WordProcessingSectionCollection value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) |  |

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce il numero di pagine nel documento.


**Returns:**
int - Il numero di pagine nel documento.

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


Cifra il documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | password | java.lang.String | La password necessaria per aprire il documento. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Decifra il documento.


### addWatermark(Watermark watermark, int pageNumber) {#addWatermark-com.groupdocs.watermark.Watermark-int-}
```
public final void addWatermark(Watermark watermark, int pageNumber)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| pageNumber | int |  |

### addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-}
```
public final void addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

### protect(int protectionType, String password) {#protect-int-java.lang.String-}
```
public final void protect(int protectionType, String password)
```


Protegge il documento dalle modifiche e imposta una password di protezione.

Per rendere il contenuto del documento modificabile, utilizza il metodo appropriato per aggiungere il watermark con
`[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` o
`[WordProcessingLockType.ReadOnlyWithEditableContent](../../com.groupdocs.watermark.options/wordprocessinglocktype#ReadOnlyWithEditableContent)` parametro.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | protectionType | int | Il tipo di protezione per il documento. |
|
|  | password | java.lang.String | La password con cui proteggere il documento. |
|

### unprotect() {#unprotect--}
```
public final void unprotect()
```


Rimuove la protezione dal documento indipendentemente dalla password.


### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

