---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till en GIF-bild."
type: docs
weight: 21
url: /sv/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till en GIF-bild.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Följande exempel visar hur man lägger en vattenstämpel på en specifik ram i en GIF-bild.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | Initierar en ny instans av klassen `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | Initierar en ny instans av klassen `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` med ett specificerat index för en ram. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


Initierar en ny instans av klassen `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)`.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


Initierar en ny instans av klassen `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` med ett specificerat index för en ram.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | frameIndex | int | Indexet för ramen som vattenmärket ska läggas till på. |
|

