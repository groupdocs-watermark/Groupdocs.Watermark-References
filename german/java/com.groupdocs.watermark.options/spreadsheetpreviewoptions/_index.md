---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Kalkulationstabellendokuments."
type: docs
weight: 52
url: /de/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Kalkulationstabellendokuments.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialisiert eine neue Instanz der `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` Klasse, wodurch der Ausgabestream geschlossen wird. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialisiert eine neue Instanz der `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` Klasse, wodurch der Ausgabestream an den Client zurückgegeben wird für weitere Verwendung. |
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
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Liest das Flag für das Rendern nur des Datenbereichs ohne Kopf‑, Fußzeilen und Ränder. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Setzt das Flag für das Rendern nur des Datenbereichs ohne Kopf‑, Fußzeilen und Ränder. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` Klasse, wodurch der Ausgabestream geschlossen wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz der `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` Klasse, wodurch der Ausgabestream an den Client zurückgegeben wird für weitere Verwendung.


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

Der Standardwert ist 96.

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

Der Standardwert ist 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Liest das Flag für das Rendern nur des Datenbereichs ohne Kopf‑, Fußzeilen und Ränder.


**Returns:**
boolean – Das Flag für das Rendern nur des Datenbereichs ohne Kopf‑, Fußzeilen und Ränder.

<br />

*** ** * ** ***

Dieses Flag führt dazu, dass das gesamte Arbeitsblatt auf einer Seite gerendert wird. Der Standardwert ist false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Setzt das Flag für das Rendern nur des Datenbereichs ohne Kopf‑, Fußzeilen und Ränder.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Das Flag für das Rendern nur des Datenbereichs ohne Kopf‑, Fußzeilen und Ränder. |

<br />

*** ** * ** ***

Dieses Flag führt dazu, dass das gesamte Arbeitsblatt auf einer Seite gerendert wird. Der Standardwert ist false.

<br />

|

