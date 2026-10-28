---
title: "WordProcessingContent"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Κλάση που αντιπροσωπεύει έγγραφο Word (doc, docx κ.λπ.) όπου πρέπει να τοποθετηθεί το υδατογράφημα."
type: docs
weight: 129
url: /el/java/com.groupdocs.watermark.contents/wordprocessingcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class WordProcessingContent extends Content implements IEncryptable
```

Κλάση που αντιπροσωπεύει έγγραφο Word (doc, docx κλπ) όπου πρέπει να τοποθετηθεί το υδατογράφημα.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)
* [Existing objects in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+word+processing+document)
* [Locking watermark in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Locking+watermark+in+word+processing+document)
* [Protecting word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Protecting+word+processing+documents)
* [Watermarks in word processing document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+word+processing+document)

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε και να αποθηκεύσετε έγγραφο Word οποιουδήποτε υποστηριζόμενου τύπου.
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


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingContent(StreamContainer stream, IStrategyManager strategyManager, FileFormatInfo fileFormatInfo, WordProcessingLoadOptions wordProcessingLoadOptions, WatermarkerSettings watermarkerSettings)](#WordProcessingContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.aspose.words.FileFormatInfo-com.groupdocs.watermark.options.WordProcessingLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSections()](#getSections--) | Αποκτά τη συλλογή όλων των ενοτήτων αυτού του `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`. |
|
| [setSections(WordProcessingSectionCollection value)](#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-) |  |
|  | [getPageCount()](#getPageCount--) | Αποκτά τον αριθμό των σελίδων στο έγγραφο. |
|
| [getAsposeWordsDocument()](#getAsposeWordsDocument--) |  |
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Κρυπτογραφεί το έγγραφο. |
|
|  | [decrypt()](#decrypt--) | Αποκρυπτογραφεί το έγγραφο. |
|
| [addWatermark(Watermark watermark, int pageNumber)](#addWatermark-com.groupdocs.watermark.Watermark-int-) |  |
| [addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-) |  |
|  | [protect(int protectionType, String password)](#protect-int-java.lang.String-) | Προστατεύει το έγγραφο από αλλαγές και ορίζει κωδικό προστασίας. |
|
|  | [unprotect()](#unprotect--) | Αφαιρεί την προστασία από το έγγραφο ανεξαρτήτως του κωδικού. |
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
| Παράμετρος | Τύπος | Περιγραφή |
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


Αποκτά τη συλλογή όλων των ενοτήτων αυτού του `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`.


**Returns:**
[WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) - The collection of all sections of this `[WordProcessingContent](../../com.groupdocs.watermark.contents/wordprocessingcontent)`.

### setSections(WordProcessingSectionCollection value) {#setSections-com.groupdocs.watermark.contents.WordProcessingSectionCollection-}
```
public final void setSections(WordProcessingSectionCollection value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WordProcessingSectionCollection](../../com.groupdocs.watermark.contents/wordprocessingsectioncollection) |  |

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Αποκτά τον αριθμό των σελίδων στο έγγραφο.


**Returns:**
int - Ο αριθμός των σελίδων στο έγγραφο.

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


Κρυπτογραφεί το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κωδικός πρόσβασης | java.lang.String | Ο κωδικός πρόσβασης που θα απαιτηθεί για το άνοιγμα του εγγράφου. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Αποκρυπτογραφεί το έγγραφο.


### addWatermark(Watermark watermark, int pageNumber) {#addWatermark-com.groupdocs.watermark.Watermark-int-}
```
public final void addWatermark(Watermark watermark, int pageNumber)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| pageNumber | int |  |

### addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-com.groupdocs.watermark.options.WordProcessingShapeSettings-}
```
public final void addWatermark(Watermark watermark, IWordProcessingWatermarkEffects effects, WordProcessingShapeSettings shapeSettings)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| effects | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |
| shapeSettings | [WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings) |  |

### protect(int protectionType, String password) {#protect-int-java.lang.String-}
```
public final void protect(int protectionType, String password)
```


Προστατεύει το έγγραφο από αλλαγές και ορίζει κωδικό προστασίας.

Για να είναι το περιεχόμενο του εγγράφου επεξεργάσιμο, χρησιμοποιήστε τη σχετική μέθοδο προσθήκης υδατογραφήματος με
`[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` ή
`[WordProcessingLockType.ReadOnlyWithEditableContent](../../com.groupdocs.watermark.options/wordprocessinglocktype#ReadOnlyWithEditableContent)` παράμετρος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | protectionType | int | Ο τύπος προστασίας για το έγγραφο. |
|
|  | κωδικός πρόσβασης | java.lang.String | Ο κωδικός πρόσβασης για την προστασία του εγγράφου. |
|

### unprotect() {#unprotect--}
```
public final void unprotect()
```


Αφαιρεί την προστασία από το έγγραφο ανεξαρτήτως του κωδικού.


### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

