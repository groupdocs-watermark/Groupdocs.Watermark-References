---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller alternativ för att ange krav och strömbefogenheter för förhandsgranskning av PDF-dokument."
type: docs
weight: 31
url: /sv/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Tillhandahåller alternativ för att ange krav och strömbefogenheter för förhandsgranskning av PDF-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initierar en ny instans av klassen `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` som får utdataflödet att stängas. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initierar en ny instans av klassen `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` som får utdataflödet att returneras till klienten för vidare användning. |
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
|  | [setResolution(int value)](#setResolution-int-) | Ställer in upplösningen för de genererade bilderna, i punkter per tum. |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Initierar en ny instans av klassen `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` som får utdataflödet att stängas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initierar en ny instans av klassen `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` som får utdataflödet att returneras till klienten för vidare användning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataströmmen. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Standardupplösning i punkter per tum.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Hämtar upplösningen för de genererade bilderna, i punkter per tum.


**Returns:**
int - Upplösningen för de genererade bilderna, i punkter per tum.

<br />

*** ** * ** ***

Standardvärdet är 150.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Ställer in upplösningen för de genererade bilderna, i punkter per tum.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Upplösningen för de genererade bilderna, i punkter per tum. |

<br />

*** ** * ** ***

Standardvärdet är 150.

<br />

|

