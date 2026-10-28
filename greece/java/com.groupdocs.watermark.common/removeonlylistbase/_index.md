---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει την αφηρημένη βασική κλάση για μια ισχυρά τυποποιημένη λίστα μόνο για αφαίρεση."
type: docs
weight: 17
url: /el/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Παρέχει την αφηρημένη βασική κλάση για μια ισχυρά τυποποιημένη λίστα μόνο για αφαίρεση.


T
: Ο τύπος του στοιχείου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η συλλογή είναι μόνο για ανάγνωση. |
|
|  | [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
|
|  | [remove(T item)](#remove-T-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
|
|  | [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η συλλογή είναι μόνο για ανάγνωση.


**Returns:**
boolean - Επιστρέφει true εάν η συλλογή είναι μόνο για ανάγνωση· διαφορετικά, false.

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αντικείμενο | T | Το στοιχείο που θα αφαιρεθεί από τη συλλογή. |
|

**Returns:**
boolean - True εάν το στοιχείο αφαιρέθηκε επιτυχώς· διαφορετικά false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | δείκτης | int | Ο μηδενικός δείκτης του στοιχείου που θα αφαιρεθεί. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αντικείμενο | T |  |

