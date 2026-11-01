---
title: "ImageWatermark クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "画像透かしを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

画像透かしを表します。

詳しくは:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

ImageWatermark 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | 指定されたファイルパスで新しい ImageWatermark インスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | 提供された画像ストリームで新しい ImageWatermark を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | 現在のインスタンスを破棄します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | 透かしのサイズと座標が親の余白を考慮して計算されるかどうかを示すプロパティです。True に設定すると、計算は親の余白を考慮します。デフォルトでは False で、親の余白は無視されます。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | この [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) の目的の高さです。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | この Watermark の水平配置です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | 透かしを背景に配置するかどうかを示すプロパティです。true の場合、透かしは下部に配置され、false の場合は上部に配置されます（デフォルトは False）。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | この Watermark の余白設定です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | この [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) の不透明度です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | この Watermark のページ設定です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | この [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) の回転角度（度単位）です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | 追加された透かしの情報をドキュメントのメタデータに保存するかどうかを示すプロパティです。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | この [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) のスケール係数で、透かしサイズが親サイズに依存する方法を定義します。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | 透かしのサイズタイプです。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | 繰り返し透かしを定義するオプションです。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | この [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) の垂直配置です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | この [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) の目的の幅です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | この [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) の x 座標です。（[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) から継承） |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | この[`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)の y 座標です。(【`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)から継承) |

### 例

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # 画像データをストリームにロードする
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # ドキュメントを開き、画像の透かしを追加する
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
`ImageWatermark` を使用するタスクガイド：

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### 関連項目
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
