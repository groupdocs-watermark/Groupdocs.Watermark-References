---
title: "WatermarkableImage"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una imagen dentro de un documento."
type: docs
weight: 127
url: /es/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Representa una imagen dentro de un documento.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

El siguiente ejemplo muestra cómo agregar una marca de agua a todas las imágenes dentro de un documento de cualquier tipo compatible.
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


## Constructores

| Constructor | Descripción |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getHeight()](#getHeight--) | Obtiene la altura de este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en píxeles. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en píxeles. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Agrega una marca de agua a este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
|
|  | [getBytes()](#getBytes--) | Obtiene la imagen como matriz de bytes. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en píxeles.


**Returns:**
int - La altura de este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en píxeles.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en píxeles.


**Returns:**
int - El ancho de este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en píxeles.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Agrega una marca de agua a este `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

Este método asume que el desplazamiento y el tamaño de la marca de agua se miden en píxeles (si están asignados).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | La marca de agua a añadir a la imagen. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Obtiene la imagen como matriz de bytes.


**Returns:**
byte[] - Los datos de la imagen.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

