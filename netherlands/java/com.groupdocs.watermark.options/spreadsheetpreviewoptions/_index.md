---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld van een Spreadsheet-document."
type: docs
weight: 52
url: /nl/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Biedt opties om vereisten en streamdelegates in te stellen voor het genereren van een voorbeeld van een Spreadsheet-document.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialiseert een nieuw exemplaar van de `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` klasse waardoor de uitvoerstroom wordt gesloten. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialiseert een nieuw exemplaar van de `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Standaardresolutie in dots per inch. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getResolution()](#getResolution--) | Haalt de resolutie op voor de gegenereerde afbeeldingen, in dots per inch. |
|
|  | [setResolution(int value)](#setResolution-int-) | Stelt de resolutie in voor de gegenereerde afbeeldingen, in dots per inch. |
|
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Haalt de vlag op voor het weergeven van alleen het gegevensgebied zonder kopteksten, voetteksten en marges. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Stelt de vlag in voor het weergeven van alleen het gegevensgebied zonder kopteksten, voetteksten en marges. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` klasse waardoor de uitvoerstroom wordt gesloten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meldt dat de generatie van het paginavoorbeeld voltooid is en haalt de uitvoerstroom op. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Standaardresolutie in dots per inch.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Haalt de resolutie op voor de gegenereerde afbeeldingen, in dots per inch.


**Returns:**
int - De resolutie voor de gegenereerde afbeeldingen, in dots per inch.

<br />

*** ** * ** ***

De standaardwaarde is 96.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Stelt de resolutie in voor de gegenereerde afbeeldingen, in dots per inch.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De resolutie voor de gegenereerde afbeeldingen, in dots per inch. |

<br />

*** ** * ** ***

De standaardwaarde is 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Haalt de vlag op voor het weergeven van alleen het gegevensgebied zonder kopteksten, voetteksten en marges.


**Returns:**
boolean - De vlag voor het weergeven van alleen het gegevensgebied zonder kopteksten, voetteksten en marges.

<br />

*** ** * ** ***

Deze vlag leidt tot het weergeven van het volledige werkblad op één pagina. De standaardwaarde is false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Stelt de vlag in voor het weergeven van alleen het gegevensgebied zonder kopteksten, voetteksten en marges.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | De vlag voor het weergeven van alleen het gegevensgebied zonder kopteksten, voetteksten en marges. |

<br />

*** ** * ** ***

Deze vlag leidt tot het weergeven van het volledige werkblad op één pagina. De standaardwaarde is false.

<br />

|

