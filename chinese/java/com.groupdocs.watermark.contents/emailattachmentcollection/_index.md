---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示电子邮件消息中附件的集合。"
type: docs
weight: 32
url: /zh/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

表示电子邮件消息中附件的集合。

此集合包含 `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)` 类型的项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | 向 `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` 添加附件。 |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


向 `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` 添加附件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileContent | byte[] | 要附加的文件内容。 |
|
|  | name | java.lang.String | 文件的名称。 |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

