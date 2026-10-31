---
title: "Kelas PresentationContent"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili dokumen PowerPoint di mana watermark dapat ditempatkan."
type: docs
url: /id/python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---


## PresentationContent class

Mewakili dokumen PowerPoint di mana watermark dapat ditempatkan.

Pelajari lebih lanjut:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents
- Working with slide backgrounds: https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds

Tipe PresentationContent menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/) | Mendekripsi dokumen. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#password) | Mengenkripsi dokumen. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Membuang instance saat ini. (diturunkan dari [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang tercantum dalam [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (diturunkan dari [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides/) | Koleksi semua slide tata letak dari [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) ini. |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide/) | Slide master handout dari [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) ini. |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide/) | Slide master untuk semua slide catatan dari [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) ini. |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides/) | Koleksi semua slide master dari PresentationContent ini. |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height/) | Tinggi slide catatan dalam poin. |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width/) | Lebar slide catatan dalam poin. |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height/) | Tinggi slide dalam poin. |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width/) | Lebar slide dalam poin. |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides/) | Koleksi semua slide dari [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

load_options = PresentationLoadOptions()
with Watermarker(r"D:\input.ppt", load_options) as watermarker:
    # Gunakan metode add untuk menambahkan watermark ke slide tertentu atau semua slide.
    watermarker.save(r"D:\output.ppt")
```

### Lihat Juga
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
