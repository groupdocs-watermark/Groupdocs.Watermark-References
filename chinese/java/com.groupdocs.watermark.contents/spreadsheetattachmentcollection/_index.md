---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Excel 文档中附件的集合。"
type: docs
weight: 102
url: /zh/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

表示 Excel 文档中附件的集合。

此集合包含 `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)` 类型的项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | 向 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 添加附件。 |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | 通过链接添加附件（文档将不包含附件文件内容）。 |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


向 `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` 添加附件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileContent | byte[] | 要附加的文件内容。 |
|
|  | sourceFullName | java.lang.String | 附件文件的完整名称（扩展名用于确定打开文件的合适应用程序）。 |
|
|  | previewImageContent | byte[] | 附件文件的预览图像，字节数组形式。 |
|
|  | x | double | 附件框架的 x 坐标（单位为点）。 |
|
|  | y | double | 附件框架的 y 坐标（单位为点）。 |
|
|  | 宽度 | double | 附件框架的宽度（单位：点）。 |
|
|  | 高度 | double | 附件框架的高度（单位：点）。 |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


通过链接添加附件（文档将不包含附件文件内容）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | 链接的文件路径。 |
|
|  | previewImageContent | byte[] | 附件文件的预览图像，字节数组形式。 |
|
|  | x | double | 附件框架的 x 坐标（单位为点）。 |
|
|  | y | double | 附件框架的 y 坐标（单位为点）。 |
|
|  | 宽度 | double | 附件框架的宽度（单位：点）。 |
|
|  | 高度 | double | 附件框架的高度（单位：点）。 |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

