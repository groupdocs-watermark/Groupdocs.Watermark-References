---
title: PdfSearchableObjects
second_title: GroupDocs.Watermark for .NET API リファレンス
description: 透かし検索に含まれる PDF コンテンツ オブジェクトを表すフラグを指定します
type: docs
weight: 2490
url: /ja/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

透かし検索に含まれる PDF コンテンツ オブジェクトを表すフラグを指定します。

```csharp
[Flags]
public enum PdfSearchableObjects
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| None | `0` | 検索オブジェクトを指定しません。 |
| XObjects | `1` | XObjects. で検索 |
| Artifacts | `2` | 成果物を検索します。 |
| Annotations | `4` | 注釈で検索. |
| Text | `8` | コンテンツ テキストで検索します。 |
| Hyperlinks | `10` | ハイパーリンクで検索. |
| AttachedImages | `20` | 添付画像で検索. |
| All | `3F` | すべてのコンテンツ オブジェクトを検索します。 |

### 関連項目

* 名前空間 [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* 組み立て [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
