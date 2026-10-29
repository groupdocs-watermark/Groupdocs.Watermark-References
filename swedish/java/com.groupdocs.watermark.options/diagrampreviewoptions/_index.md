---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller alternativ för att sätta krav och strömbefogenheter för förhandsgranskning av diagramdokument."
type: docs
weight: 12
url: /sv/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Tillhandahåller alternativ för att sätta krav och strömbefogenheter för förhandsgranskning av diagramdokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initierar en ny instans av klassen `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` som gör att utdataströmmen stängs. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initierar en ny instans av `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` klassen som gör att utdataströmmen returneras till klienten för vidare användning. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Standardupplösning i punkter per tum. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getResolution()](#getResolution--) | Hämtar upplösningen för de genererade bilderna, i punkter per tum. |
|
|  | [setResolution(float value)](#setResolution-float-) | Ställer in upplösningen för de genererade bilderna, i punkter per tum. |
|
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Hämtar flaggan för rendering med hög kvalitet. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Ställer in flaggan för rendering med hög kvalitet. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Initierar en ny instans av klassen `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` som gör att utdataströmmen stängs.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initierar en ny instans av `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` klassen som gör att utdataströmmen returneras till klienten för vidare användning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataströmmen. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Standardupplösning i punkter per tum.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Hämtar upplösningen för de genererade bilderna, i punkter per tum.


**Returns:**
float – Upplösningen för de genererade bilderna, i punkter per tum.

<br />

*** ** * ** ***

Standardvärdet är 300.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Ställer in upplösningen för de genererade bilderna, i punkter per tum.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | Upplösningen för de genererade bilderna, i punkter per tum. |

<br />

*** ** * ** ***

Standardvärdet är 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Hämtar flaggan för rendering med hög kvalitet.


**Returns:**
boolean - Flaggan för rendering med hög kvalitet.

<br />

*** ** * ** ***

Rendering med hög kvalitet använder fler resurser. Standardvärdet är falskt.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Ställer in flaggan för rendering med hög kvalitet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Flaggan för rendering med hög kvalitet. |

<br />

*** ** * ** ***

Rendering med hög kvalitet använder fler resurser. Standardvärdet är falskt.

<br />

|

