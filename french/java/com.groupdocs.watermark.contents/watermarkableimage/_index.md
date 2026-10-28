---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une image à l'intérieur d'un document."
type: docs
weight: 127
url: /fr/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Représente une image à l'intérieur d'un document.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

L'exemple suivant montre comment ajouter un filigrane à toutes les images d'un document de n'importe quel type pris en charge.
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


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en pixels. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en pixels. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Ajoute un filigrane à ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
|
|  | [getBytes()](#getBytes--) | Obtient l'image sous forme de tableau d'octets. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur de ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en pixels.


**Returns:**
int - La hauteur de ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en pixels.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur de ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en pixels.


**Returns:**
int - La largeur de ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` en pixels.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Ajoute un filigrane à ce `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

Cette méthode suppose que le décalage et la taille du filigrane sont mesurés en pixels (s'ils sont attribués).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Le filigrane à ajouter à l'image. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Obtient l'image sous forme de tableau d'octets.


**Returns:**
byte[] - Les données de l'image.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

