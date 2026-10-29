---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "检索已处理的 MB 数量。"
type: docs
weight: 40
url: /zh/net/groupdocs.watermark/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

检索已处理的 MB 数量。

```csharp
public static decimal GetConsumptionQuantity()
```

### 返回值

已处理的 MB 数量。

### 示例

以下示例演示如何检索已处理的 MB 数量。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### 另请参阅

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
