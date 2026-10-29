---
title: "修复方法"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "指定用于图像修复的算法。"
type: docs
weight: 80
url: /zh/net/groupdocs.watermark.common/inpaintingmethod/
---
## InpaintingMethod enumeration

指定用于图像修复的算法。

```csharp
public enum InpaintingMethod
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PatchBased | `0` | 基于补丁的修复（Criminisi 风格）。在已知区域中查找相似的纹理补丁并将其复制到掩码中。 |
| Telea | `1` | Telea 算法。快速行进方法，将像素值从区域边界向内部传播。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
