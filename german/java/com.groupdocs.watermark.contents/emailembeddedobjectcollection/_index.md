---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von eingebetteten Objekten in einer E-Mail-Nachricht dar."
type: docs
weight: 36
url: /de/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Stellt eine Sammlung von eingebetteten Objekten in einer E-Mail-Nachricht dar.

Diese Sammlung enthält Elemente des Typs `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Fügt eine eingebettete Ressource zum `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` hinzu. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Fügt eine eingebettete Ressource zum `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileContent | byte[] | Der Inhalt der hinzuzufügenden Datei. |
|
|  | name | java.lang.String | Der Name der Datei. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

