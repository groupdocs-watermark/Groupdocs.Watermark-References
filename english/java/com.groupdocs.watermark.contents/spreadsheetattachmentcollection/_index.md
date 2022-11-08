---
title: SpreadsheetAttachmentCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a collection of attachments in an Excel document.
type: docs
weight: 102
url: /java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Represents a collection of attachments in an Excel document.

This collection contains the items of `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)` type.
## Methods

| Method | Description |
| --- | --- |
| [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Adds an attachment to the `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
| [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Adds an attachment by a link (the document will not contain attached file content). |
| [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) |  |
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Adds an attachment to the `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileContent | byte[] | The content of the file to be attached. |
| sourceFullName | java.lang.String | The full name of the attached file (The extension is used to determine appropriate application to open the file). |
| previewImageContent | byte[] | The attached file preview image as a byte array. |
| x | double | The x-coordinate of the attachment frame (in points). |
| y | double | The y-coordinate of the attachment frame (in points). |
| width | double | The width of the attachment frame in points. |
| height | double | The height of the attachment frame in points. |

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Adds an attachment by a link (the document will not contain attached file content).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFullName | java.lang.String | The linked file path. |
| previewImageContent | byte[] | The attached file preview image as a byte array. |
| x | double | The x-coordinate of the attachment frame (in points). |
| y | double | The y-coordinate of the attachment frame (in points). |
| width | double | The width of the attachment frame in points. |
| height | double | The height of the attachment frame in points. |

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

