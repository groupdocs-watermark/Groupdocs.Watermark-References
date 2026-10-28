---
title: "SpreadsheetAttachmentCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di allegati in un documento Excel."
type: docs
weight: 102
url: /it/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Rappresenta una raccolta di allegati in un documento Excel.

Questa collezione contiene gli elementi di tipo `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Aggiunge un allegato al `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Aggiunge un allegato tramite un collegamento (il documento non conterrà il contenuto del file allegato). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Aggiunge un allegato al `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileContent | byte[] | Il contenuto del file da allegare. |
|
|  | sourceFullName | java.lang.String | Il nome completo del file allegato (l'estensione è usata per determinare l'applicazione appropriata per aprire il file). |
|
|  | previewImageContent | byte[] | L'immagine di anteprima del file allegato come array di byte. |
|
|  | x | double | La coordinata x del riquadro dell'allegato (in punti). |
|
|  | y | double | La coordinata y del riquadro dell'allegato (in punti). |
|
|  | larghezza | double | La larghezza del frame di allegato in punti. |
|
|  | altezza | double | L'altezza del frame di allegato in punti. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Aggiunge un allegato tramite un collegamento (il documento non conterrà il contenuto del file allegato).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Il percorso del file collegato. |
|
|  | previewImageContent | byte[] | L'immagine di anteprima del file allegato come array di byte. |
|
|  | x | double | La coordinata x del riquadro dell'allegato (in punti). |
|
|  | y | double | La coordinata y del riquadro dell'allegato (in punti). |
|
|  | larghezza | double | La larghezza del frame di allegato in punti. |
|
|  | altezza | double | L'altezza del frame di allegato in punti. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

