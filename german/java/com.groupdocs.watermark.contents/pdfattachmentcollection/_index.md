---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von Anhängen in einem PDF-Dokument dar."
type: docs
weight: 59
url: /de/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Stellt eine Sammlung von Anhängen in einem PDF-Dokument dar.

Diese Sammlung enthält die Elemente des Typs `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Fügt dem `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` einen Anhang hinzu. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Fügt dem `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` einen Anhang hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileContent | byte[] | Der Inhalt der anzuhängenden Datei. |
|
|  | name | java.lang.String | Der Name der Datei. |
|
|  | description | java.lang.String | Die Beschreibung der Datei. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

