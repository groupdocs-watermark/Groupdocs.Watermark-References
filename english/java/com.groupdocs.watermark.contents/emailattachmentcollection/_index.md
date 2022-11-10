---
title: EmailAttachmentCollection
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a collection of attachments in an email message.
type: docs
weight: 32
url: /java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Represents a collection of attachments in an email message.

This collection contains the items of `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)` type.
## Methods

| Method | Description |
| --- | --- |
| [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Adds an attachment to the `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
| [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) |  |
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Adds an attachment to the `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileContent | byte[] | The content of the file to be attached. |
| name | java.lang.String | The name of the file. |

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

