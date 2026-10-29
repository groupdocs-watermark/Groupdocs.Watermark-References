---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till en bild med flera ramar."
type: docs
weight: 26
url: /sv/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

Representerar alternativ för att lägga till vattenstämpel när en vattenstämpel läggs till en bild med flera ramar.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

Följande exempel visar hur man lägger till ett vattenmärke på en specifik ram i en flerbildsbild.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | Initierar en ny instans av `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`-klassen. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | Initierar en ny instans av `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`-klassen med ett specificerat index för ramen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | Hämtar indexet för ramen som vattenmärket ska läggas till på. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | Ställer in indexet för ramen som vattenmärket ska läggas till på. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


Initierar en ny instans av `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`-klassen.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


Initierar en ny instans av `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)`-klassen med ett specificerat index för ramen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | frameIndex | int | Indexet för ramen som vattenmärket ska läggas till på. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Hämtar indexet för ramen som vattenmärket ska läggas till på.


**Returns:**
int - Indexet för ramen som vattenmärket ska läggas till på.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


Ställer in indexet för ramen som vattenmärket ska läggas till på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Indexet för ramen som vattenmärket ska läggas till på. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

