---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när en vattenstämpel läggs till på en bild i ett Presentation-dokument."
type: docs
weight: 46
url: /sv/java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Representerar alternativ när en vattenstämpel läggs till på en bild i ett Presentation-dokument.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Följande exempel visar hur man lägger till ett vattenmärke på en specifik bild i en Power Point-presentation.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.ppt", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>  
>    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
>    options.setSlideIndex(0);
>    options.setLocked(false); // default
>    options.setProtectWithUnreadableCharacters(false); // default
>    options.setName(null); // default
>    options.setAlternativeText(null); // default
>    
>    watermarker.save("C:\\Documents\\watermarked_test.ppt");
>    watermarker.close();
>  
> ```
> ````


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | Initierar en ny instans av klassen `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | Hämtar indexet för bilden som vattenmärket ska läggas till på. |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | Ställer in indexet för bilden som vattenstämpeln ska läggas till på. |
|
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


Initierar en ny instans av klassen `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`.


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Hämtar indexet för bilden som vattenmärket ska läggas till på.


**Returns:**
int - Indexet för bilden som vattenstämpeln ska läggas till på.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


Ställer in indexet för bilden som vattenstämpeln ska läggas till på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Indexet för bilden som vattenstämpeln ska läggas till på. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

