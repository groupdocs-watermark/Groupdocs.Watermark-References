---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο RotateAngleSearchCriteria με γωνία έναρξης και γωνία λήξης."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Αρχικοποιεί ένα νέο RotateAngleSearchCriteria με γωνία έναρξης και γωνία λήξης.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| min_angle | `float` | Η γωνία έναρξης σε μοίρες. |
| max_angle | `float` | Η γωνία λήξης σε μοίρες. |

### Παράδειγμα

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# Αναζητήστε υδατογραφήματα περιστραμμένα μεταξύ 30 και 60 μοιρών
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Δείτε επίσης
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
