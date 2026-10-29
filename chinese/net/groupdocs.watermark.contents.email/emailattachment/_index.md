---
title: "EmailAttachment"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示附加到电子邮件消息的文件。"
type: docs
weight: 320
url: /zh/net/groupdocs.watermark.contents.email/emailattachment/
---
## EmailAttachment class

表示附加到电子邮件消息的文件。

```csharp
public class EmailAttachment : EmailAttachmentBase
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | 获取或设置附件文件内容。 |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | 获取此 [`EmailAttachmentBase`](../emailattachmentbase) 的内容 ID。 |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | 获取此 [`EmailAttachmentBase`](../emailattachmentbase) 的媒体类型。 |
| [Name](../../groupdocs.watermark.contents.email/emailattachment/name) { get; set; } | 获取或设置附件文件的名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | 从附件文件加载内容。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | 使用指定的加载选项从附件文件加载内容。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | 使用指定的加载选项和设置从附件文件加载内容。 |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | 获取存储在附件文件中的文档信息。 |

### 另请参阅

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
