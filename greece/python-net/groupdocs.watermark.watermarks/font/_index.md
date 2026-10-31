---
title: "Κλάση Font"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια γραμματοσειρά."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

Αντιπροσωπεύει μια γραμματοσειρά.

Ο τύπος Font εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | Δημιουργεί ένα νέο αντικείμενο Font με το καθορισμένο όνομα οικογένειας γραμματοσειράς και μέγεθος. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | Δημιουργεί ένα νέο αντικείμενο Font με το καθορισμένο όνομα οικογένειας γραμματοσειράς, μέγεθος και στυλ. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | Δημιουργεί ένα νέο αντικείμενο Font με προσαρμοσμένο όνομα οικογένειας γραμματοσειράς, φάκελο που περιέχει γραμματοσειρές TrueType, μέγεθος και στυλ. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | Δημιουργεί ένα νέο αντικείμενο Font με προσαρμοσμένο όνομα οικογένειας γραμματοσειράς, το φάκελο που περιέχει τα αρχεία γραμματοσειρών TrueType, και μέγεθος. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | Η γραμματοσειρά είναι έντονη. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | Το όνομα οικογένειας αυτής της Font. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | Ο φάκελος που περιέχει αρχεία γραμματοσειρών TrueType. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | Η γραμματοσειρά είναι πλάγια. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | Το μέγεθος αυτής της γραμματοσειράς. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | Η γραμματοσειρά καθορίζει μια οριζόντια γραμμή μέσω του κειμένου. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | Οι πληροφορίες στυλ για αυτή τη γραμματοσειρά. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | Η γραμματοσειρά είναι υπογραμμισμένη. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
