---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Präsentationsdokuments."
type: docs
weight: 12
url: /de/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Präsentationsdokuments.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialisiert eine neue Instanz der `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)`-Klasse, wodurch der Ausgabestream geschlossen wird. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialisiert eine neue Instanz der `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)`-Klasse, wodurch der Ausgabestream dem Client zur weiteren Verwendung zurückgegeben wird. |
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
|  | [setResolution(long value)](#setResolution-long-) | Legt die Auflösung der erzeugten Bilder in Punkten pro Zoll fest. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)`-Klasse, wodurch der Ausgabestream geschlossen wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz der `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)`-Klasse, wodurch der Ausgabestream dem Client zur weiteren Verwendung zurückgegeben wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Benachrichtigt, dass die Erstellung der Seitenvorschau abgeschlossen ist, und gibt den Ausgabestream zurück. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Standardauflösung in Punkten pro Zoll.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Ermittelt die Auflösung der erzeugten Bilder in Punkten pro Zoll.


**Returns:**
long - Die Auflösung der erzeugten Bilder in Punkten pro Zoll.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Legt die Auflösung der erzeugten Bilder in Punkten pro Zoll fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | long | Die Auflösung der erzeugten Bilder in Punkten pro Zoll. |
|

