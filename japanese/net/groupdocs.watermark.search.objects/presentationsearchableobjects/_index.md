---
title: "PresentationSearchableObjects"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かし検索に含める PowerPoint コンテンツオブジェクトを表すフラグを指定します。"
type: docs
weight: 2540
url: /ja/net/groupdocs.watermark.search.objects/presentationsearchableobjects/
---
## PresentationSearchableObjects enumeration

透かし検索に含める PowerPoint コンテンツオブジェクトを表すフラグを指定します。

```csharp
[Flags]
public enum PresentationSearchableObjects
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | 検索対象オブジェクトがないことを指定します。 |
| Shapes | `1` | シェイプ内を検索します。 |
| ChartsBackgrounds | `2` | チャートの背景内を検索します。 |
| SlidesBackgrounds | `4` | スライドの背景内を検索します。 |
| Hyperlinks | `8` | ハイパーリンク内を検索します。 |
| All | `F` | すべてのコンテンツオブジェクト内を検索します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
