---
title: PdfAttachmentCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a collection of attachments in a pdf document.
type: docs
weight: 59
url: /java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Represents a collection of attachments in a pdf document.

This collection contains the items of `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)` type.
## Methods

| Method | Description |
| --- | --- |
| [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Adds an attachment to the `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
| [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) |  |
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Adds an attachment to the `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileContent | byte[] | The content of the file to be attached. |
| name | java.lang.String | The name of the file. |
| description | java.lang.String | The description of the file. |

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

