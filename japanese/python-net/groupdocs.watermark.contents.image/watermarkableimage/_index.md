---
title: "WatermarkableImage クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ドキュメント内の画像を表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

ドキュメント内の画像を表します。

詳しくは:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

WatermarkableImage 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | この [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) に透かしを追加します。このメソッドは、透かしのオフセットとサイズがピクセル単位で測定されていること（設定されている場合）を前提としています。 |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | 画像をバイト配列として取得します。 |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 指定された検索条件に従って画像を検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)で指定されたオブジェクト内で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)に列挙されたオブジェクト上で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | この [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) の高さ（ピクセル単位）です。 |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | この WatermarkableImage の幅（ピクセル単位）です。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # テキスト透かしを初期化します。
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # ドキュメント内のすべての画像を検索します。
    images = watermarker.get_images()

    # 各画像に透かしを追加します。
    for img in images:
        img.add(watermark)

    # 変更を保存します。
    watermarker.save(r"D:\output.doc")
```

### 関連項目
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
