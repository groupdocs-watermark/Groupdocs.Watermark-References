---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn Wasserzeichen zu Word-Dokumentseiten hinzugefügt werden."
type: docs
weight: 76
url: /de/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Stellt Optionen dar, wenn Wasserzeichen zu Word-Dokumentseiten hinzugefügt werden.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu einer bestimmten Seite eines Word-Dokuments hinzufügt.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Initialisiert eine neue Instanz der `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Ermittelt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Setzt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Initialisiert eine neue Instanz der `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` Klasse.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ermittelt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int[] - Die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

Alle Zahlen müssen größer oder gleich 1 sein. Diese Eigenschaft wird nur verwendet, wenn das Wasserzeichen zu einem Dokument hinzugefügt wird. Wenn dieser Wert null oder leer ist, wird das Wasserzeichen zu allen Seiten hinzugefügt.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Setzt die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Die Seitenzahlen, zu denen das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

Alle Zahlen müssen größer oder gleich 1 sein. Diese Eigenschaft wird nur verwendet, wenn das Wasserzeichen zu einem Dokument hinzugefügt wird. Wenn dieser Wert null oder leer ist, wird das Wasserzeichen zu allen Seiten hinzugefügt.

<br />

|

