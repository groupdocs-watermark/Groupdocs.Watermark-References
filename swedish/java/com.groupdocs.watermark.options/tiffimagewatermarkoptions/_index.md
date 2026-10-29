---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel till en TIFF-bild."
type: docs
weight: 63
url: /sv/java/com.groupdocs.watermark.options/tiffimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class TiffImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Representerar alternativ för att lägga till vattenstämpel till en TIFF-bild.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Följande exempel visar hur man lägger till en vattenstämpel på en specifik ram i en TIFF-bild.
>
> ````
> ```
>
>    TiffImageImageLoadOptions loadOptions = new TiffImageImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.tiff", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.tiff");
>    watermarker.close();
>  
> ```
> ````


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TiffImageWatermarkOptions()](#TiffImageWatermarkOptions--) | Initierar en ny instans av klassen `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)`. |
|
|  | [TiffImageWatermarkOptions(int frameIndex)](#TiffImageWatermarkOptions-int-) | Initierar en ny instans av klassen `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` med ett specificerat index för ramen. |
|
### TiffImageWatermarkOptions() {#TiffImageWatermarkOptions--}
```
public TiffImageWatermarkOptions()
```


Initierar en ny instans av klassen `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)`.


### TiffImageWatermarkOptions(int frameIndex) {#TiffImageWatermarkOptions-int-}
```
public TiffImageWatermarkOptions(int frameIndex)
```


Initierar en ny instans av klassen `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` med ett specificerat index för ramen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | frameIndex | int | Indexet för ramen som vattenmärket ska läggas till på. |
|

