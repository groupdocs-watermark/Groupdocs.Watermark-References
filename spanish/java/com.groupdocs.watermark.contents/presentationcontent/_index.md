---
title: "PresentationContent"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa un documento PowerPoint donde se puede colocar una marca de agua."
type: docs
weight: 81
url: /es/java/com.groupdocs.watermark.contents/presentationcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PresentationContent extends Content implements IEncryptable
```

Representa un documento PowerPoint donde se puede colocar una marca de agua.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](../https://docs.groupdocs.com/display/watermarkjava/Working+with+slide+backgrounds)

El siguiente ejemplo muestra cómo cargar y guardar un documento PowerPoint de cualquier tipo compatible.
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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PresentationLoadOptions presentationLoadOptions, IPresentationInfo presentationInfo, WatermarkerSettings watermarkerSettings)](#PresentationContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PresentationLoadOptions-com.aspose.slides.IPresentationInfo-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSlideWidth()](#getSlideWidth--) | Obtiene el ancho de una diapositiva en puntos. |
|
|  | [getSlideHeight()](#getSlideHeight--) | Obtiene la altura de una diapositiva en puntos. |
|
|  | [getNotesSlideWidth()](#getNotesSlideWidth--) | Obtiene el ancho de una diapositiva de notas en puntos. |
|
|  | [getNotesSlideHeight()](#getNotesSlideHeight--) | Obtiene la altura de una diapositiva de notas en puntos. |
|
|  | [getSlides()](#getSlides--) | Obtiene la colección de todas las diapositivas de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getMasterSlides()](#getMasterSlides--) | Obtiene la colección de todas las diapositivas maestras de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getLayoutSlides()](#getLayoutSlides--) | Obtiene la colección de todas las diapositivas de diseño de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getMasterNotesSlide()](#getMasterNotesSlide--) | Obtiene la diapositiva maestra para todas las diapositivas de notas de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getMasterHandoutSlide()](#getMasterHandoutSlide--) | Obtiene la diapositiva maestra de folletos de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`. |
|
|  | [getAsposeSlidesPresentation()](#getAsposeSlidesPresentation--) | <br /> |

|
|  | [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Encripta el documento. |
|
|  | [decrypt()](#decrypt--) | Desencripta el documento. |
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
| Parámetro | Tipo | Descripción |
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


Obtiene el ancho de una diapositiva en puntos.


**Returns:**
double - El ancho de una diapositiva en puntos.

### getSlideHeight() {#getSlideHeight--}
```
public final double getSlideHeight()
```


Obtiene la altura de una diapositiva en puntos.


**Returns:**
double - La altura de una diapositiva en puntos.

### getNotesSlideWidth() {#getNotesSlideWidth--}
```
public final double getNotesSlideWidth()
```


Obtiene el ancho de una diapositiva de notas en puntos.


**Returns:**
double - El ancho de una diapositiva de notas en puntos.

### getNotesSlideHeight() {#getNotesSlideHeight--}
```
public final double getNotesSlideHeight()
```


Obtiene la altura de una diapositiva de notas en puntos.


**Returns:**
double - La altura de una diapositiva de notas en puntos.

### getSlides() {#getSlides--}
```
public final PresentationSlideCollection getSlides()
```


Obtiene la colección de todas las diapositivas de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationSlideCollection](../../com.groupdocs.watermark.contents/presentationslidecollection) - The collection of all slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterSlides() {#getMasterSlides--}
```
public final PresentationMasterSlideCollection getMasterSlides()
```


Obtiene la colección de todas las diapositivas maestras de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationMasterSlideCollection](../../com.groupdocs.watermark.contents/presentationmasterslidecollection) - The collection of all master slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getLayoutSlides() {#getLayoutSlides--}
```
public final PresentationLayoutSlideCollection getLayoutSlides()
```


Obtiene la colección de todas las diapositivas de diseño de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationLayoutSlideCollection](../../com.groupdocs.watermark.contents/presentationlayoutslidecollection) - The collection of all layout slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public final PresentationMasterNotesSlide getMasterNotesSlide()
```


Obtiene la diapositiva maestra para todas las diapositivas de notas de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


**Returns:**
[PresentationMasterNotesSlide](../../com.groupdocs.watermark.contents/presentationmasternotesslide) - The master slide for all notes slides of this `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.

### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public final PresentationMasterHandoutSlide getMasterHandoutSlide()
```


Obtiene la diapositiva maestra de folletos de este `[PresentationContent](../../com.groupdocs.watermark.contents/presentationcontent)`.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


Encripta el documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contraseña | java.lang.String | La contraseña que se requerirá para abrir el documento. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Desencripta el documento.


### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

