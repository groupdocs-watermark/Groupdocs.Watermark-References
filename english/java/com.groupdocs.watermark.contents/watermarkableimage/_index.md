---
title: WatermarkableImage
second_title: GroupDocs.Watermark for Java API Reference
description: Represents an image inside a document.
type: docs
weight: 127
url: /java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Represents an image inside a document.

**Learn more:**

 *  [Adding watermark to images inside a document][]

The following example demonstrates how to add watermark to all images inside a document of any supported type.

> ```
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
> ```


[Adding watermark to images inside a document]: https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document
## Constructors

| Constructor | Description |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Gets the height of this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels. |
| [getWidth()](#getWidth--) | Gets the width of this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels. |
| [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Adds a watermark to this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
| [getBytes()](#getBytes--) | Gets the image as byte array. |
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.

**Returns:**
int - The height of this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.

**Returns:**
int - The width of this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.
### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Adds a watermark to this `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

This method assumes that watermark offset and size are measured in pixels (if they are assigned).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) | The watermark to add to the image. |

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Gets the image as byte array.

**Returns:**
byte[] - The image data.
### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

