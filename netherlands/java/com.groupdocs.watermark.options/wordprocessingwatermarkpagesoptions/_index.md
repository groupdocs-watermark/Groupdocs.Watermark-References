---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt de opties voor bij het toevoegen van een watermerk aan Word-documentpagina's."
type: docs
weight: 76
url: /nl/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Stelt de opties voor bij het toevoegen van een watermerk aan Word-documentpagina's.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Het volgende voorbeeld laat zien hoe u een watermerk toevoegt aan een specifieke pagina van een Word‑document.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Initialiseert een nieuw exemplaar van de `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`‑klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Haalt de paginanummers op om het watermerk toe te voegen. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Stelt de paginanummers in om het watermerk toe te voegen. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Initialiseert een nieuw exemplaar van de `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`‑klasse.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Haalt de paginanummers op om het watermerk toe te voegen.


**Returns:**
int[] - De paginanummers om het watermerk toe te voegen.

<br />

*** ** * ** ***

Alle getallen moeten groter dan of gelijk aan 1 zijn. Deze eigenschap wordt alleen gebruikt bij het toevoegen van het watermerk aan een document. Als deze waarde null of leeg is, wordt het watermerk aan alle pagina's toegevoegd.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Stelt de paginanummers in om het watermerk toe te voegen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int[] | De paginanummers om het watermerk toe te voegen. |

<br />

*** ** * ** ***

Alle getallen moeten groter dan of gelijk aan 1 zijn. Deze eigenschap wordt alleen gebruikt bij het toevoegen van het watermerk aan een document. Als deze waarde null of leeg is, wordt het watermerk aan alle pagina's toegevoegd.

<br />

|

