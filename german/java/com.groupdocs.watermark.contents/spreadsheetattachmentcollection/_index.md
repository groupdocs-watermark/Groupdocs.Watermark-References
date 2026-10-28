---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von Anhängen in einem Excel-Dokument dar."
type: docs
weight: 102
url: /de/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Stellt eine Sammlung von Anhängen in einem Excel-Dokument dar.

Diese Sammlung enthält die Elemente des Typs `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Fügt dem `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` einen Anhang hinzu. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Fügt einen Anhang über einen Link hinzu (das Dokument enthält nicht den Inhalt der angehängten Datei). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Fügt dem `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` einen Anhang hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileContent | byte[] | Der Inhalt der anzuhängenden Datei. |
|
|  | sourceFullName | java.lang.String | Der vollständige Name der angehängten Datei (die Erweiterung wird verwendet, um die geeignete Anwendung zum Öffnen der Datei zu bestimmen). |
|
|  | previewImageContent | byte[] | Das Vorschaubild der angehängten Datei als Byte-Array. |
|
|  | x | double | Die x-Koordinate des Anhangrahmens (in Punkten). |
|
|  | y | double | Die y-Koordinate des Anhangrahmens (in Punkten). |
|
|  | Breite | double | Die Breite des Anhangrahmens in Punkten. |
|
|  | Höhe | double | Die Höhe des Anhangrahmens in Punkten. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Fügt einen Anhang über einen Link hinzu (das Dokument enthält nicht den Inhalt der angehängten Datei).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Der Pfad der verknüpften Datei. |
|
|  | previewImageContent | byte[] | Das Vorschaubild der angehängten Datei als Byte-Array. |
|
|  | x | double | Die x-Koordinate des Anhangrahmens (in Punkten). |
|
|  | y | double | Die y-Koordinate des Anhangrahmens (in Punkten). |
|
|  | Breite | double | Die Breite des Anhangrahmens in Punkten. |
|
|  | Höhe | double | Die Höhe des Anhangrahmens in Punkten. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

