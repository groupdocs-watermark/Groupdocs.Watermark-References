---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines WordProcessing-Dokuments."
type: docs
weight: 69
url: /de/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines WordProcessing-Dokuments.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialisiert eine neue Instanz der `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` Klasse, die den Ausgabestream schließt. |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialisiert eine neue Instanz der `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` Klasse, die den Ausgabestream an den Client zurückgibt, um ihn weiter zu verwenden. |
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
|  | [setResolution(float value)](#setResolution-float-) | Legt die Auflösung der erzeugten Bilder in Punkten pro Zoll fest. |
|
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` Klasse, die den Ausgabestream schließt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz der `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` Klasse, die den Ausgabestream an den Client zurückgibt, um ihn weiter zu verwenden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Benachrichtigt, dass die Erstellung der Seitenvorschau abgeschlossen ist, und gibt den Ausgabestream zurück. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Standardauflösung in Punkten pro Zoll.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Ermittelt die Auflösung der erzeugten Bilder in Punkten pro Zoll.


**Returns:**
float - Die Auflösung für die erzeugten Bilder, in Punkten pro Zoll.

<br />

*** ** * ** ***

Der Standardwert ist 96.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Legt die Auflösung der erzeugten Bilder in Punkten pro Zoll fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | Die Auflösung der erzeugten Bilder in Punkten pro Zoll. |

<br />

*** ** * ** ***

Der Standardwert ist 96.

<br />

|

