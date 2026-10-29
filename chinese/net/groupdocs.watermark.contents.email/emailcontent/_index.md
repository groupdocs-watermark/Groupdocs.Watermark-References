---
title: "EmailContent"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示电子邮件消息。"
type: docs
weight: 360
url: /zh/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

表示电子邮件消息。

```csharp
public sealed class EmailContent : Content
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | 获取电子邮件消息的所有附件集合。 |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | 获取电子邮件消息的密件抄送（BCC）收件人集合。 |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | 获取或设置消息正文的纯文本表示。 |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | 获取电子邮件消息正文的类型。 |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | 获取电子邮件消息的抄送 (CC) 收件人集合。 |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | 获取电子邮件消息中所有嵌入对象的集合。 |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | 获取电子邮件消息的发件人地址。 |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | 获取或设置消息正文的 HTML 表示。 |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | 获取或设置电子邮件消息的主题。 |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | 获取电子邮件消息的收件人集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 释放当前实例。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 备注

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### 另请参阅

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
