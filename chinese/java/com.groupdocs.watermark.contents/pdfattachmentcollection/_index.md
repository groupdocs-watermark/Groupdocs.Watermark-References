---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PDF 文档中附件的集合。"
type: docs
weight: 59
url: /zh/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

表示 PDF 文档中附件的集合。

此集合包含类型为 `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)` 的项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | 向 `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` 添加附件。 |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


向 `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` 添加附件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileContent | byte[] | 要附加的文件内容。 |
|
|  | name | java.lang.String | 文件的名称。 |
|
|  | description | java.lang.String | 文件的描述。 |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

