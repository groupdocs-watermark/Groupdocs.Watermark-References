---
title: "PdfContent"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かしを配置できる pdf ドキュメントを表します。"
type: docs
weight: 660
url: /ja/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

透かしを配置できる pdf ドキュメントを表します。

```csharp
public class PdfContent : Content
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | この[`PdfContent`](../pdfcontent)のすべての添付ファイルのコレクションを取得します。 |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | 透かし追加時に使用される pdf ページ余白を取得または設定します。 |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | この[`PdfContent`](../pdfcontent)のすべてのページのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | コンテンツを復号化します。 |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 現在のインスタンスを破棄します。 |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | ユーザーパスワードとオーナーパスワードと同じパスワードを使用してドキュメントを暗号化します。 |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | コンテンツを暗号化します。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | すべてのコンテンツページを画像に変換します。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 備考

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### 関連項目

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
