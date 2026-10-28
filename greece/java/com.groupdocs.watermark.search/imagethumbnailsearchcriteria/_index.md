---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά κριτήρια αναζήτησης για εύρεση εικόνων σε ένα περιεχόμενο."
type: docs
weight: 33
url: /el/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Αναπαριστά κριτήρια αναζήτησης για εύρεση εικόνων σε ένα περιεχόμενο.

<br />

*** ** * ** ***

Αυτό το κριτήριο αναζήτησης χρησιμοποιεί δυαδική μικρογραφία εικόνας για τον υπολογισμό της ομοιότητας εικόνας.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` με καθορισμένη διαδρομή αρχείου. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` με καθορισμένη ροή. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Λαμβάνει το μέγεθος της μικρογραφίας. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Ορίζει το μέγεθος της μικρογραφίας. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` με καθορισμένη διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου από την οποία θα φορτωθεί η εικόνα. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` με καθορισμένη ροή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ροή | java.io.InputStream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Λαμβάνει το μέγεθος της μικρογραφίας.


**Returns:**
byte - Από προεπιλογή θα χρησιμοποιηθεί μικρογραφία 32x32.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Ορίζει το μέγεθος της μικρογραφίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte | Από προεπιλογή θα χρησιμοποιηθεί μικρογραφία 32x32. |
|

