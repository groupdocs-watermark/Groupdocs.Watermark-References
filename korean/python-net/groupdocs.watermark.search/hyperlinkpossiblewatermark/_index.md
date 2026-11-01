---
title: "HyperlinkPossibleWatermark 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "PowerPoint 콘텐츠에서 가능한 하이퍼링크 워터마크를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

PowerPoint 콘텐츠에서 가능한 하이퍼링크 워터마크를 나타냅니다.

HyperlinkPossibleWatermark 유형은 다음 멤버를 노출합니다:

### 속성
| 속성 | 설명 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | 이 HyperlinkPossibleWatermark의 높이입니다. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | 이 HyperlinkPossibleWatermark의 부모입니다. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | 이 HyperlinkPossibleWatermark의 회전 각도(도)입니다. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | 이 HyperlinkPossibleWatermark의 URL입니다. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | 이 [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/)의 측정 단위입니다. |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | 이 HyperlinkPossibleWatermark의 너비입니다. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | 이 HyperlinkPossibleWatermark의 x 좌표입니다. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | 이 [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/)의 y좌표입니다. |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | 이 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)의 형식이 지정된 텍스트 조각 컬렉션입니다. ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)에서 상속됨) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | 이 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)의 이미지이며, 워터마크에 이미지가 없을 경우 None입니다. ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)에서 상속됨) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | 워터마크가 배치된 페이지 번호입니다. ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)에서 상속됨) |

### 예시

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

### 또 보기
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
