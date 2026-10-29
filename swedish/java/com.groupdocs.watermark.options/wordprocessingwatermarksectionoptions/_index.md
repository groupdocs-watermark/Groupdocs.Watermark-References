---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när ett formvattenmärke läggs till i en Word-dokumentsektion."
type: docs
weight: 77
url: /sv/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Representerar alternativ när ett formvattenmärke läggs till i en Word-dokumentsektion.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Följande exempel visar hur man lägger till en vattenstämpel i ett specifikt avsnitt i ett Word-dokument.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Initierar en ny instans av klassen `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Hämtar indexet för ett avsnitt som vattenstämpeln ska läggas till på. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Ställer in indexet för ett avsnitt som vattenstämpeln ska läggas till på. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Initierar en ny instans av klassen `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Hämtar indexet för ett avsnitt som vattenstämpeln ska läggas till på.


**Returns:**
int - Indexet för ett avsnitt att lägga vattenstämpeln på.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Ställer in indexet för ett avsnitt som vattenstämpeln ska läggas till på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Indexet för ett avsnitt att lägga vattenstämpeln på. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

