---
title: "and_ メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "論理 AND 演算子を使用して、この SearchCriteria を他の条件と結合します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

論理 AND 演算子を使用して、この SearchCriteria を他の条件と結合します。

```python
def and_(self, other):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| other | `SearchCriteria` | 組み合わせる検索基準です。 |

**Returns:** Combined search criteria.

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # 基準を組み合わせます: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### 関連項目
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
