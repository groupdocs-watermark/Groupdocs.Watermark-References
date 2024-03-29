---
title: ReleasePageStream
second_title: .NET API 参考的 GroupDocs.Watermark
description: 表示释放由创建的流的方法CreatePageStream./createpagestream代表.
type: docs
weight: 2090
url: /zh/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

表示释放由创建的流的方法[`CreatePageStream`](../createpagestream)代表.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 生成的页面预览的页码。 |
| pageStream | Stream | 包含生成的页面预览的流。 |

### 也可以看看

* 命名空间 [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* 部件 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
