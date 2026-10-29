---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "指定表示要包含在水印搜索中的 pdf 内容对象的标志。"
type: docs
weight: 2530
url: /zh/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

指定表示要包含在水印搜索中的 pdf 内容对象的标志。

```csharp
[Flags]
public enum PdfSearchableObjects
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 指定没有搜索对象。 |
| XObjects | `1` | 在 XObjects 中搜索。 |
| Artifacts | `2` | 在工件中搜索。 |
| Annotations | `4` | 在批注中搜索。 |
| Text | `8` | 在内容文本中搜索。 |
| Hyperlinks | `10` | 在超链接中搜索。 |
| AttachedImages | `20` | 在附件图像中搜索。 |
| Vector | `40` | 在运算符中搜索。 |
| All | `7F` | 在所有内容对象中搜索。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
