---
title: "kelas HyperlinkPossibleWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili watermark hyperlink yang mungkin dalam konten PowerPoint."
type: docs
url: /id/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Mewakili watermark hyperlink yang mungkin dalam konten PowerPoint.

Tipe HyperlinkPossibleWatermark menampilkan anggota-anggota berikut:

### Properti
| Properti | Deskripsi |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | Tinggi HyperlinkPossibleWatermark ini. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | Induk HyperlinkPossibleWatermark ini. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | Sudut rotasi HyperlinkPossibleWatermark ini dalam derajat. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | URL HyperlinkPossibleWatermark ini. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | Satuan pengukuran [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | Lebar HyperlinkPossibleWatermark ini. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | Koordinat x HyperlinkPossibleWatermark ini. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | Koordinat y [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | Koleksi fragmen teks terformat dari [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (diturunkan dari [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | Gambar dari [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) ini atau None jika watermark tidak memiliki gambar. (diturunkan dari [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Nomor halaman tempat watermark ditempatkan. (diturunkan dari [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Contoh

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

### Lihat Juga
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
