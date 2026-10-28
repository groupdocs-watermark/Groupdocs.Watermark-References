---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen zu einem TIFF-Bild dar."
type: docs
weight: 63
url: /de/java/com.groupdocs.watermark.options/tiffimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class TiffImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen zu einem TIFF-Bild dar.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu einem bestimmten Frame eines TIFF-Bildes hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TiffImageWatermarkOptions()](#TiffImageWatermarkOptions--) | Initialisiert eine neue Instanz der `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` Klasse. |
|
|  | [TiffImageWatermarkOptions(int frameIndex)](#TiffImageWatermarkOptions-int-) | Initialisiert eine neue Instanz der `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` Klasse mit einem angegebenen Index des Frames. |
|
### TiffImageWatermarkOptions() {#TiffImageWatermarkOptions--}
```
public TiffImageWatermarkOptions()
```


Initialisiert eine neue Instanz der `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` Klasse.


### TiffImageWatermarkOptions(int frameIndex) {#TiffImageWatermarkOptions-int-}
```
public TiffImageWatermarkOptions(int frameIndex)
```


Initialisiert eine neue Instanz der `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` Klasse mit einem angegebenen Index des Frames.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | frameIndex | int | Der Index des Frames, dem das Wasserzeichen hinzugefügt wird. |
|

