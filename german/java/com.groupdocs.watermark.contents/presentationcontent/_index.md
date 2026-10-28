---
title: "PresentationContent"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein PowerPoint-Dokument dar, in dem ein Wasserzeichen platziert werden kann."
type: docs
weight: 81
url: /de/java/com.groupdocs.watermark.contents/presentationcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PresentationContent extends Content implements IEncryptable
```

Stellt ein PowerPoint-Dokument dar, in dem ein Wasserzeichen platziert werden kann.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](../https://docs.groupdocs.com/display/watermarkjava/Working+with+slide+backgrounds)

Das folgende Beispiel zeigt, wie man ein PowerPoint-Dokument eines beliebigen unterstützten Typs lädt und speichert.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PresentationLoadOptions presentationLoadOptions, IPresentationInfo presentationInfo, WatermarkerSettings watermarkerSettings)](#PresentationContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PresentationLoadOptions-com.aspose.slides.IPresentationInfo-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSlideWidth()](#getSlideWidth--) | Ermittelt die Breite einer Folie in Punkten. |
|
|  | [getSlideHeight()](#getSlideHeight--) | Ermittelt die Höhe einer Folie in Punkten. |
|
|  | [getNotesSlideWidth()](#getNotesSlideWidth--) | Ermittelt die Breite einer Notizfolie in Punkten. |
|
|  | [getNotesSlideHeight()](#getNotesSlideHeight--) | Ermittelt die Höhe einer Notizfolie in Punkten. |
|
|  | [getSlides()](#getSlides--) | Ermittelt die Sammlung aller Folien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getMasterSlides()](#getMasterSlides--) | Ermittelt die Sammlung aller Masterfolien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getLayoutSlides()](#getLayoutSlides--) | Ermittelt die Sammlung aller Layoutfolien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getMasterNotesSlide()](#getMasterNotesSlide--) | Ermittelt die Masterfolie für alle Notizfolien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getMasterHandoutSlide()](#getMasterHandoutSlide--) | Ermittelt die Master-Handoutfolie dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getAsposeSlidesPresentation()](#getAsposeSlidesPresentation--) | <br /> |

|
|  | [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Verschlüsselt das Dokument. |
|
|  | [decrypt()](#decrypt--) | Entschlüsselt das Dokument. |
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
| Parameter | Typ | Beschreibung |
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


Ermittelt die Breite einer Folie in Punkten.


**Returns:**
double - Die Breite einer Folie in Punkten.

### getSlideHeight() {#getSlideHeight--}
```
public final double getSlideHeight()
```


Ermittelt die Höhe einer Folie in Punkten.


**Returns:**
double - Die Höhe einer Folie in Punkten.

### getNotesSlideWidth() {#getNotesSlideWidth--}
```
public final double getNotesSlideWidth()
```


Ermittelt die Breite einer Notizfolie in Punkten.


**Returns:**
double - Die Breite einer Notizfolie in Punkten.

### getNotesSlideHeight() {#getNotesSlideHeight--}
```
public final double getNotesSlideHeight()
```


Ermittelt die Höhe einer Notizfolie in Punkten.


**Returns:**
double - Die Höhe einer Notizfolie in Punkten.

### getSlides() {#getSlides--}
```
public final PresentationSlideCollection getSlides()
```


Ermittelt die Sammlung aller Folien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationSlideCollection](../../com.groupdocs.watermark.contents/presentationslidecollection) - The collection of all slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterSlides() {#getMasterSlides--}
```
public final PresentationMasterSlideCollection getMasterSlides()
```


Ermittelt die Sammlung aller Masterfolien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationMasterSlideCollection](../../com.groupdocs.watermark.contents/presentationmasterslidecollection) - The collection of all master slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getLayoutSlides() {#getLayoutSlides--}
```
public final PresentationLayoutSlideCollection getLayoutSlides()
```


Ermittelt die Sammlung aller Layoutfolien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationLayoutSlideCollection](../../com.groupdocs.watermark.contents/presentationlayoutslidecollection) - The collection of all layout slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public final PresentationMasterNotesSlide getMasterNotesSlide()
```


Ermittelt die Masterfolie für alle Notizfolien dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationMasterNotesSlide](../../com.groupdocs.watermark.contents/presentationmasternotesslide) - The master slide for all notes slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public final PresentationMasterHandoutSlide getMasterHandoutSlide()
```


Ermittelt die Master-Handoutfolie dieses `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


Verschlüsselt das Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Passwort | java.lang.String | Das Passwort, das zum Öffnen des Dokuments erforderlich ist. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Entschlüsselt das Dokument.


### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

