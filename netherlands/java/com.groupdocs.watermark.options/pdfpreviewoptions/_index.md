---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt opties om vereisten en streamdelegates in te stellen voor de previewgeneratie van een PDF-document."
type: docs
weight: 31
url: /nl/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Biedt opties om vereisten en streamdelegates in te stellen voor de previewgeneratie van een PDF-document.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialiseert een nieuw exemplaar van de klasse `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` waardoor de outputstream wordt gesloten. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialiseert een nieuw exemplaar van de klasse `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` waardoor de outputstream wordt teruggegeven aan de client voor verder gebruik. |
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
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de klasse `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` waardoor de outputstream wordt gesloten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de klasse `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` waardoor de outputstream wordt teruggegeven aan de client voor verder gebruik.


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

De standaardwaarde is 150.

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

De standaardwaarde is 150.

<br />

|

