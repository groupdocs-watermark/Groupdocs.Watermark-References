---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Diagrammdokuments."
type: docs
weight: 12
url: /de/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Diagrammdokuments.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialisiert eine neue Instanz der `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` Klasse, die den Ausgabestream schließt. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialisiert eine neue Instanz von `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` Klasse, die den Ausgabestream an den Client zurückgibt, um ihn weiter zu verwenden. |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Ruft das Flag für die hochqualitative Darstellung ab. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Setzt das Flag für die hochqualitative Darstellung. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` Klasse, die den Ausgabestream schließt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz von `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` Klasse, die den Ausgabestream an den Client zurückgibt, um ihn weiter zu verwenden.


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

Der Standardwert ist 300.

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

Der Standardwert ist 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Ruft das Flag für die hochqualitative Darstellung ab.


**Returns:**
boolean - Das Flag für die hochqualitative Darstellung.

<br />

*** ** * ** ***

Die hochqualitative Darstellung verwendet mehr Ressourcen. Der Standardwert ist false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Setzt das Flag für die hochqualitative Darstellung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | Das Flag für die hochqualitative Darstellung. |

<br />

*** ** * ** ***

Die hochqualitative Darstellung verwendet mehr Ressourcen. Der Standardwert ist false.

<br />

|

