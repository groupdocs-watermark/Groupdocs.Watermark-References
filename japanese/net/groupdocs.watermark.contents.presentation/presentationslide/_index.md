---
title: "PresentationSlide"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PowerPoint ドキュメントのスライドを表します。"
type: docs
weight: 1060
url: /ja/net/groupdocs.watermark.contents.presentation/presentationslide/
---
## PresentationSlide class

PowerPoint ドキュメントのスライドを表します。

```csharp
public class PresentationSlide : PresentationBaseSlide
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Charts](../../groupdocs.watermark.contents.presentation/presentationbaseslide/charts) { get; } | プレゼンテーション上のすべてのチャートのコレクションを取得します。 |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseslide/imagefillformat) { get; } | プレゼンテーションの画像塗りつぶし形式設定を取得します。 |
| [LayoutSlide](../../groupdocs.watermark.contents.presentation/presentationslide/layoutslide) { get; } | この[`PresentationSlide`](../presentationslide) のレイアウトスライドを取得します。 |
| [MasterSlide](../../groupdocs.watermark.contents.presentation/presentationslide/masterslide) { get; } | この[`PresentationSlide`](../presentationslide) のマスタースライドを取得します。 |
| [NotesSlide](../../groupdocs.watermark.contents.presentation/presentationslide/notesslide) { get; } | この[`PresentationSlide`](../presentationslide) のノートスライドを取得します。 |
| [Shapes](../../groupdocs.watermark.contents.presentation/presentationbaseslide/shapes) { get; } | プレゼンテーションのすべてのシェイプのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 関連項目

* class [PresentationBaseSlide](../presentationbaseslide)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
