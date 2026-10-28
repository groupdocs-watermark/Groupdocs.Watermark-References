---
title: "MarginType"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Καθορίζει πώς πρέπει να ερμηνευτούν οι τιμές περιθωρίων."
type: docs
weight: 14
url: /el/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Καθορίζει πώς πρέπει να ερμηνευτούν οι τιμές περιθωρίων.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Absolute](#Absolute) | Τιμή περιθωρίου μετρημένη σε μονάδες περιεχομένου. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | Η τιμή του περιθωρίου πρέπει να ερμηνεύεται ως μέρος της κατάλληλης διάστασης του γονέα. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Η τιμή του περιθωρίου πρέπει να ερμηνεύεται ως μέρος της ελάχιστης διάστασης του γονέα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Επιστρέφει μια αναπαράσταση συμβολοσειράς της τιμής `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Αναλύει μια συμβολοσειρά σε μια τιμή απαρίθμησης `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Τιμή περιθωρίου μετρημένη σε μονάδες περιεχομένου.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Η τιμή του περιθωρίου πρέπει να ερμηνεύεται ως μέρος της κατάλληλης διάστασης του γονέα.


Τα αριστερά και δεξιά περιθώρια είναι σχετικά με το πλάτος του γονέα,
τα άνω και κάτω περιθώρια είναι σχετικά με το ύψος του γονέα.
Εάν επιλεγεί αυτός ο τύπος, η τιμή του περιθωρίου πρέπει να είναι μεταξύ 0.0 και 1.0.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Η τιμή του περιθωρίου πρέπει να ερμηνεύεται ως μέρος της ελάχιστης διάστασης του γονέα.


Εάν επιλεγεί αυτός ο τύπος, η τιμή του περιθωρίου πρέπει να είναι μεταξύ 0.0 και 1.0.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς της τιμής `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η τιμή για μετατροπή. |
|

**Returns:**
java.lang.String - Η αναπαράσταση συμβολοσειράς της τιμής `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Αναλύει μια συμβολοσειρά σε μια τιμή απαρίθμησης `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Η συμβολοσειρά για ανάλυση. |
|

**Returns:**
int - Η τιμή απαρίθμησης `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

