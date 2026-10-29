---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "初始化 PreviewOptionsgroupdocs.watermark.options/previewoptions 类的新实例，使输出流被关闭。"
type: docs
weight: 10
url: /zh/net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例，使输出流被关闭。

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 为特定页面预览创建流。 |

### 另请参阅

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例，使输出流返回给客户端以供进一步使用。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 为特定页面预览创建流。 |
| releasePageStream | ReleasePageStream | 通知页面预览生成已完成并获取输出流。 |

### 另请参阅

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
