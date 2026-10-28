---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn ein Form-Wasserzeichen zu einem Word-Dokumentabschnitt hinzugefügt wird."
type: docs
weight: 77
url: /de/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Stellt Optionen dar, wenn ein Form-Wasserzeichen zu einem Word-Dokumentabschnitt hinzugefügt wird.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu einem bestimmten Abschnitt eines Word-Dokuments hinzufügt.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Initialisiert eine neue Instanz der `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Ermittelt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Setzt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Initialisiert eine neue Instanz der `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` Klasse.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Ermittelt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Setzt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

