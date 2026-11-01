---
title: "PdfContent クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "透かしを配置できる PDF ドキュメントを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

透かしを配置できる PDF ドキュメントを表します。

詳しくは:
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

PdfContent 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | コンテンツを復号化します。 |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | ユーザーパスワードとオーナーパスワードと同じパスワードを使用してドキュメントを暗号化します。 |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | コンテンツを暗号化します。 |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | すべてのコンテンツページを画像に変換します。 |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | 現在のインスタンスを破棄します。（[`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) から継承） |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 指定された検索条件に従って画像を検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)で指定されたオブジェクト内で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)に列挙されたオブジェクト上で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | この [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/) のすべての添付ファイルのコレクションです。 |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | 透かし追加時に使用される PDF ページ余白です。 |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | この [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/) のすべてのページのコレクションです。 |

### 例

```python
from groupdocs.watermark import Watermarker

# PDF ファイルを読み込む
watermarker = Watermarker("sample.pdf")

# PDF コンテンツツリーを取得する
pdf_content = watermarker.get_content()

# ページを反復処理し、サイズを出力する
for page in pdf_content.pages:
    print(page.width, page.height)
```

### 関連項目
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
