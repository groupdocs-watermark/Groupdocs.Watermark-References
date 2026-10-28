---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines PDF‑Dokuments."
type: docs
weight: 31
url: /de/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Bietet Optionen zum Festlegen von Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines PDF‑Dokuments.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialisiert eine neue Instanz der `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` Klasse, wodurch der Ausgabestream geschlossen wird. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialisiert eine neue Instanz von `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` Klasse, wodurch der Ausgabestream dem Client für weitere Verwendung zurückgegeben wird. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Standardauflösung in Punkten pro Zoll. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getResolution()](#getResolution--) | Ermittelt die Auflösung der erzeugten Bilder in Punkten pro Zoll. |
|
|  | [setResolution(int value)](#setResolution-int-) | Legt die Auflösung der erzeugten Bilder in Punkten pro Zoll fest. |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` Klasse, wodurch der Ausgabestream geschlossen wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz von `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` Klasse, wodurch der Ausgabestream dem Client für weitere Verwendung zurückgegeben wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Benachrichtigt, dass die Erstellung der Seitenvorschau abgeschlossen ist, und gibt den Ausgabestream zurück. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Standardauflösung in Punkten pro Zoll.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Ermittelt die Auflösung der erzeugten Bilder in Punkten pro Zoll.


**Returns:**
int – Die Auflösung für die erzeugten Bilder, in Punkten pro Zoll.

<br />

*** ** * ** ***

Der Standardwert ist 150.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Legt die Auflösung der erzeugten Bilder in Punkten pro Zoll fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Auflösung der erzeugten Bilder in Punkten pro Zoll. |

<br />

*** ** * ** ***

Der Standardwert ist 150.

<br />

|

