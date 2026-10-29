---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "初始化 EmailPreviewOptionsgroupdocs.watermark.options.email/emailpreviewoptions 类的新实例，并导致输出流被关闭。"
type: docs
weight: 10
url: /zh/net/groupdocs.watermark.options.email/emailpreviewoptions/emailpreviewoptions/
---
## EmailPreviewOptions(CreatePageStream) {#constructor}

初始化 [`EmailPreviewOptions`](../../emailpreviewoptions) 类的新实例，并导致输出流被关闭。

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 为特定页面预览创建流。 |

### 另请参阅

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

---

## EmailPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

初始化 [`EmailPreviewOptions`](../../emailpreviewoptions) 类的新实例，使输出流返回给客户端以供进一步使用。

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 为特定页面预览创建流。 |
| releasePageStream | ReleasePageStream | 通知页面预览生成已完成并获取输出流。 |

### 另请参阅

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
