---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά κριτήρια αναζήτησης για εύρεση εικόνων σε ένα περιεχόμενο."
type: docs
weight: 30
url: /el/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Αναπαριστά κριτήρια αναζήτησης για εύρεση εικόνων σε ένα περιεχόμενο.

<br />

*** ** * ** ***

Αυτά τα κριτήρια αναζήτησης χρησιμοποιούν ιστογράμματα χρώματος εικόνας για τον υπολογισμό της ομοιότητας εικόνων.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` με καθορισμένη διαδρομή αρχείου. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` με καθορισμένη ροή. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Λαμβάνει τον αριθμό των κουβάδων που θα χρησιμοποιηθούν για τη δημιουργία ιστογραμμάτων χρώματος. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Ορίζει τον αριθμό των κουβάδων που θα χρησιμοποιηθούν για τη δημιουργία ιστογραμμάτων χρώματος. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` με καθορισμένη διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου από την οποία θα φορτωθεί η εικόνα. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` με καθορισμένη ροή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ροή | java.io.InputStream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Λαμβάνει τον αριθμό των κουβάδων που θα χρησιμοποιηθούν για τη δημιουργία ιστογραμμάτων χρώματος.


**Returns:**
byte - Η προεπιλεγμένη τιμή είναι 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Ορίζει τον αριθμό των κουβάδων που θα χρησιμοποιηθούν για τη δημιουργία ιστογραμμάτων χρώματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte | Η προεπιλεγμένη τιμή είναι 10. |
|

