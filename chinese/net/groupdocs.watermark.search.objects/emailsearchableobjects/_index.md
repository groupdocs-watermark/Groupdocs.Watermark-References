---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "指定表示要包含在水印搜索中的电子邮件消息对象的标志。"
type: docs
weight: 2520
url: /zh/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

指定表示要包含在水印搜索中的电子邮件消息对象的标志。

```csharp
[Flags]
public enum EmailSearchableObjects
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 指定没有搜索对象。 |
| Subject | `1` | 在邮件主题中搜索。 |
| PlainTextBody | `2` | 在邮件纯文本正文中搜索。 |
| HtmlBody | `4` | 在邮件 HTML 正文中搜索。 |
| AttachedImages | `8` | 在附件图像中搜索。 |
| EmbeddedImages | `10` | 在嵌入图像中搜索。 |
| All | `1F` | 在所有邮件对象中搜索。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
