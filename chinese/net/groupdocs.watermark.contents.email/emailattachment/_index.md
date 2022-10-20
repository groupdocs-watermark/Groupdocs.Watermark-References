---
title: EmailAttachment
second_title: .NET API 参考的 GroupDocs.Watermark
description: 表示附加到电子邮件的文件
type: docs
weight: 290
url: /zh/net/groupdocs.watermark.contents.email/emailattachment/
---
## EmailAttachment class

表示附加到电子邮件的文件。

```csharp
public class EmailAttachment : EmailAttachmentBase
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | 获取或设置附件内容。 |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | 获取此内容的 id[`EmailAttachmentBase`](../emailattachmentbase). |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | 获取这个的媒体类型[`EmailAttachmentBase`](../emailattachmentbase). |
| [Name](../../groupdocs.watermark.contents.email/emailattachment/name) { get; set; } | 获取或设置附加文件的名称。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | 从附件加载内容。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | 使用指定的加载选项从附件加载内容。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | 使用指定的加载选项和设置从附件加载内容。 |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | 获取有关存储在附件中的文档的信息。 |

### 也可以看看

* class [EmailAttachmentBase](../emailattachmentbase)
* 命名空间 [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* 部件 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->