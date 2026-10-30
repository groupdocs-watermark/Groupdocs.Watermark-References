---
title: "ウォーターマーカー"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ドキュメント内の透かし管理用クラスを表します。"
type: docs
weight: 3140
url: /ja/net/groupdocs.watermark/watermarker/
---
## Watermarker class

ドキュメント内の透かし管理用クラスを表します。

```csharp
public class Watermarker : IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | 指定されたストリームで、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |
| [Watermarker](watermarker#constructor_4)(string) | 指定されたドキュメントパスで、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | 指定されたストリームとロードオプションで、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | 指定されたストリームと設定で、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | 指定されたドキュメントパスとロードオプションで、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | 指定されたドキュメントパスと設定で、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | 指定されたストリーム、ロードオプション、設定で、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | 指定されたドキュメントパス、ロードオプション、設定で、[`Watermarker`](../watermarker) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | 透かし検索に含めるコンテンツオブジェクトを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | 読み込まれたドキュメントに透かしを追加します。 |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | 透かしオプションを使用して、読み込まれたドキュメントに透かしを追加します。 |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | 現在のインスタンスを破棄します。 |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | ドキュメントのプレビュー画像を生成します。 |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | 読み込まれたドキュメントの [`Content`](../../groupdocs.watermark.contents/content) オブジェクトを返します。 |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | 読み込まれたドキュメントの形式に関する情報を取得します。 |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | ドキュメント内のすべての画像を検索します。 |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。 |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | ドキュメントから透かしを削除します。 |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | コレクション内のすべての透かしをドキュメントから削除します。 |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | ドキュメントデータを基になるストリームに保存します。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | 保存オプションを使用して、ドキュメントデータを基になるストリームに保存します。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | ドキュメントを指定されたストリームに保存します。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | ドキュメントを指定されたファイルの場所に保存します。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | 保存オプションを使用して、ドキュメントを指定されたストリームに保存します。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | 保存オプションを使用して、ドキュメントを指定されたファイルの場所に保存します。 |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | ドキュメント内のすべての可能な透かしを検索します。 |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | 指定された検索基準に従って、可能な透かしを検索します。 |

### 例

任意のサポートされている形式のコンテンツを読み込み、保存します。

```csharp
// ファイルからコンテンツを読み込みます。
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Watermarker クラスのメソッドを使用して、透かしを追加、検索、または削除します。

    // 変更を保存します。
    watermarker.Save("D:\\output.pdf");
}
```

### 関連項目

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
