---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει ένα αρχείο που επισυνάπτεται σε ένα έγγραφο Excel."
type: docs
weight: 101
url: /el/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Αντιπροσωπεύει ένα αρχείο που επισυνάπτεται σε ένα έγγραφο Excel.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getContent()](#getContent--) | Λαμβάνει το περιεχόμενο του συνημμένου αρχείου. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ορίζει το περιεχόμενο του συνημμένου αρχείου. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Λαμβάνει την προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Ορίζει την προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte. |
|
|  | [isLink()](#isLink--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το περιεχόμενο περιέχει μόνο έναν σύνδεσμο προς το αρχείο. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Λαμβάνει το πλήρες όνομα του συνημμένου αρχείου. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με το συνημμένο αρχείο. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με το συνημμένο αρχείο. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Λαμβάνει την οριζόντια μετατόπιση του πλαισίου συνημμένου από το αριστερό όριο του φύλλου εργασίας σε σημεία. |
|
|  | [setX(double value)](#setX-double-) | Ορίζει την οριζόντια μετατόπιση του πλαισίου συνημμένου από το αριστερό όριο του φύλλου εργασίας σε σημεία. |
|
|  | [getY()](#getY--) | Λαμβάνει την κάθετη μετατόπιση του πλαισίου συνημμένου από το άνω όριο του φύλλου εργασίας σε σημεία. |
|
|  | [setY(double value)](#setY-double-) | Ορίζει την κάθετη μετατόπιση του πλαισίου συνημμένου από το άνω όριο του φύλλου εργασίας σε σημεία. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του πλαισίου συνημμένου σε σημεία. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος του πλαισίου συνημμένου σε σημεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος του πλαισίου συνημμένου σε σημεία. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ορίζει το ύψος του πλαισίου συνημμένου σε σημεία. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Λαμβάνει το περιεχόμενο του συνημμένου αρχείου.


**Returns:**
byte[] - Το περιεχόμενο του συνημμένου αρχείου.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ορίζει το περιεχόμενο του συνημμένου αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte[] | Το περιεχόμενο του συνημμένου αρχείου. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Λαμβάνει την προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte.


**Returns:**
byte[] - Η προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Ορίζει την προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte[] | Η προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το περιεχόμενο περιέχει μόνο έναν σύνδεσμο προς το αρχείο.


**Returns:**
boolean - True εάν το συνημμένο αρχείο αναφέρεται μέσω συνδέσμου (το περιεχόμενο δεν περιέχει το περιεχόμενο του συνημμένου αρχείου); διαφορετικά, false.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Λαμβάνει το πλήρες όνομα του συνημμένου αρχείου.


**Returns:**
java.lang.String - Το πλήρες όνομα του συνημμένου αρχείου.

<br />

*** ** * ** ***

Η επέκταση χρησιμοποιείται για τον καθορισμό της κατάλληλης εφαρμογής για το άνοιγμα του αρχείου.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με το συνημμένο αρχείο.


**Returns:**
java.lang.String - Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με το συνημμένο αρχείο.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με το συνημμένο αρχείο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το περιγραφικό (εναλλακτικό) κείμενο που σχετίζεται με το συνημμένο αρχείο. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


Λαμβάνει την οριζόντια μετατόπιση του πλαισίου συνημμένου από το αριστερό όριο του φύλλου εργασίας σε σημεία.


**Returns:**
double - Η x-συντεταγμένη του πλαισίου συνημμένου.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ορίζει την οριζόντια μετατόπιση του πλαισίου συνημμένου από το αριστερό όριο του φύλλου εργασίας σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η x-συντεταγμένη του πλαισίου συνημμένου. |
|

### getY() {#getY--}
```
public final double getY()
```


Λαμβάνει την κάθετη μετατόπιση του πλαισίου συνημμένου από το άνω όριο του φύλλου εργασίας σε σημεία.


**Returns:**
double - Η y-συντεταγμένη του πλαισίου συνημμένου.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ορίζει την κάθετη μετατόπιση του πλαισίου συνημμένου από το άνω όριο του φύλλου εργασίας σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η συντεταγμένη y του πλαισίου επισύναψης. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Λαμβάνει το πλάτος του πλαισίου συνημμένου σε σημεία.


**Returns:**
double - Το πλάτος του πλαισίου επισύναψης σε points.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ορίζει το πλάτος του πλαισίου συνημμένου σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Το πλάτος του πλαισίου επισύναψης σε points. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Λαμβάνει το ύψος του πλαισίου συνημμένου σε σημεία.


**Returns:**
double - Το ύψος του πλαισίου επισύναψης σε points.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ορίζει το ύψος του πλαισίου συνημμένου σε σημεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Το ύψος του πλαισίου επισύναψης σε points. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



