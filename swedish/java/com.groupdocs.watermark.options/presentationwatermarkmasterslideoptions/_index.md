---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när en vattenstämpel läggs till en huvudbild i ett presentationsdokument."
type: docs
weight: 43
url: /sv/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Representerar alternativ när en vattenstämpel läggs till en huvudbild i ett presentationsdokument.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Se användningsexemplen i `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Initierar en ny instans av klassen `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Hämtar indexet för master‑bilden som vattenstämpeln ska läggas till på. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Ställer in indexet för master‑bilden som vattenstämpeln ska läggas till på. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Initierar en ny instans av klassen `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)`.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Hämtar indexet för master‑bilden som vattenstämpeln ska läggas till på.


**Returns:**
int - Indexet för master‑bilden som vattenstämpeln ska läggas till på.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Ställer in indexet för master‑bilden som vattenstämpeln ska läggas till på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Indexet för master‑bilden som vattenstämpeln ska läggas till på. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

