---
title: "EmailEmbeddedObjectCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di oggetti incorporati in un messaggio email."
type: docs
weight: 36
url: /it/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Rappresenta una raccolta di oggetti incorporati in un messaggio email.

Questa collezione contiene gli elementi di tipo `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Aggiunge una risorsa incorporata a `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Aggiunge una risorsa incorporata a `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileContent | byte[] | Il contenuto del file da aggiungere. |
|
|  | name | java.lang.String | Il nome del file. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

