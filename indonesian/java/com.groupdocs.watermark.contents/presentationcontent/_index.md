---
title: "PresentationContent"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili dokumen PowerPoint di mana watermark dapat ditempatkan."
type: docs
weight: 81
url: /id/java/com.groupdocs.watermark.contents/presentationcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PresentationContent extends Content implements IEncryptable
```

Mewakili dokumen PowerPoint di mana watermark dapat ditempatkan.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](../https://docs.groupdocs.com/display/watermarkjava/Working+with+slide+backgrounds)

Contoh berikut menunjukkan cara memuat dan menyimpan dokumen PowerPoint dari tipe apa pun yang didukung.
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


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PresentationContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PresentationLoadOptions presentationLoadOptions, IPresentationInfo presentationInfo, WatermarkerSettings watermarkerSettings)](#PresentationContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PresentationLoadOptions-com.aspose.slides.IPresentationInfo-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSlideWidth()](#getSlideWidth--) | Mendapatkan lebar slide dalam poin. |
|
|  | [getSlideHeight()](#getSlideHeight--) | Mendapatkan tinggi slide dalam poin. |
|
|  | [getNotesSlideWidth()](#getNotesSlideWidth--) | Mendapatkan lebar slide catatan dalam poin. |
|
|  | [getNotesSlideHeight()](#getNotesSlideHeight--) | Mendapatkan tinggi slide catatan dalam poin. |
|
|  | [getSlides()](#getSlides--) | Mendapatkan koleksi semua slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini. |
|
|  | [getMasterSlides()](#getMasterSlides--) | Mendapatkan koleksi semua master slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini. |
|
|  | [getLayoutSlides()](#getLayoutSlides--) | Mendapatkan koleksi semua layout slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini. |
|
|  | [getMasterNotesSlide()](#getMasterNotesSlide--) | Mendapatkan master slide untuk semua slide catatan dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini. |
|
|  | [getMasterHandoutSlide()](#getMasterHandoutSlide--) | Mendapatkan master handout slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini. |
|
|  | [getAsposeSlidesPresentation()](#getAsposeSlidesPresentation--) | <br /> |

|
|  | [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Mengenkripsi dokumen. |
|
|  | [decrypt()](#decrypt--) | Mendekripsi dokumen. |
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
| Parameter | Tipe | Deskripsi |
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


Mendapatkan lebar slide dalam poin.


**Returns:**
double - Lebar slide dalam poin.

### getSlideHeight() {#getSlideHeight--}
```
public final double getSlideHeight()
```


Mendapatkan tinggi slide dalam poin.


**Returns:**
double - Tinggi slide dalam poin.

### getNotesSlideWidth() {#getNotesSlideWidth--}
```
public final double getNotesSlideWidth()
```


Mendapatkan lebar slide catatan dalam poin.


**Returns:**
double - Lebar slide catatan dalam poin.

### getNotesSlideHeight() {#getNotesSlideHeight--}
```
public final double getNotesSlideHeight()
```


Mendapatkan tinggi slide catatan dalam poin.


**Returns:**
double - Tinggi slide catatan dalam poin.

### getSlides() {#getSlides--}
```
public final PresentationSlideCollection getSlides()
```


Mendapatkan koleksi semua slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini.


**Returns:**
[PresentationSlideCollection](../../com.groupdocs.watermark.contents/presentationslidecollection) - The collection of all slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterSlides() {#getMasterSlides--}
```
public final PresentationMasterSlideCollection getMasterSlides()
```


Mendapatkan koleksi semua master slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini.


**Returns:**
[PresentationMasterSlideCollection](../../com.groupdocs.watermark.contents/presentationmasterslidecollection) - The collection of all master slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getLayoutSlides() {#getLayoutSlides--}
```
public final PresentationLayoutSlideCollection getLayoutSlides()
```


Mendapatkan koleksi semua layout slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini.


**Returns:**
[PresentationLayoutSlideCollection](../../com.groupdocs.watermark.contents/presentationlayoutslidecollection) - The collection of all layout slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public final PresentationMasterNotesSlide getMasterNotesSlide()
```


Mendapatkan master slide untuk semua slide catatan dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini.


**Returns:**
[PresentationMasterNotesSlide](../../com.groupdocs.watermark.contents/presentationmasternotesslide) - The master slide for all notes slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public final PresentationMasterHandoutSlide getMasterHandoutSlide()
```


Mendapatkan master handout slide dari `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)` ini.


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


Mengenkripsi dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kata sandi | java.lang.String | Kata sandi yang diperlukan untuk membuka dokumen. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Mendekripsi dokumen.


### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kata sandi | java.lang.String |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

