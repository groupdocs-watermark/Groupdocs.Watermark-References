---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει την αφηρημένη βασική κλάση για μια ισχυρά τυποποιημένη λίστα μόνο για ανάγνωση."
type: docs
weight: 16
url: /el/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Παρέχει την αφηρημένη βασική κλάση για μια ισχυρά τυποποιημένη λίστα μόνο για ανάγνωση.


T
: Ο τύπος του στοιχείου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στη συλλογή. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη στη συλλογή. |
|
|  | [contains(T item)](#contains-T-) | Καθορίζει εάν η συλλογή περιέχει ένα συγκεκριμένο αντικείμενο. |
|
|  | [indexOf(T item)](#indexOf-T-) | Καθορίζει τον δείκτη ενός συγκεκριμένου αντικειμένου στη συλλογή. |
|
|  | [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει μια συλλογή. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στη συλλογή.


**Returns:**
int - Ο αριθμός των στοιχείων που περιέχονται στη συλλογή.

### getInnerList() {#getInnerList--}
```
public final System.Collections.Generic.List<T> getInnerList()
```


<br />



**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### get_Item(int index) {#get-Item-int-}
```
public T get_Item(int index)
```


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | δείκτης | int | Ο δείκτης μηδενικής βάσης του στοιχείου προς λήψη. Τιμή: Το στοιχείο στον καθορισμένο δείκτη. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Καθορίζει εάν η συλλογή περιέχει ένα συγκεκριμένο αντικείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αντικείμενο | T | Το αντικείμενο προς εντοπισμό στη συλλογή. |
|

**Returns:**
boolean - Αληθές εάν το αντικείμενο βρεθεί στη συλλογή· διαφορετικά, ψευδές.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Καθορίζει τον δείκτη ενός συγκεκριμένου αντικειμένου στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αντικείμενο | T | Το αντικείμενο προς εντοπισμό στη συλλογή. |
|

**Returns:**
int - Ο δείκτης του αντικειμένου εάν βρεθεί στη συλλογή· διαφορετικά, -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Επιστρέφει έναν απαριθμητή που διατρέχει μια συλλογή.


**Returns:**
java.util.Iterator<T> - Ένα αντικείμενο IEnumerator{T} που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αντικείμενο | T |  |

