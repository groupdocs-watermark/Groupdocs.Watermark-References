---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld van een e-maildocument."
type: docs
weight: 17
url: /nl/java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld van een e-maildocument.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialiseert een nieuw exemplaar van de `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` klasse waardoor de outputstroom wordt gesloten. |
|
|  | [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialiseert een nieuw exemplaar van `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` klasse waardoor de outputstroom wordt teruggegeven aan de client voor verder gebruik. |
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
|  | [setResolution(float value)](#setResolution-float-) | Stelt de resolutie in voor de gegenereerde afbeeldingen, in dots per inch. |
|
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` klasse waardoor de outputstroom wordt gesloten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` klasse waardoor de outputstroom wordt teruggegeven aan de client voor verder gebruik.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meldt dat de generatie van het paginavoorbeeld voltooid is en haalt de uitvoerstroom op. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Standaardresolutie in dots per inch.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Haalt de resolutie op voor de gegenereerde afbeeldingen, in dots per inch.


**Returns:**
float - De resolutie voor de gegenereerde afbeeldingen, in punten per inch.

<br />

*** ** * ** ***

De standaardwaarde is 96.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Stelt de resolutie in voor de gegenereerde afbeeldingen, in dots per inch.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | De resolutie voor de gegenereerde afbeeldingen, in dots per inch. |

<br />

*** ** * ** ***

De standaardwaarde is 96.

<br />

|

