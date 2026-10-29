---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir belgenin içindeki görüntüyü temsil eder."
type: docs
weight: 127
url: /tr/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

Bir belgenin içindeki görüntüyü temsil eder.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

Aşağıdaki örnek, desteklenen herhangi bir türdeki belgenin içindeki tüm görüntülere filigran eklemenin nasıl yapılacağını gösterir.
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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getHeight()](#getHeight--) | Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesinin yüksekliğini piksel olarak alır. |
|
|  | [getWidth()](#getWidth--) | Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesinin genişliğini piksel olarak alır. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesine bir filigran ekler. |
|
|  | [getBytes()](#getBytes--) | Görüntüyü bayt dizisi olarak alır. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesinin yüksekliğini piksel olarak alır.


**Returns:**
int - Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesinin yüksekliği piksel olarak.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesinin genişliğini piksel olarak alır.


**Returns:**
int - Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesinin genişliği piksel olarak.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Bu `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` nesnesine bir filigran ekler.

Bu yöntem, filigran ofseti ve boyutunun piksel cinsinden ölçüldüğünü varsayar (atanmışsa).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Görüntüye eklenecek filigran. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


Görüntüyü bayt dizisi olarak alır.


**Returns:**
byte[] - Görüntü verisi.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

