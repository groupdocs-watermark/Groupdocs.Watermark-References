---
title: "FromExtension"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "将文件扩展名映射到文件类型。"
type: docs
weight: 590
url: /zh/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

将文件扩展名映射到文件类型。

```csharp
public static FileType FromExtension(string extension)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| extension | String | 文件扩展名（包括句点 “.”）。 |

### 返回值

当文件类型受支持时返回它，否则返回默认的 [`Unknown`](../unknown) 文件类型。

### Exceptions

| exception | 条件 |
| --- | --- |
| ArgumentException | 当 *extension* 为 null 或空字符串时抛出。 |

### 另请参阅

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
