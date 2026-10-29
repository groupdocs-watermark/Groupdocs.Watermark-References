---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "检索已消耗的积分数量。"
type: docs
weight: 30
url: /zh/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

检索已消耗的积分数量。

```csharp
public static long GetConsumptionCredit()
```

### 返回值

已消耗的积分数量。

### 示例

以下示例演示如何检索已消耗的积分数量。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### 另请参阅

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
