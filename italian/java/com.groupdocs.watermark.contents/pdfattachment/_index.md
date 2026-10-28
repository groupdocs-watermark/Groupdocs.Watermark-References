---
title: "PdfAttachment"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un file allegato a un contenuto PDF."
type: docs
weight: 58
url: /it/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

Rappresenta un file allegato a un contenuto PDF.

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Restituisce il nome del file allegato. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Imposta il nome del file allegato. |
|
|  | [getDescription()](#getDescription--) | Ottiene la descrizione del file allegato. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | Imposta la descrizione del file allegato. |
|
|  | [getContent()](#getContent--) | Ottiene il contenuto del file allegato. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Imposta il contenuto del file allegato. |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome del file allegato.


**Returns:**
java.lang.String - Il nome del file allegato.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Imposta il nome del file allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome del file allegato. |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Ottiene la descrizione del file allegato.


**Returns:**
java.lang.String - La descrizione del file allegato.

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Imposta la descrizione del file allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La descrizione del file allegato. |
|

### getContent() {#getContent--}
```
public byte[] getContent()
```


Ottiene il contenuto del file allegato.


**Returns:**
byte[] - Il contenuto del file allegato.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Imposta il contenuto del file allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte[] | Il contenuto del file allegato. |
|

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Aggiorna il file allegato da uno stream.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Ottiene uno stream dal file allegato.


**Returns:**
com.aspose.ms.System.IO.Stream
