---
title: "WatermarkableImage"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili gambar di dalam dokumen."
type: docs
weight: 127
url: /id/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Mewakili gambar di dalam dokumen.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

Contoh berikut menunjukkan cara menambahkan watermark ke semua gambar di dalam dokumen dengan tipe apa pun yang didukung.
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


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi dari `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ini dalam piksel. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar dari `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ini dalam piksel. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Menambahkan watermark ke `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ini. |
|
|  | [getBytes()](#getBytes--) | Mendapatkan gambar sebagai array byte. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi dari `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ini dalam piksel.


**Returns:**
int - Tinggi dari `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` dalam piksel.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar dari `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ini dalam piksel.


**Returns:**
int - Lebar dari `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` dalam piksel.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Menambahkan watermark ke `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` ini.

Metode ini mengasumsikan bahwa offset dan ukuran watermark diukur dalam piksel (jika telah ditetapkan).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Watermark yang akan ditambahkan ke gambar. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Mendapatkan gambar sebagai array byte.


**Returns:**
byte[] - Data gambar.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

