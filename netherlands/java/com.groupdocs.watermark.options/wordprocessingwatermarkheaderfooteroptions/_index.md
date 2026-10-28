---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt de opties voor bij het toevoegen van het watermerk aan een kop-/voettekst van een Word-sectie."
type: docs
weight: 74
url: /nl/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Stelt de opties voor bij het toevoegen van het watermerk aan een kop-/voettekst van een Word-sectie.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Initialiseert een nieuw exemplaar van de `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`‑klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Haalt de index van een sectie op om het watermerk toe te voegen. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Stelt de index van een sectie in om het watermerk toe te voegen. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Haalt de waarde op die het type koptekst of voettekst identificeert waaraan het watermerk moet worden toegevoegd. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Stelt de waarde in die het type kop- of voettekst identificeert waaraan het watermerk moet worden toegevoegd. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Initialiseert een nieuw exemplaar van de `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`‑klasse.


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

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Haalt de waarde op die het type koptekst of voettekst identificeert waaraan het watermerk moet worden toegevoegd.


**Returns:**
int - De waarde van het type `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` die het type kop- of voettekst identificeert waaraan het watermerk moet worden toegevoegd.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Stelt de waarde in die het type kop- of voettekst identificeert waaraan het watermerk moet worden toegevoegd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | int | De waarde van het type `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` die het type kop- of voettekst identificeert waaraan het watermerk moet worden toegevoegd. |
|

