---
title: "SpreadsheetSearchableObjects"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かし検索に含める Excel コンテンツオブジェクトを表すフラグを指定します。"
type: docs
weight: 2560
url: /ja/net/groupdocs.watermark.search.objects/spreadsheetsearchableobjects/
---
## SpreadsheetSearchableObjects enumeration

透かし検索に含める Excel コンテンツオブジェクトを表すフラグを指定します。

```csharp
[Flags]
public enum SpreadsheetSearchableObjects
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | 検索対象オブジェクトがないことを指定します。 |
| Shapes | `1` | シェイプ内を検索します。 |
| ChartsBackgrounds | `2` | チャートの背景内を検索します。 |
| HeadersFooters | `4` | ヘッダーとフッター内を検索します。 |
| WorksheetBackgrounds | `8` | ワークシートの背景内を検索します。 |
| Cells | `10` | セル内を検索します。 |
| Hyperlinks | `20` | ハイパーリンク内を検索します。 |
| AttachedImages | `40` | 添付画像内を検索します。 |
| All | `7F` | すべてのコンテンツオブジェクト内を検索します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
