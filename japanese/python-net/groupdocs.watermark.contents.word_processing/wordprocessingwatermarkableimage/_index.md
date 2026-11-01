---
title: "WordProcessingWatermarkableImage クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "Word 文書内の画像を表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/
is_root: false
weight: 190
---


## WordProcessingWatermarkableImage class

Word 文書内の画像を表します。

WordProcessingWatermarkableImage 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/#image_data) | 指定された画像データを使用して、[`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) クラスの新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | この [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) に透かしを追加します。このメソッドは、透かしのオフセットとサイズがピクセル単位で測定されていると想定します（割り当てられている場合）。（[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) から継承） |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | （[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) から継承） |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 指定された検索条件に従って画像を検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)で指定されたオブジェクト内で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | 画像をバイト配列として取得します。（[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) から継承） |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)に列挙されたオブジェクト上で実行されます。（[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | （[`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | この [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) の高さ（ピクセル単位）。（[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) から継承） |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | この WatermarkableImage の幅（ピクセル単位）。（[`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) から継承） |

### 例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()
image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### 関連項目
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
