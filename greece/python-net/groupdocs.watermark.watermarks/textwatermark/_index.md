---
title: "Κλάση TextWatermark"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα υδατογράφημα κειμένου."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Αντιπροσωπεύει ένα υδατογράφημα κειμένου.

Μάθετε περισσότερα:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

Ο τύπος TextWatermark εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Αρχικοποιεί ένα νέο TextWatermark με το καθορισμένο κείμενο και τη γραμματοσειρά. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | Το χρώμα φόντου του κειμένου. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | Η γραμματοσειρά του κειμένου. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | Το χρώμα προσκηνίου του κειμένου. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | Οι ρυθμίσεις περιθωρίου αυτού του TextWatermark, εφαρμόζονται μόνο σε αρχεία εικόνας. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | Το κείμενο που θα χρησιμοποιηθεί ως υδατογράφημα. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | Η στοίχιση του κειμένου του υδατογραφήματος. |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | Η ιδιότητα που υποδεικνύει αν το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται λαμβάνοντας υπόψη τα περιθώρια του γονέα. Αν οριστεί σε True, οι υπολογισμοί λαμβάνουν υπόψη τα περιθώρια του γονέα· εξ ορισμού η τιμή είναι False και τα περιθώρια του γονέα αγνοούνται. (κληρονομείται από [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | Το επιθυμητό ύψος αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (κληρονομείται από [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | Η οριζόντια στοίχιση αυτού του Watermark. (κληρονομείται από [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | Η ιδιότητα που υποδεικνύει αν το υδατογράφημα πρέπει να τοποθετηθεί στο παρασκήνιο. Αν είναι true, το υδατογράφημα τοποθετείται στο κάτω μέρος· διαφορετικά, τοποθετείται στο επάνω μέρος (προεπιλογή είναι False). (κληρονομείται από [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | Οι ρυθμίσεις περιθωρίων αυτού του Watermark. (κληρονομείται από [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | Η διαφάνεια αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | Οι ρυθμίσεις διαμόρφωσης σελίδων αυτού του Watermark. (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | Η γωνία περιστροφής αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) σε μοίρες. (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | Η ιδιότητα υποδεικνύει εάν θα αποθηκευτούν πληροφορίες σχετικά με τα προστιθέμενα υδατογραφήματα στα μεταδεδομένα του εγγράφου. (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | Ο συντελεστής κλίμακας αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), ο οποίος ορίζει πώς το μέγεθος του υδατογραφήματος εξαρτάται από το μέγεθος του γονέα. (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Ο τύπος μεγέθυνσης του υδατογραφήματος. (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Οι επιλογές για τον ορισμό επαναλαμβανόμενου υδατογραφήματος. (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | Η κάθετη στοίχιση αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | Το επιθυμητό πλάτος αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | Η συντεταγμένη x αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | Η συντεταγμένη y αυτού του [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (κληρονομείται από το [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `TextWatermark`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
