---
title: "SizeSearchCriteria クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "透かしサイズでフィルタリングできる基準を表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/
is_root: false
weight: 140
---


## SizeSearchCriteria class

透かしサイズでフィルタリングできる基準を表します。

詳しくは:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SizeSearchCriteria 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/__init__/#dimension-min-max) | 指定された次元、開始値、終了値で SizeSearchCriteria クラスの新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | この SearchCriteria を他の基準と論理 AND 演算子で結合します。（[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | （[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | この SearchCriteria を否定します。（[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | この SearchCriteria を他の基準と論理 OR 演算子で結合します。（[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | （[`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [dimension](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/dimension/) | 検索対象となる透かしの次元です。 |
| [maximum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/maximum/) | 終了値です。 |
| [minimum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/minimum/) | 開始値です。 |

### 例

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.common import Dimension
from groupdocs.watermark.search.search_criteria import SizeSearchCriteria, RotateAngleSearchCriteria, TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    width_range = SizeSearchCriteria(Dimension.WIDTH, 50, 100)
    rotate_angle = RotateAngleSearchCriteria(0, 45)
    text_criteria = TextSearchCriteria(re.compile(r"^Test watermark$"))
    watermarks = watermarker.search(text_criteria.and_(width_range.or_(rotate_angle)))
    watermarks.clear()
    watermarker.save("./output.pdf")
```

### 関連項目
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
