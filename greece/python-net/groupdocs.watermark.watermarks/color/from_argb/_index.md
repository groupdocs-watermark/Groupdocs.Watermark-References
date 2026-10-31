---
title: "from_argb μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί μια δομή Color από μια 32‑bit τιμή ARGB."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Δημιουργεί μια δομή Color από μια 32‑bit τιμή ARGB.

```python
def from_argb(cls, argb):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb | `int` | Μια τιμή που καθορίζει την 32-bit τιμή ARGB. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Δημιουργεί μια δομή Color από το καθορισμένο βασικό Color αλλά με μια νέα τιμή άλφα.

Παρόλο που αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας 32‑bit τιμής για την τιμή άλφα, η τιμή περιορίζεται σε 8 bits.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| alpha | `int` | Η τιμή άλφα για το νέο Color. Οι έγκυρες τιμές είναι από 0 έως 255. |
| base_color | `Color` | Το Color από το οποίο θα δημιουργηθεί το νέο Color. |

**Returns:** Color: The Color that this method creates.

| Εγείρει | Περιγραφή |
| :- | :- |
| `ValueError` | Η άλφα είναι μικρότερη από 0 ή μεγαλύτερη από 255. |

### Παράδειγμα

```python
from groupdocs.watermark.watermarks import Color

# Δημιουργήστε ένα ημιδιαφανές κόκκινο χρώμα (alpha 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Δημιουργεί ένα [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) από τις καθορισμένες 8‑bit τιμές κόκκινου, πράσινου και μπλε, με το κανάλι άλφα να ορίζεται έμμεσα σε 255 (πλήρως αδιαφανές).

Παρόλο που αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας 32‑bit τιμής για κάθε συνιστώσα χρώματος, κάθε συνιστώσα περιορίζεται σε 8 bits.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| red | `int` | Η τιμή της κόκκινης συνιστώσας για το νέο `Color`. Οι έγκυρες τιμές είναι από 0 έως 255. |
| green | `int` | Η τιμή της πράσινης συνιστώσας για το νέο `Color`. Οι έγκυρες τιμές είναι από 0 έως 255. |
| blue | `int` | Η τιμή της μπλε συνιστώσας για το νέο `Color`. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:** Color: The color that this method creates.

| Εγείρει | Περιγραφή |
| :- | :- |
| `ValueError` | Το κόκκινο, το πράσινο ή το μπλε είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

## from_argb {#alpha-red-green-blue}

Δημιουργεί ένα [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) από τις τέσσερις τιμές των συστατικών ARGB (άλφα, κόκκινο, πράσινο και μπλε).

Παρόλο που αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας 32‑bit τιμής για κάθε συνιστώσα, η τιμή κάθε συνιστώσας περιορίζεται σε 8 bits.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| alpha | `int` | Η τιμή της άλφα συνιστώσας για το νέο `Color`. Οι έγκυρες τιμές είναι από 0 έως 255. |
| red | `int` | Η τιμή της κόκκινης συνιστώσας για το νέο `Color`. Οι έγκυρες τιμές είναι από 0 έως 255. |
| green | `int` | Η τιμή της πράσινης συνιστώσας για το νέο `Color`. Οι έγκυρες τιμές είναι από 0 έως 255. |
| blue | `int` | Η τιμή της μπλε συνιστώσας για το νέο `Color`. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:** Color: The `Color` that this method creates.

| Εγείρει | Περιγραφή |
| :- | :- |
| `ValueError` | Το κόκκινο, το πράσινο ή το μπλε είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

### Παράδειγμα

```python
from groupdocs.watermark.watermarks import Color

# Δημιουργήστε ένα πλήρως αδιαφανές κόκκινο χρώμα
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Δείτε επίσης
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
