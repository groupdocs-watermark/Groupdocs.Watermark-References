---
title: "计量"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "提供使用计量授权对组件进行授权的方法。"
type: docs
weight: 1690
url: /zh/net/groupdocs.watermark/metered/
---
## Metered class

提供使用计量授权对组件进行授权的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered)() | 初始化 [`Metered`](../metered) 类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | 使用计量密钥激活产品。 |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | 检索已消耗的积分数量。 |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | 检索已处理的 MB 数量。 |

### 备注

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### 示例

以下示例演示如何使用计量密钥激活产品。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### 另请参阅

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
