---
title: "WatermarkableImage"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un'immagine all'interno di un documento."
type: docs
weight: 127
url: /it/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Rappresenta un'immagine all'interno di un documento.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

Il seguente esempio dimostra come aggiungere una filigrana a tutte le immagini all'interno di un documento di qualsiasi tipo supportato.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>  
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>  
>    // Find all images in the content.
>    WatermarkableImageCollection images = watermarker.getImages();
>  
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.add(watermark);
>    }
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
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getHeight()](#getHeight--) | Restituisce l'altezza di questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixel. |
|
|  | [getWidth()](#getWidth--) | Restituisce la larghezza di questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixel. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Aggiunge una filigrana a questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
|
|  | [getBytes()](#getBytes--) | Restituisce l'immagine come array di byte. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza di questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixel.


**Returns:**
int - L'altezza di questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixel.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza di questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixel.


**Returns:**
int - La larghezza di questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixel.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Aggiunge una filigrana a questo `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

Questo metodo assume che l'offset e le dimensioni della filigrana siano misurati in pixel (se sono assegnati).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | La filigrana da aggiungere all'immagine. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Restituisce l'immagine come array di byte.


**Returns:**
byte[] - I dati dell'immagine.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

