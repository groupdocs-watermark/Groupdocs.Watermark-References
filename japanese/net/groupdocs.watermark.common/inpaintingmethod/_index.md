---
title: "InpaintingMethod"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "画像インペインティングに使用されるアルゴリズムを指定します。"
type: docs
weight: 80
url: /ja/net/groupdocs.watermark.common/inpaintingmethod/
---
## InpaintingMethod enumeration

画像インペインティングに使用されるアルゴリズムを指定します。

```csharp
public enum InpaintingMethod
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PatchBased | `0` | パッチベースのインペインティング（Criminisi スタイル）。既知領域で類似したテクスチャパッチを見つけ、マスクにコピーします。 |
| Telea | `1` | Telea アルゴリズム。領域境界から内部へピクセル値を伝搬させる高速マーチング手法です。 |

### 関連項目

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
