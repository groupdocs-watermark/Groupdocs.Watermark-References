---
title: "PresentationWatermarkBaseSlideOptions クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "プレゼンテーション ドキュメントへの透かし追加オプションの基底クラスです。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
is_root: false
weight: 70
---


## PresentationWatermarkBaseSlideOptions class

プレゼンテーション ドキュメントへの透かし追加オプションの基底クラスです。

詳しくは:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

PresentationWatermarkBaseSlideOptions 型は次のメンバーを公開します:

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | 形状に関連付けられる説明（代替）テキストです。 |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | 透かしに適用する効果で、[`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) または [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) インスタンスとして指定します。 |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | このプロパティは PowerPoint でシェイプの編集が禁止されているかどうかを示します。 |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | 形状の名前です。 |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | テキスト透かし文字が読めない文字と混在しているかどうかを示すプロパティです。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | クラスのデフォルト値を取得します。（[`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) から継承） |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationWatermarkMasterSlideOptions
from groupdocs.watermark.options.presentation import PresentationWatermarkLayoutSlideOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./presentation.pptx") as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 8.0))

    master_options = PresentationWatermarkMasterSlideOptions()
    master_options.master_slide_index = 0
    watermarker.add(watermark, master_options)

    layout_options = PresentationWatermarkLayoutSlideOptions()
    layout_options.layout_slide_index = 0
    watermarker.add(watermark, layout_options)

    watermarker.save("./output.pptx")
```

### 関連項目
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
