---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο ImageDctHashSearchCriteria με καθορισμένη διαδρομή αρχείου."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Αρχικοποιεί ένα νέο αντικείμενο ImageDctHashSearchCriteria με καθορισμένη διαδρομή αρχείου.

```python
def __init__(self, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου από την οποία θα φορτωθεί η εικόνα. |

### Παράδειγμα

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Αρχικοποιεί ένα νέο αντικείμενο ImageDctHashSearchCriteria με το παρεχόμενο ρεύμα εικόνας.

```python
def __init__(self, stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή από την οποία θα φορτωθεί η εικόνα. |

### Δείτε επίσης
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
