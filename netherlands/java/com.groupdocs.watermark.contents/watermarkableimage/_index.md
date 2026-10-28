---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een afbeelding binnen een document voor."
type: docs
weight: 127
url: /nl/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Stelt een afbeelding binnen een document voor.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

Het volgende voorbeeld laat zien hoe je een watermerk toevoegt aan alle afbeeldingen in een document van elk ondersteund type.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getHeight()](#getHeight--) | Haalt de hoogte op van deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte op van deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Voegt een watermerk toe aan deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
|
|  | [getBytes()](#getBytes--) | Haalt de afbeelding op als byte-array. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte op van deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.


**Returns:**
int - De hoogte van deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte op van deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.


**Returns:**
int - De breedte van deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in pixels.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Voegt een watermerk toe aan deze `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

Deze methode gaat ervan uit dat de offset en grootte van het watermerk in pixels worden gemeten (indien ze zijn toegewezen).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Het watermerk om toe te voegen aan de afbeelding. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Haalt de afbeelding op als byte-array.


**Returns:**
byte[] - De afbeeldingsgegevens.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

