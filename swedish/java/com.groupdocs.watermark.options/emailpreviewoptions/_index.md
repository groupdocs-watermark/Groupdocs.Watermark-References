---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller alternativ för att sätta krav och strömbefogenheter för förhandsgranskning av e‑postdokument."
type: docs
weight: 17
url: /sv/java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

Tillhandahåller alternativ för att sätta krav och strömbefogenheter för förhandsgranskning av e‑postdokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initierar en ny instans av klassen `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` som gör att utdataflödet stängs. |
|
|  | [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initierar en ny instans av `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)`-klassen som gör att utdataflödet returneras till klienten för vidare användning. |
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
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


Initierar en ny instans av klassen `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` som gör att utdataflödet stängs.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initierar en ny instans av `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)`-klassen som gör att utdataflödet returneras till klienten för vidare användning.


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

Standardvärdet är 96.

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

Standardvärdet är 96.

<br />

|

