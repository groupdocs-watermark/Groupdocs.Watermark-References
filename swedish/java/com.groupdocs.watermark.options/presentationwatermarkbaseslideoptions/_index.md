---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Basklass för alternativ för att lägga till vattenstämpel till ett presentationsdokument."
type: docs
weight: 39
url: /sv/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Basklass för alternativ för att lägga till vattenstämpel till ett presentationsdokument.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Följande exempel visar hur man lägger till en vattenstämpel på olika service‑bilder i en Power Point-presentation.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLocked()](#isLocked--) | Hämtar ett värde som indikerar om redigering av formen i PowerPoint är förbjuden. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Ställer in ett värde som indikerar om redigering av formen i PowerPoint är förbjuden. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Hämtar eller anger ett värde som indikerar om tecken i textvattenstämpeln blandas med oläsliga tecken. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Hämtar eller anger ett värde som indikerar om tecken i textvattenstämpeln blandas med oläsliga tecken. |
|
|  | [getName()](#getName--) | Hämtar namnet på en form. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Anger namnet på en form. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Hämtar den beskrivande (alternativa) texten som kommer att associeras med en form. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Anger den beskrivande (alternativa) texten som kommer att associeras med en form. |
|
|  | [getEffects()](#getEffects--) | Hämtar ett värde av `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` eller `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` för effekter som ska tillämpas på vattenstämpeln. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Ställer in ett värde av `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` eller `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` för effekter som ska tillämpas på vattenstämpeln. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Hämtar ett värde som indikerar om redigering av formen i PowerPoint är förbjuden.


**Returns:**
boolean – Om värdet är true kommer redigering av formen att vara förbjuden. Som standard är värdet false, så formen kan redigeras i PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Ställer in ett värde som indikerar om redigering av formen i PowerPoint är förbjuden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Om värdet är true kommer redigering av formen att vara förbjuden. Som standard är värdet false, så formen kan redigeras i PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Hämtar eller anger ett värde som indikerar om tecken i textvattenstämpeln blandas med oläsliga tecken.

Detta skydd gäller endast när `#isLocked().isLocked()` returnerar `true`.


**Returns:**
boolean – Ett värde som indikerar om tecken i textvattenstämpeln blandas med oläsliga tecken.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Hämtar eller anger ett värde som indikerar om tecken i textvattenstämpeln blandas med oläsliga tecken.

Detta skydd gäller endast när `#isLocked().isLocked()` returnerar `true`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Ett värde som indikerar om textvattenmärkestecknen är blandade med oläsliga tecken. |
|

### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på en form.


**Returns:**
java.lang.String - Formens namn.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Anger namnet på en form.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Formens namn. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Hämtar den beskrivande (alternativa) texten som kommer att associeras med en form.


**Returns:**
java.lang.String - Den beskrivande (alternativa) texten som kommer att associeras med en form.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Anger den beskrivande (alternativa) texten som kommer att associeras med en form.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Den beskrivande (alternativa) texten som kommer att associeras med en form. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Hämtar ett värde av `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` eller `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` för effekter som ska tillämpas på vattenstämpeln.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Ställer in ett värde av `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` eller `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` för effekter som ska tillämpas på vattenstämpeln.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | Värdet för `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` eller `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` för effekter som ska tillämpas på vattenmärket. |
|

