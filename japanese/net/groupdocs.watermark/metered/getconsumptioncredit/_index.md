---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "消費されたクレジット数を取得します。"
type: docs
weight: 30
url: /ja/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

消費されたクレジット数を取得します。

```csharp
public static long GetConsumptionCredit()
```

### 戻り値

消費されたクレジットの数です。

### 例

以下の例は、消費されたクレジット数の取得方法を示しています。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### 関連項目

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
