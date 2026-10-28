---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Wasserzeichens zu einem Mehrrahmenbild dar."
type: docs
weight: 26
url: /de/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen beim Hinzufügen eines Wasserzeichens zu einem Mehrrahmenbild dar.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Das folgende Beispiel demonstriert, wie man ein Wasserzeichen zu einem bestimmten Frame eines mehrrahmigen Bildes hinzufügt.
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
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
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Initialisiert eine neue Instanz der `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` Klasse. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Initialisiert eine neue Instanz der `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` Klasse mit einem angegebenen Index des Frames. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Liest den Index des Frames, dem das Wasserzeichen hinzugefügt wird. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Setzt den Index des Frames, dem das Wasserzeichen hinzugefügt wird. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Initialisiert eine neue Instanz der `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` Klasse.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Initialisiert eine neue Instanz der `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` Klasse mit einem angegebenen Index des Frames.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | frameIndex | int | Der Index des Frames, dem das Wasserzeichen hinzugefügt wird. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Liest den Index des Frames, dem das Wasserzeichen hinzugefügt wird.


**Returns:**
int - Der Index des Frames, dem das Wasserzeichen hinzugefügt wird.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Setzt den Index des Frames, dem das Wasserzeichen hinzugefügt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index des Frames, dem das Wasserzeichen hinzugefügt wird. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

