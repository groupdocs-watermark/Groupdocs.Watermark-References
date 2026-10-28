---
title: "PdfAttachmentCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di allegati in un documento PDF."
type: docs
weight: 59
url: /it/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Rappresenta una raccolta di allegati in un documento PDF.

Questa collezione contiene gli elementi di tipo `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Aggiunge un allegato al `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Aggiunge un allegato al `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileContent | byte[] | Il contenuto del file da allegare. |
|
|  | name | java.lang.String | Il nome del file. |
|
|  | description | java.lang.String | La descrizione del file. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

