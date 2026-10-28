---
title: "PdfAttachment"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine an einen PDF-Inhalt angehängte Datei dar."
type: docs
weight: 58
url: /de/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

Stellt eine an einen PDF-Inhalt angehängte Datei dar.

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Ermittelt den Namen der angehängten Datei. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Legt den Namen der angehängten Datei fest. |
|
|  | [getDescription()](#getDescription--) | Ruft die Beschreibung der angehängten Datei ab. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | Legt die Beschreibung der angehängten Datei fest. |
|
|  | [getContent()](#getContent--) | Liest den Inhalt der angehängten Datei. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Setzt den Inhalt der angehängten Datei. |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


Ermittelt den Namen der angehängten Datei.


**Returns:**
java.lang.String - Der Name der angehängten Datei.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Legt den Namen der angehängten Datei fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Name der angehängten Datei. |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Ruft die Beschreibung der angehängten Datei ab.


**Returns:**
java.lang.String - Die Beschreibung der angehängten Datei.

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Legt die Beschreibung der angehängten Datei fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Die Beschreibung der angehängten Datei. |
|

### getContent() {#getContent--}
```
public byte[] getContent()
```


Liest den Inhalt der angehängten Datei.


**Returns:**
byte[] - Der Inhalt der angehängten Datei.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Setzt den Inhalt der angehängten Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte[] | Der Inhalt der angehängten Datei. |
|

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Aktualisiert die angehängte Datei aus einem Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Liest einen Stream aus der angehängten Datei.


**Returns:**
com.aspose.ms.System.IO.Stream
