---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Bild innerhalb eines Dokuments dar."
type: docs
weight: 127
url: /de/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Stellt ein Bild innerhalb eines Dokuments dar.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu allen Bildern in einem Dokument eines beliebigen unterstützten Typs hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getHeight()](#getHeight--) | Ermittelt die Höhe dieses `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in Pixeln. |
|
|  | [getWidth()](#getWidth--) | Ermittelt die Breite dieses `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in Pixeln. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Fügt diesem `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ein Wasserzeichen hinzu. |
|
|  | [getBytes()](#getBytes--) | Ermittelt das Bild als Byte-Array. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ermittelt die Höhe dieses `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in Pixeln.


**Returns:**
int - Die Höhe dieses `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in Pixeln.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ermittelt die Breite dieses `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in Pixeln.


**Returns:**
int - Die Breite dieses `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` in Pixeln.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Fügt diesem `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ein Wasserzeichen hinzu.

Diese Methode geht davon aus, dass Wasserzeichen‑Versatz und -Größe in Pixeln gemessen werden (falls sie zugewiesen wurden).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Das Wasserzeichen, das dem Bild hinzugefügt werden soll. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Ermittelt das Bild als Byte-Array.


**Returns:**
byte[] - Die Bilddaten.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

