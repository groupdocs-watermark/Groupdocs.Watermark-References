---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image GIF."
type: docs
weight: 21
url: /fr/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane à une image GIF.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

L’exemple suivant montre comment ajouter un filigrane à une image GIF particulière.
>
> ````
> ```
>
>    GifImageLoadOptions loadOptions = new GifImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | Initialise une nouvelle instance de la classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | Initialise une nouvelle instance de la classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` avec un indice spécifié d'une trame. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


Initialise une nouvelle instance de la classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


Initialise une nouvelle instance de la classe `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` avec un indice spécifié d'une trame.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | frameIndex | int | L'indice du cadre auquel ajouter le filigrane. |
|

