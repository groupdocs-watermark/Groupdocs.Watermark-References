---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Wasserzeichens zu einem GIF‑Bild dar."
type: docs
weight: 21
url: /de/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Wasserzeichens zu einem GIF‑Bild dar.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu einem bestimmten Frame eines GIF‑Bildes hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | Initialisiert eine neue Instanz der `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` Klasse. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | Initialisiert eine neue Instanz der `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` Klasse mit einem angegebenen Index eines Frames. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


Initialisiert eine neue Instanz der `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` Klasse.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


Initialisiert eine neue Instanz der `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` Klasse mit einem angegebenen Index eines Frames.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | frameIndex | int | Der Index des Frames, dem das Wasserzeichen hinzugefügt wird. |
|

