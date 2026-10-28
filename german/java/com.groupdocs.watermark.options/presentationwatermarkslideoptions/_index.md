---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn ein Wasserzeichen zu einer Folie eines Präsentationsdokuments hinzugefügt wird."
type: docs
weight: 46
url: /de/java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Stellt Optionen dar, wenn ein Wasserzeichen zu einer Folie eines Präsentationsdokuments hinzugefügt wird.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Das folgende Beispiel zeigt, wie man einem bestimmten Folie einer Power‑Point‑Präsentation ein Wasserzeichen hinzufügt.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | Initialisiert eine neue Instanz der Klasse `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | Gibt den Index der Folie zurück, zu der das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | Legt den Index der Folie fest, zu der das Wasserzeichen hinzugefügt werden soll. |
|
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


Initialisiert eine neue Instanz der Klasse `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)`.


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Gibt den Index der Folie zurück, zu der das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Index der Folie, zu der das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


Legt den Index der Folie fest, zu der das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index der Folie, zu der das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

