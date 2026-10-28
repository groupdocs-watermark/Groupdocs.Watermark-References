---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Basisklasse voor opties voor het toevoegen van een watermerk aan een Presentatiedocument."
type: docs
weight: 39
url: /nl/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Basisklasse voor opties voor het toevoegen van een watermerk aan een Presentatiedocument.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Het volgende voorbeeld toont hoe je een watermerk toevoegt aan verschillende service‑dia's van een Power Point-presentatie.
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


## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isLocked()](#isLocked--) | Haalt een waarde op die aangeeft of bewerken van de vorm in PowerPoint verboden is. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Stelt een waarde in die aangeeft of bewerken van de vorm in PowerPoint verboden is. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Haalt een waarde op of stelt deze in die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens. |
|
|  | [getName()](#getName--) | Haalt de naam van een vorm op. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Stelt de naam van een vorm in. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Haalt de beschrijvende (alternatieve) tekst op die aan een vorm zal worden gekoppeld. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Stelt de beschrijvende (alternatieve) tekst in die aan een vorm zal worden gekoppeld. |
|
|  | [getEffects()](#getEffects--) | Haalt een waarde van `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` of `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` op voor effecten die op het watermerk moeten worden toegepast. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Stelt een waarde van `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` of `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` in voor effecten die op het watermerk moeten worden toegepast. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Haalt een waarde op die aangeeft of bewerken van de vorm in PowerPoint verboden is.


**Returns:**
boolean - Als de waarde true is, wordt bewerken van de vorm verboden. Standaard is de waarde false, de vorm kan worden bewerkt in PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Stelt een waarde in die aangeeft of bewerken van de vorm in PowerPoint verboden is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Als de waarde true is, wordt bewerken van de vorm verboden. Standaard is de waarde false, de vorm kan worden bewerkt in PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Haalt een waarde op of stelt deze in die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens.

Deze bescherming is alleen van toepassing wanneer `#isLocked().isLocked()` `true` retourneert.


**Returns:**
boolean - Een waarde die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens.

Deze bescherming is alleen van toepassing wanneer `#isLocked().isLocked()` `true` retourneert.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Een waarde die aangeeft of de tekstopwatermerktekens gemengd zijn met onleesbare tekens. |
|

### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van een vorm op.


**Returns:**
java.lang.String - De vormnaam.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Stelt de naam van een vorm in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De vormnaam. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Haalt de beschrijvende (alternatieve) tekst op die aan een vorm zal worden gekoppeld.


**Returns:**
java.lang.String - De beschrijvende (alternatieve) tekst die aan een vorm zal worden gekoppeld.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Stelt de beschrijvende (alternatieve) tekst in die aan een vorm zal worden gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De beschrijvende (alternatieve) tekst die aan een vorm zal worden gekoppeld. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Haalt een waarde van `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` of `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` op voor effecten die op het watermerk moeten worden toegepast.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Stelt een waarde van `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` of `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` in voor effecten die op het watermerk moeten worden toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | De waarde van `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` of `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` voor effecten die op het watermerk moeten worden toegepast. |
|

