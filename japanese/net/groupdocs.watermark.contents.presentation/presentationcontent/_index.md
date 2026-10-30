---
title: "PresentationContent"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かしを配置できる PowerPoint ドキュメントを表します。"
type: docs
weight: 900
url: /ja/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

透かしを配置できる PowerPoint ドキュメントを表します。

```csharp
public class PresentationContent : Content
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | この [`PresentationContent`](../presentationcontent) のすべてのレイアウトスライドのコレクションを取得します。 |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | この [`PresentationContent`](../presentationcontent) のマスターハンドアウトスライドを取得します。 |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | この [`PresentationContent`](../presentationcontent) のすべてのノートスライドのマスタースライドを取得します。 |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | この [`PresentationContent`](../presentationcontent) のすべてのマスタースライドのコレクションを取得します。 |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | ノートスライドの高さをポイント単位で取得します。 |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | ノートスライドの幅をポイント単位で取得します。 |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | スライドの高さをポイント単位で取得します。 |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | この [`PresentationContent`](../presentationcontent) のすべてのスライドのコレクションを取得します。 |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | スライドの幅をポイント単位で取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | ドキュメントを復号化します。 |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 現在のインスタンスを破棄します。 |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | ドキュメントを暗号化します。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 備考

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### 例

サポートされている任意のタイプの PowerPoint ドキュメントを読み込みおよび保存します。

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // Add メソッドを使用して、特定のスライドまたはすべてのスライドに透かしを追加します。

    // 変更を保存します。
    watermarker.Save(@"D:\output.ppt");
}
```

### 関連項目

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
