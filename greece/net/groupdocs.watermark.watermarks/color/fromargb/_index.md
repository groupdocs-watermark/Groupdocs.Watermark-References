---
title: FromArgb
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Δημιουργεί έναColorgroupdocs.watermark.watermarks/color δομή από μια τιμή ARGB 32bit.
type: docs
weight: 1430
url: /el/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Δημιουργεί ένα[`Color`](../../color) δομή από μια τιμή ARGB 32-bit.

```csharp
public static Color FromArgb(int argb)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb | Int32 | Μια τιμή που καθορίζει την τιμή ARGB 32-bit. |

### Επιστρεφόμενη Αξία

ο[`Color`](../../color) δομή που δημιουργεί αυτή η μέθοδος.

### Δείτε επίσης

* struct [Color](../../color)
* χώρος ονομάτων [GroupDocs.Watermark.Watermarks](../../color)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Δημιουργεί ένα[`Color`](../../color) δομή από την καθορισμένη[`Color`](../../color) δομή, αλλά με τη νέα καθορισμένη τιμή άλφα.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | Int32 | Η τιμή άλφα για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| baseColor | Color | ο[`Color`](../../color) από το οποίο να δημιουργηθεί το νέο[`Color`](../../color). |

### Επιστρεφόμενη Αξία

ο[`Color`](../../color) που δημιουργεί αυτή η μέθοδος.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Το άλφα είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

### Παρατηρήσεις

Αν και αυτή η μέθοδος επιτρέπει τη μετάδοση μιας τιμής 32 bit για την τιμή άλφα, η τιμή περιορίζεται στα 8 bit.

### Δείτε επίσης

* struct [Color](../../color)
* χώρος ονομάτων [GroupDocs.Watermark.Watermarks](../../color)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Δημιουργεί ένα[`Color`](../../color)δομή από τις καθορισμένες τιμές χρώματος 8 bit (κόκκινο, πράσινο και μπλε) και η τιμή άλφα είναι σιωπηρά 255 (πλήρως αδιαφανής).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| red | Int32 | Η τιμή του κόκκινου στοιχείου για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| green | Int32 | Η τιμή του πράσινου στοιχείου για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| blue | Int32 | Η τιμή του μπλε στοιχείου για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |

### Επιστρεφόμενη Αξία

ο[`Color`](../../color) που δημιουργεί αυτή η μέθοδος.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Το κόκκινο, το πράσινο ή το μπλε είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

### Παρατηρήσεις

Αν και αυτή η μέθοδος επιτρέπει τη μετάδοση μιας τιμής 32 bit για κάθε στοιχείο χρώματος, η τιμή κάθε στοιχείου περιορίζεται στα 8 bit.

### Δείτε επίσης

* struct [Color](../../color)
* χώρος ονομάτων [GroupDocs.Watermark.Watermarks](../../color)
* συνέλευση [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Δημιουργεί ένα[`Color`](../../color) δομή από τις τέσσερις τιμές του στοιχείου ARGB (άλφα, κόκκινο, πράσινο και μπλε).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | Int32 | Η τιμή του στοιχείου άλφα για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| red | Int32 | Η τιμή του κόκκινου στοιχείου για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| green | Int32 | Η τιμή του πράσινου στοιχείου για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |
| blue | Int32 | Η τιμή του μπλε στοιχείου για το νέο[`Color`](../../color). Οι έγκυρες τιμές είναι από 0 έως 255. |

### Επιστρεφόμενη Αξία

ο[`Color`](../../color) που δημιουργεί αυτή η μέθοδος.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Το κόκκινο, το πράσινο ή το μπλε είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

### Παρατηρήσεις

Αν και αυτή η μέθοδος επιτρέπει τη μετάδοση μιας τιμής 32 bit για κάθε στοιχείο, η τιμή κάθε στοιχείου περιορίζεται στα 8 bit.

### Δείτε επίσης

* struct [Color](../../color)
* χώρος ονομάτων [GroupDocs.Watermark.Watermarks](../../color)
* συνέλευση [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->