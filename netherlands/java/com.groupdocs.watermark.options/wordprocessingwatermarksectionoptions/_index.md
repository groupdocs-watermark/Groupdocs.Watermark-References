---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt de opties voor bij het toevoegen van een vormwatermerk aan een Word-documentsectie."
type: docs
weight: 77
url: /nl/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Stelt de opties voor bij het toevoegen van een vormwatermerk aan een Word-documentsectie.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Het volgende voorbeeld toont hoe u een watermerk kunt toevoegen aan een specifiek gedeelte van een Word-document.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Initialiseert een nieuw exemplaar van de klasse `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Haalt de index van een sectie op om het watermerk toe te voegen. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Stelt de index van een sectie in om het watermerk toe te voegen. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Initialiseert een nieuw exemplaar van de klasse `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Haalt de index van een sectie op om het watermerk toe te voegen.


**Returns:**
int - De index van een sectie waaraan het watermerk moet worden toegevoegd.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Stelt de index van een sectie in om het watermerk toe te voegen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De index van een sectie waaraan het watermerk moet worden toegevoegd. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

