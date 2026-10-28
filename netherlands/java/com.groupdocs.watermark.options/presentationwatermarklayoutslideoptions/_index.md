---
title: "PresentationWatermarkLayoutSlideOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt opties voor bij het toevoegen van een watermerk aan een lay-outdia van een Presentatiedocument."
type: docs
weight: 40
url: /nl/java/com.groupdocs.watermark.options/presentationwatermarklayoutslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkLayoutSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Stelt opties voor bij het toevoegen van een watermerk aan een lay-outdia van een Presentatiedocument.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Bekijk de gebruiksvoorbeelden in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationWatermarkLayoutSlideOptions()](#PresentationWatermarkLayoutSlideOptions--) | Initialiseert een nieuw exemplaar van de `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLayoutSlideIndex()](#getLayoutSlideIndex--) | Haalt de index op van de lay-outdia waaraan het watermerk moet worden toegevoegd. |
|
|  | [setLayoutSlideIndex(int value)](#setLayoutSlideIndex-int-) | Stelt de index in van de lay-outdia waaraan het watermerk moet worden toegevoegd. |
|
### PresentationWatermarkLayoutSlideOptions() {#PresentationWatermarkLayoutSlideOptions--}
```
public PresentationWatermarkLayoutSlideOptions()
```


Initialiseert een nieuw exemplaar van de `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)` klasse.


### getLayoutSlideIndex() {#getLayoutSlideIndex--}
```
public final int getLayoutSlideIndex()
```


Haalt de index op van de lay-outdia waaraan het watermerk moet worden toegevoegd.


**Returns:**
int - De index van de lay-outdia waaraan het watermerk moet worden toegevoegd.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setLayoutSlideIndex(int value) {#setLayoutSlideIndex-int-}
```
public final void setLayoutSlideIndex(int value)
```


Stelt de index in van de lay-outdia waaraan het watermerk moet worden toegevoegd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De index van de lay-outdia waaraan het watermerk moet worden toegevoegd. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

