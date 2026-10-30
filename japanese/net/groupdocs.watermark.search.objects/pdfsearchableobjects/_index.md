---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かし検索に含める pdf コンテンツオブジェクトを表すフラグを指定します。"
type: docs
weight: 2530
url: /ja/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

透かし検索に含める pdf コンテンツオブジェクトを表すフラグを指定します。

```csharp
[Flags]
public enum PdfSearchableObjects
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | 検索対象オブジェクトがないことを指定します。 |
| XObjects | `1` | XObjects 内を検索します。 |
| Artifacts | `2` | アーティファクト内を検索します。 |
| Annotations | `4` | 注釈内を検索します。 |
| Text | `8` | コンテンツテキスト内を検索します。 |
| Hyperlinks | `10` | ハイパーリンク内を検索します。 |
| AttachedImages | `20` | 添付画像内を検索します。 |
| Vector | `40` | 演算子内を検索します。 |
| All | `7F` | すべてのコンテンツオブジェクト内を検索します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
