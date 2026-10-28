---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor bij het toevoegen van een watermerk aan een masterdia van een Presentatiedocument."
type: docs
weight: 43
url: /nl/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Stelt opties voor bij het toevoegen van een watermerk aan een masterdia van een Presentatiedocument.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Bekijk de gebruiksvoorbeelden in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Initialiseert een nieuw exemplaar van de `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Haalt de index op van de masterdia waaraan het watermerk moet worden toegevoegd. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Stelt de index in van de masterdia waaraan het watermerk moet worden toegevoegd. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Initialiseert een nieuw exemplaar van de `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` klasse.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Haalt de index op van de masterdia waaraan het watermerk moet worden toegevoegd.


**Returns:**
int - De index van de masterdia waaraan het watermerk moet worden toegevoegd.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Stelt de index in van de masterdia waaraan het watermerk moet worden toegevoegd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De index van de masterdia waaraan het watermerk moet worden toegevoegd. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

