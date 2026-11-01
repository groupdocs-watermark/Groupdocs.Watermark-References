---
title: "Класс HyperlinkPossibleWatermark"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет возможный гиперссылочный водяной знак в содержимом PowerPoint."
type: docs
url: /ru/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Представляет возможный гиперссылочный водяной знак в содержимом PowerPoint.

Тип HyperlinkPossibleWatermark раскрывает следующие члены:

### Свойства
| Свойство | Описание |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | Высота этого HyperlinkPossibleWatermark. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | Родитель этого HyperlinkPossibleWatermark. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | Угол поворота этого HyperlinkPossibleWatermark в градусах. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | URL-адрес этого HyperlinkPossibleWatermark. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | Единица измерения этого [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | Ширина этого HyperlinkPossibleWatermark. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | Координата x этого HyperlinkPossibleWatermark. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | Координата y этого [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | Коллекция отформатированных текстовых фрагментов этого [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (унаследовано от [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | Изображение этого [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) или None, если у водяного знака нет изображения. (унаследовано от [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Номер страницы, на которой размещён водяной знак. (унаследовано от [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Пример

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

### См. также
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
