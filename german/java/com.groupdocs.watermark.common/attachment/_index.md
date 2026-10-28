---
title: "Attachment"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine an ein Dokument angehängte Datei dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Stellt eine an ein Dokument angehängte Datei dar.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Gibt die Informationen über ein im angehängten Dokument gespeichertes Dokument zurück. |
|
|  | [getContent()](#getContent--) | Liest den Inhalt der angehängten Datei. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Setzt den Inhalt der angehängten Datei. |
|
|  | [createWatermarker()](#createWatermarker--) | Lädt einen Inhalt aus der angehängten Datei. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen und Einstellungen. |
|
|  | [getContentStream()](#getContentStream--) | Liest einen Stream aus der angehängten Datei. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Aktualisiert die angehängte Datei aus einem Stream. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Aktualisiert den angehängten Inhalt. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gibt die Informationen über ein im angehängten Dokument gespeichertes Dokument zurück.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Liest den Inhalt der angehängten Datei.


**Returns:**
byte[] - Der Inhalt der angehängten Datei.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Setzt den Inhalt der angehängten Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte[] | Der Inhalt der angehängten Datei. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Lädt einen Inhalt aus der angehängten Datei.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Zusätzliche Optionen, die beim Laden eines Anhangs verwendet werden. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen und Einstellungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Zusätzliche Optionen, die beim Laden eines Anhangs verwendet werden. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Liest einen Stream aus der angehängten Datei.


**Returns:**
com.aspose.ms.System.IO.Stream - Der Stream, aus dem der Dateiinhalte gelesen wird.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Aktualisiert die angehängte Datei aus einem Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Der Stream, aus dem die angehängte Datei aktualisiert wird. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Aktualisiert den angehängten Inhalt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | Die aktualisierte Version des Inhalts. |
|

