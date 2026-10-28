---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示电子邮件中嵌入对象的集合。"
type: docs
weight: 36
url: /zh/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

表示电子邮件中嵌入对象的集合。

此集合包含 `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)` 类型的项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | 向 `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` 添加嵌入资源。 |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


向 `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` 添加嵌入资源。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileContent | byte[] | 要添加的文件内容。 |
|
|  | name | java.lang.String | 文件的名称。 |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

