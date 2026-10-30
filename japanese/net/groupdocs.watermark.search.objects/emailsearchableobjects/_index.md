---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かし検索に含めるメールメッセージオブジェクトを表すフラグを指定します。"
type: docs
weight: 2520
url: /ja/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

透かし検索に含めるメールメッセージオブジェクトを表すフラグを指定します。

```csharp
[Flags]
public enum EmailSearchableObjects
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | 検索対象オブジェクトがないことを指定します。 |
| Subject | `1` | メッセージの件名内を検索します。 |
| PlainTextBody | `2` | メッセージのプレーンテキスト本文内を検索します。 |
| HtmlBody | `4` | メッセージの HTML 本文内を検索します。 |
| AttachedImages | `8` | 添付画像内を検索します。 |
| EmbeddedImages | `10` | 埋め込み画像内を検索します。 |
| All | `1F` | すべてのメールオブジェクト内を検索します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
