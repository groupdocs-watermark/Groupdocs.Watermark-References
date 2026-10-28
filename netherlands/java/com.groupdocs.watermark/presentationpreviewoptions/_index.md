---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld van een Presentatiedocument."
type: docs
weight: 12
url: /nl/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld van een Presentatiedocument.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialiseert een nieuw exemplaar van de `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` klasse waardoor de outputstream wordt gesloten. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialiseert een nieuw exemplaar van de `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` klasse waardoor de outputstream wordt geretourneerd aan de client voor verder gebruik. |
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
|  | [setResolution(long value)](#setResolution-long-) | Stelt de resolutie in voor de gegenereerde afbeeldingen, in dots per inch. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` klasse waardoor de outputstream wordt gesloten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` klasse waardoor de outputstream wordt geretourneerd aan de client voor verder gebruik.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meldt dat de generatie van het paginavoorbeeld voltooid is en haalt de uitvoerstroom op. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Standaardresolutie in dots per inch.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Haalt de resolutie op voor de gegenereerde afbeeldingen, in dots per inch.


**Returns:**
long - De resolutie voor de gegenereerde afbeeldingen, in dots per inch.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Stelt de resolutie in voor de gegenereerde afbeeldingen, in dots per inch.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | long | De resolutie voor de gegenereerde afbeeldingen, in dots per inch. |
|

