---
title: "OfficeImageFillFormat"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις ρυθμίσεις μορφής γεμίσματος εικόνας σε οποιοδήποτε υποστηριζόμενο περιεχόμενο γραφείου."
type: docs
weight: 46
url: /el/java/com.groupdocs.watermark.contents/officeimagefillformat/
---
**Inheritance:**
java.lang.Object
```
public abstract class OfficeImageFillFormat<TWatermarkableImage>
```

Αντιπροσωπεύει τις ρυθμίσεις μορφής γεμίσματος εικόνας σε οποιοδήποτε υποστηριζόμενο περιεχόμενο γραφείου.


TWatermarkableImage
: Ο ακριβής τύπος της εικόνας με δυνατότητα υδατογράφημα που χρησιμοποιείται ως φόντο.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [OfficeImageFillFormat()](#OfficeImageFillFormat--) | <br /> |

|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο. |
|
|  | [getTransparency()](#getTransparency--) | Λαμβάνει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0 (πλήρως διαφανής). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ορίζει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0 (πλήρως διαφανής). |
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Λαμβάνει την εικόνα φόντου. |
|
|  | [setBackgroundImage(TWatermarkableImage value)](#setBackgroundImage-TWatermarkableImage-) | Ορίζει την εικόνα φόντου. |
|
|  | [checkIfBackgroundImageIsSet()](#checkIfBackgroundImageIsSet--) | <br /> |

|
### OfficeImageFillFormat() {#OfficeImageFillFormat--}
```
public OfficeImageFillFormat()
```


<br />



### getTileAsTexture() {#getTileAsTexture--}
```
public abstract boolean getTileAsTexture()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο.


**Returns:**
boolean - True εάν η εικόνα επαναλαμβάνεται σε όλο το φόντο· διαφορετικά, false (η εικόνα τεντώνεται).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public abstract void setTileAsTexture(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | True εάν η εικόνα επαναλαμβάνεται σε όλο το φόντο· διαφορετικά, false (η εικόνα τεντώνεται). |
|

### getTransparency() {#getTransparency--}
```
public abstract double getTransparency()
```


Λαμβάνει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0 (πλήρως διαφανής).


**Returns:**
double - Η διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) μέχρι 1.0 (πλήρως διαφανής).

### setTransparency(double value) {#setTransparency-double-}
```
public abstract void setTransparency(double value)
```


Ορίζει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0 (πλήρως διαφανής).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) μέχρι 1.0 (πλήρως διαφανής). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public abstract TWatermarkableImage getBackgroundImage()
```


Λαμβάνει την εικόνα φόντου.


**Returns:**
TWatermarkableImage - Η εικόνα φόντου. Επιστρέφει null εάν η εικόνα δεν έχει οριστεί.

### setBackgroundImage(TWatermarkableImage value) {#setBackgroundImage-TWatermarkableImage-}
```
public abstract void setBackgroundImage(TWatermarkableImage value)
```


Ορίζει την εικόνα φόντου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | TWatermarkableImage | Η εικόνα φόντου. Επιστρέφει null εάν η εικόνα δεν έχει οριστεί. |
|

### checkIfBackgroundImageIsSet() {#checkIfBackgroundImageIsSet--}
```
public final void checkIfBackgroundImageIsSet()
```


<br />



