---
title: "従量制"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "メータードライセンスでコンポーネントをライセンスするメソッドを提供します。"
type: docs
weight: 1690
url: /ja/net/groupdocs.watermark/metered/
---
## Metered class

メータードライセンスでコンポーネントをライセンスするメソッドを提供します。

```csharp
public class Metered
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Metered](metered)() | [`Metered`](../metered) クラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | 従量制キーで製品を有効化します。 |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | 消費されたクレジット数を取得します。 |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | 処理された MB の量を取得します。 |

### 備考

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### 例

以下の例は、従量制キーで製品を有効化する方法を示しています。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### 関連項目

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
