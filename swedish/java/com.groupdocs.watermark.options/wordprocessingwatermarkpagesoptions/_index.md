---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när vattenmärke läggs till på Word-dokumentets sidor."
type: docs
weight: 76
url: /sv/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Representerar alternativ när vattenmärke läggs till på Word-dokumentets sidor.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Följande exempel visar hur man lägger till en vattenstämpel på en specifik sida i ett Word-dokument.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Initierar en ny instans av klassen `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Hämtar sidnumren för att lägga till vattenstämpeln. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ställer in sidnumren för att lägga till vattenstämpeln. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Initierar en ny instans av klassen `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Hämtar sidnumren för att lägga till vattenstämpeln.


**Returns:**
int[] - Sidnumren för att lägga till vattenstämpeln.

<br />

*** ** * ** ***

Alla nummer måste vara större än eller lika med 1. Denna egenskap används endast när vattenstämpeln läggs till i ett dokument. Om detta värde är  null  eller tomt, läggs vattenstämpeln till på alla sidor.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ställer in sidnumren för att lägga till vattenstämpeln.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int[] | Sidnumren för att lägga till vattenstämpeln. |

<br />

*** ** * ** ***

Alla nummer måste vara större än eller lika med 1. Denna egenskap används endast när vattenstämpeln läggs till i ett dokument. Om detta värde är  null  eller tomt, läggs vattenstämpeln till på alla sidor.

<br />

|

