---
title: "PresentationWatermarkLayoutSlideOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen beim Hinzufügen von Wasserzeichen zu einer Layoutfolie eines Präsentationsdokuments dar."
type: docs
weight: 40
url: /de/java/com.groupdocs.watermark.options/presentationwatermarklayoutslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkLayoutSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Stellt Optionen beim Hinzufügen von Wasserzeichen zu einer Layoutfolie eines Präsentationsdokuments dar.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Siehe die Anwendungsbeispiele in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationWatermarkLayoutSlideOptions()](#PresentationWatermarkLayoutSlideOptions--) | Initialisiert eine neue Instanz der Klasse `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)`. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLayoutSlideIndex()](#getLayoutSlideIndex--) | Ermittelt den Index der Layout‑Folie, zu der das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setLayoutSlideIndex(int value)](#setLayoutSlideIndex-int-) | Legt den Index der Layout‑Folie fest, zu der das Wasserzeichen hinzugefügt werden soll. |
|
### PresentationWatermarkLayoutSlideOptions() {#PresentationWatermarkLayoutSlideOptions--}
```
public PresentationWatermarkLayoutSlideOptions()
```


Initialisiert eine neue Instanz der Klasse `[PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)`.


### getLayoutSlideIndex() {#getLayoutSlideIndex--}
```
public final int getLayoutSlideIndex()
```


Ermittelt den Index der Layout‑Folie, zu der das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Index der Layout‑Folie, zu der das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setLayoutSlideIndex(int value) {#setLayoutSlideIndex-int-}
```
public final void setLayoutSlideIndex(int value)
```


Legt den Index der Layout‑Folie fest, zu der das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index der Layout‑Folie, zu der das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

