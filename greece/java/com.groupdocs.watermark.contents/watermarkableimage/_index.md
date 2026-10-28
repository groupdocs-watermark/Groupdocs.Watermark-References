---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει μια εικόνα μέσα σε ένα έγγραφο."
type: docs
weight: 127
url: /el/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Αντιπροσωπεύει μια εικόνα μέσα σε ένα έγγραφο.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε υδατογράφημα σε όλες τις εικόνες μέσα σε ένα έγγραφο οποιουδήποτε υποστηριζόμενου τύπου.
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


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος αυτού του `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` σε εικονοστοιχεία. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` σε εικονοστοιχεία. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Προσθέτει υδατογράφημα σε αυτό το `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`. |
|
|  | [getBytes()](#getBytes--) | Λαμβάνει την εικόνα ως πίνακα byte. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος αυτού του `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` σε εικονοστοιχεία.


**Returns:**
int - Το ύψος αυτού του `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` σε εικονοστοιχεία.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος αυτού του `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` σε εικονοστοιχεία.


**Returns:**
int - Το πλάτος αυτού του `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` σε εικονοστοιχεία.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Προσθέτει υδατογράφημα σε αυτό το `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`.

Αυτή η μέθοδος υποθέτει ότι η μετατόπιση και το μέγεθος του υδατογραφήματος μετρώνται σε εικονοστοιχεία (αν έχουν οριστεί).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Το υδατογράφημα που θα προστεθεί στην εικόνα. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Λαμβάνει την εικόνα ως πίνακα byte.


**Returns:**
byte[] - Τα δεδομένα της εικόνας.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

