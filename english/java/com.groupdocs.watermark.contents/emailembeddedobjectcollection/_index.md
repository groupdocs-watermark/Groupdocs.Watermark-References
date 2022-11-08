---
title: EmailEmbeddedObjectCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a collection of embedded objects in an email message.
type: docs
weight: 36
url: /java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Represents a collection of embedded objects in an email message.

This collection contains the items of `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)` type.
## Methods

| Method | Description |
| --- | --- |
| [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Adds an embedded resource to the `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
| [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) |  |
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Adds an embedded resource to the `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileContent | byte[] | The content of the file to be added. |
| name | java.lang.String | The name of the file. |

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

