---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示一个方法，该方法释放由 CreatePageStream./createpagestream 委托创建的流。"
type: docs
weight: 2160
url: /zh/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

表示一个方法，该方法释放由 [`CreatePageStream`](../createpagestream) 委托创建的流。

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 生成的页面预览的页码。 |
| pageStream | Stream | 包含生成的页面预览的流。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
