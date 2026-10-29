---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller alternativ för att sätta krav och strömbefogenheter för förhandsgranskning av presentationsdokument."
type: docs
weight: 12
url: /sv/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Tillhandahåller alternativ för att sätta krav och strömbefogenheter för förhandsgranskning av presentationsdokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initierar en ny instans av klassen `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` som gör att utdataströmmen stängs. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initierar en ny instans av `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)`-klassen som gör att utdataströmmen returneras till klienten för vidare användning. |
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
|  | [setResolution(long value)](#setResolution-long-) | Ställer in upplösningen för de genererade bilderna, i punkter per tum. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Initierar en ny instans av klassen `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` som gör att utdataströmmen stängs.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initierar en ny instans av `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)`-klassen som gör att utdataströmmen returneras till klienten för vidare användning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataströmmen. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Standardupplösning i punkter per tum.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Hämtar upplösningen för de genererade bilderna, i punkter per tum.


**Returns:**
long - Upplösningen för de genererade bilderna, i punkter per tum.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Ställer in upplösningen för de genererade bilderna, i punkter per tum.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | long | Upplösningen för de genererade bilderna, i punkter per tum. |
|

