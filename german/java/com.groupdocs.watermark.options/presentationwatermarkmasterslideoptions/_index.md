---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen beim Hinzufügen von Wasserzeichen zu einer Master‑Folie eines Präsentationsdokuments dar."
type: docs
weight: 43
url: /de/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Stellt Optionen beim Hinzufügen von Wasserzeichen zu einer Master‑Folie eines Präsentationsdokuments dar.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Siehe die Anwendungsbeispiele in `[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | Initialisiert eine neue Instanz der `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | Liest den Index der Masterfolie, zu der das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | Setzt den Index der Masterfolie, zu der das Wasserzeichen hinzugefügt werden soll. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


Initialisiert eine neue Instanz der `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` Klasse.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


Liest den Index der Masterfolie, zu der das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Index der Masterfolie, zu der das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


Setzt den Index der Masterfolie, zu der das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index der Masterfolie, zu der das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

