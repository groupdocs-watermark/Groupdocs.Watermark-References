---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung."
type: docs
weight: 47
url: /de/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialisiert eine neue Instanz der `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` Klasse, die den Ausgabestream schließt. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialisiert eine neue Instanz der `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` Klasse, wodurch der Ausgabestream dem Client für weitere Verwendung zurückgegeben wird. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Liefert die Seitenvorschaubreite. |
|
|  | [setWidth(int value)](#setWidth-int-) | Setzt die Seitenvorschaubreite. |
|
|  | [getHeight()](#getHeight--) | Liefert die Seitenvorschauhöhe. |
|
|  | [setHeight(int value)](#setHeight-int-) | Setzt die Seitenvorschauhöhe. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Liefert ein Array von Seitenzahlen, für die Vorschauen erzeugt werden. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Setzt ein Array von Seitenzahlen, für die Vorschauen erzeugt werden. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Liefert das Vorschaubildformat. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Setzt das Vorschaubildformat. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Liefert eine Instanz der Seitenstrom-Erstellungsklasse. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Setzt eine Instanz der Seitenstrom-Erstellungsklasse. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Liefert eine Instanz der Seitenvorschau-Abschlussklasse. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Setzt eine Instanz der Seitenvorschau-Abschlussklasse. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` Klasse, die den Ausgabestream schließt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz der `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` Klasse, wodurch der Ausgabestream dem Client für weitere Verwendung zurückgegeben wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Benachrichtigt, dass die Erstellung der Seitenvorschau abgeschlossen ist, und gibt den Ausgabestream zurück. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Liefert die Seitenvorschaubreite.


**Returns:**
int - Die Seitenvorschaubreite.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Setzt die Seitenvorschaubreite.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Seitenvorschaubreite. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liefert die Seitenvorschauhöhe.


**Returns:**
int - Die Seitenvorschauhöhe.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Setzt die Seitenvorschauhöhe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Seitenvorschauhöhe. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Liefert ein Array von Seitenzahlen, für die Vorschauen erzeugt werden.


**Returns:**
int[] - Das Array von Seitenzahlen, für die Vorschauen erzeugt werden.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Setzt ein Array von Seitenzahlen, für die Vorschauen erzeugt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Das Array von Seitenzahlen, für die Vorschauen erzeugt werden. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Liefert das Vorschaubildformat.


**Returns:**
int - Das Vorschaubildformat.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Setzt das Vorschaubildformat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Das Vorschaubildformat. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Liefert eine Instanz der Seitenstrom-Erstellungsklasse.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Setzt eine Instanz der Seitenstrom-Erstellungsklasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Die Instanz der Seitenstrom-Erstellungsklasse. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Liefert eine Instanz der Seitenvorschau-Abschlussklasse.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Setzt eine Instanz der Seitenvorschau-Abschlussklasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Die Instanz des Delegaten für die Fertigstellung der Seitenvorschau. |
|

