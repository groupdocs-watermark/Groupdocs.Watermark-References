---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en bild i ett dokument."
type: docs
weight: 127
url: /sv/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Representerar en bild i ett dokument.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

Följande exempel visar hur man lägger till en vattenstämpel på alla bilder i ett dokument av någon stödd typ.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` i pixlar. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` i pixlar. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Lägger till en vattenstämpel på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
|
|  | [getBytes()](#getBytes--) | Hämtar bilden som en byte-array. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` i pixlar.


**Returns:**
int - Höjden på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` i pixlar.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` i pixlar.


**Returns:**
int - Bredden på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` i pixlar.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Lägger till en vattenstämpel på detta `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

Denna metod förutsätter att vattenstämpelns förskjutning och storlek mäts i pixlar (om de har tilldelats).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Vattenstämpeln som ska läggas till i bilden. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Hämtar bilden som en byte-array.


**Returns:**
byte[] - Bilddata.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

