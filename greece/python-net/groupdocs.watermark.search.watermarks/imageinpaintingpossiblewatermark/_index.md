---
title: "ImageInpaintingPossibleWatermark κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια χειροκίνητα καθορισμένη περιοχή εικόνας που πρέπει να επαναχρωματιστεί (συμπληρωθεί χρησιμοποιώντας τα γύρω pixel)."
type: docs
url: /el/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
is_root: false
weight: 110
---


## ImageInpaintingPossibleWatermark class

Αντιπροσωπεύει μια χειροκίνητα καθορισμένη περιοχή εικόνας που πρέπει να επαναχρωματιστεί (συμπληρωθεί χρησιμοποιώντας τα γύρω pixel).

Ο τύπος ImageInpaintingPossibleWatermark εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο ImageInpaintingPossibleWatermark. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [method](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method/) | Ο αλγόριθμος inpainting που χρησιμοποιείται για την ανίχνευση πιθανών υδατογραφιών. Η προεπιλογή είναι `InpaintingMethod.patch_based`. |
| [parent](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent/) | Ο γονέας αυτού του ImageInpaintingPossibleWatermark. Πάντα επιστρέφει None επειδή η περιοχή καθορίζεται χειροκίνητα. |
| [patch_size](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patch_size/) | Το μέγεθος του patch που χρησιμοποιείται από τον αλγόριθμο (μονό, 5-11). |
| [polygons](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons/) | Οι πολυγωνικές περιοχές που θα υποστούν inpainting, εκφρασμένες ως λίστα πολυγώνων όπου κάθε πολύγωνο είναι λίστα κορυφών σε εικονοστοιχεία της εικόνας. |
| [rectangles](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles/) | Οι ορθογώνιες περιοχές που θα υποστούν inpainting, σε εικονοστοιχεία της εικόνας. |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | Η συλλογή μορφοποιημένων τμημάτων κειμένου αυτής της [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [height](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/height/) | Το ύψος αυτής της [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | Η εικόνα αυτής της [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) ή None εάν η υδατογράφημα δεν έχει εικόνα. (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Ο αριθμός σελίδας όπου τοποθετείται η υδατογράφημα. (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/rotate_angle/) | Η γωνία περιστροφής του [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) σε μοίρες. (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [text](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/text/) | Το κείμενο αυτού του [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από το [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/unit_of_measurement/) | Η μονάδα μέτρησης του [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [width](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/width/) | Το πλάτος του [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [x](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/x/) | Η συντεταγμένη x του [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [y](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/y/) | Η συντεταγμένη y του [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Δείτε επίσης
* module [`groupdocs.watermark.search.watermarks`](/watermark/python-net/groupdocs.watermark.search.watermarks/)
