---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een watermerk aan een multi-frame-afbeelding."
type: docs
weight: 26
url: /nl/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Stelt opties voor het toevoegen van een watermerk voor bij het toevoegen van een watermerk aan een multi-frame-afbeelding.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Het volgende voorbeeld toont hoe u een watermerk toevoegt aan een specifiek frame van een multi‑frame‑afbeelding.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Initialiseert een nieuwe instantie van de `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` klasse. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Initialiseert een nieuwe instantie van de `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` klasse met een opgegeven index van het frame. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Haalt de index van het frame op waaraan het watermerk moet worden toegevoegd. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Stelt de index van het frame in waaraan het watermerk moet worden toegevoegd. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Initialiseert een nieuwe instantie van de `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` klasse.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Initialiseert een nieuwe instantie van de `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` klasse met een opgegeven index van het frame.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | frameIndex | int | De index van het frame waaraan het watermerk moet worden toegevoegd. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Haalt de index van het frame op waaraan het watermerk moet worden toegevoegd.


**Returns:**
int - De index van het frame waaraan het watermerk moet worden toegevoegd.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Stelt de index van het frame in waaraan het watermerk moet worden toegevoegd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De index van het frame waaraan het watermerk moet worden toegevoegd. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

