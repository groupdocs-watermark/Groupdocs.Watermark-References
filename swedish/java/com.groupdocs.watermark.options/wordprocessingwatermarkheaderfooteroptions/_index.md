---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar alternativ när vattenmärket läggs till i ett Word-sektionshuvud/fot."
type: docs
weight: 74
url: /sv/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Representerar alternativ när vattenmärket läggs till i ett Word-sektionshuvud/fot.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Initierar en ny instans av klassen `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Hämtar indexet för ett avsnitt som vattenstämpeln ska läggas till på. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Ställer in indexet för ett avsnitt som vattenstämpeln ska läggas till på. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Hämtar värdet som identifierar typen av sidhuvud eller sidfot som vattenstämpeln ska läggas till på. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Ställer in värdet som identifierar typen av sidhuvud eller sidfot att lägga vattenstämpeln på. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Initierar en ny instans av klassen `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`.


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

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Hämtar värdet som identifierar typen av sidhuvud eller sidfot som vattenstämpeln ska läggas till på.


**Returns:**
int - Värdet av typen `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` som identifierar typen av sidhuvud eller sidfot att lägga vattenstämpeln på.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Ställer in värdet som identifierar typen av sidhuvud eller sidfot att lägga vattenstämpeln på.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Värdet av typen `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` som identifierar typen av sidhuvud eller sidfot att lägga vattenstämpeln på. |
|

