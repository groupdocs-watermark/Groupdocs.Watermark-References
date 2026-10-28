---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld van een Diagramdocument."
type: docs
weight: 12
url: /nl/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld van een Diagramdocument.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialiseert een nieuw exemplaar van de `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` klasse waardoor de uitvoerstroom wordt gesloten. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialiseert een nieuw exemplaar van `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik. |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Haalt de vlag voor rendering van hoge kwaliteit op. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Stelt de vlag voor rendering van hoge kwaliteit in. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` klasse waardoor de uitvoerstroom wordt gesloten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Maakt een stream voor een specifieke paginavoorbeeld. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik.


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

De standaardwaarde is 300.

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

De standaardwaarde is 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Haalt de vlag voor rendering van hoge kwaliteit op.


**Returns:**
boolean - De vlag voor rendering van hoge kwaliteit.

<br />

*** ** * ** ***

Rendering van hoge kwaliteit gebruikt meer bronnen. De standaardwaarde is  false .

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Stelt de vlag voor rendering van hoge kwaliteit in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | De vlag voor rendering van hoge kwaliteit. |

<br />

*** ** * ** ***

Rendering van hoge kwaliteit gebruikt meer bronnen. De standaardwaarde is  false .

<br />

|

