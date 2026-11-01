---
title: "HyperlinkPossibleWatermark クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "PowerPoint コンテンツ内の可能なハイパーリンク透かしを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

PowerPoint コンテンツ内の可能なハイパーリンク透かしを表します。

HyperlinkPossibleWatermark 型は次のメンバーを公開します:

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | この HyperlinkPossibleWatermark の高さです。 |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | この HyperlinkPossibleWatermark の親です。 |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | この HyperlinkPossibleWatermark の回転角度（度）です。 |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | この HyperlinkPossibleWatermark の URL です。 |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | この [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) の測定単位です。 |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | この HyperlinkPossibleWatermark の幅です。 |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | この HyperlinkPossibleWatermark の X 座標です。 |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | この [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) の y 座標です。 |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | この [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) の書式設定されたテキストフラグメントのコレクション。（[`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) から継承） |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | この [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) の画像、または透かしに画像がない場合は None。（[`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) から継承） |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | 透かしが配置されているページ番号。（[`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) から継承） |

### 例

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search import HyperlinkPossibleWatermark
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria(re.compile(r"someurl\.com")))
    for i in range(len(possible) - 1, -1, -1):
        if isinstance(possible[i], HyperlinkPossibleWatermark):
            print(possible[i].text)
            watermarker.remove(possible[i])
    watermarker.save("./output.pdf")
```

### 関連項目
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
