---
title: "PresentationFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PowerPoint ドキュメント内の書式設定されたテキスト断片のコレクションを表します。"
type: docs
weight: 920
url: /ja/net/groupdocs.watermark.contents.presentation/presentationformattedtextfragmentcollection/
---
## PresentationFormattedTextFragmentCollection class

PowerPoint ドキュメント内の書式設定されたテキスト断片のコレクションを表します。

```csharp
public class PresentationFormattedTextFragmentCollection : FormattedTextFragmentCollection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CollectionType](../../groupdocs.watermark.search/formattedtextfragmentcollection/collectiontype) { get; } | 書式設定フラグメントコレクションのタイプを取得します。 |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | コレクションに含まれる要素数を取得します。 |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | コレクション内の指定インデックスにある要素を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string) | 書式設定テキストフラグメントをコレクションに追加します。 |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font) | 書式設定テキストフラグメントをコレクションに追加します。 |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color) | 書式設定テキストフラグメントをコレクションに追加します。 |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color, Color) | 書式設定テキストフラグメントをコレクションに追加します。 |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(FormattedTextFragment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(FormattedTextFragment) |  |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string) | 指定されたインデックスで書式設定テキストフラグメントをコレクションに挿入します。 |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font) | 指定されたインデックスで書式設定テキストフラグメントをコレクションに挿入します。 |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color) | 指定されたインデックスで書式設定テキストフラグメントをコレクションに挿入します。 |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color, Color) | 指定されたインデックスで書式設定テキストフラグメントをコレクションに挿入します。 |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(FormattedTextFragment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 備考

このコレクションには、[`PresentationFormattedTextFragment`](../presentationformattedtextfragment) 型の項目が含まれます。

### 関連項目

* class [FormattedTextFragmentCollection](../../groupdocs.watermark.search/formattedtextfragmentcollection)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
