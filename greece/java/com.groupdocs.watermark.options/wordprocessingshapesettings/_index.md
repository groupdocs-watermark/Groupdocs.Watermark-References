---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ρυθμίσεις που μπορούν να εφαρμοστούν σε υδατογράφημα σχήματος για ένα έγγραφο Word."
type: docs
weight: 71
url: /el/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Αναπαριστά ρυθμίσεις που μπορούν να εφαρμοστούν σε υδατογράφημα σχήματος για ένα έγγραφο Word.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isLocked()](#isLocked--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο Word είναι απαγορευμένη. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο Word είναι απαγορευμένη. |
|
|  | [getLockType()](#getLockType--) | Λαμβάνει τον τύπο κλειδώματος του υδατογραφήματος. |
|
|  | [setLockType(int value)](#setLockType-int-) | Ορίζει τον τύπο κλειδώματος του υδατογραφήματος. |
|
|  | [getPassword()](#getPassword--) | Λαμβάνει έναν κωδικό πρόσβασης που χρησιμοποιείται για το κλείδωμα του υδατογραφήματος. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίζει έναν κωδικό πρόσβασης που χρησιμοποιείται για το κλείδωμα του υδατογραφήματος. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Λαμβάνει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ορίζει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο Word είναι απαγορευμένη.


**Returns:**
boolean - Εάν η τιμή είναι  true , η επεξεργασία του σχήματος θα είναι απαγορευμένη. Από προεπιλογή, η τιμή είναι  false , το σχήμα μπορεί να επεξεργαστεί στο Word.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο Word είναι απαγορευμένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Εάν η τιμή είναι  true , η επεξεργασία σχήματος θα απαγορεύεται. Από προεπιλογή, η τιμή είναι  false , το σχήμα μπορεί να επεξεργαστεί στο Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Λαμβάνει τον τύπο κλειδώματος του υδατογραφήματος.


**Returns:**
int - Ο τύπος κλειδώματος υδατογραφήματος του `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Ορίζει τον τύπο κλειδώματος του υδατογραφήματος.

Η τιμή `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` δεν μπορεί να χρησιμοποιηθεί με
ένα αντικείμενο τύπου `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Ο τύπος κλειδώματος υδατογραφήματος του `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει έναν κωδικό πρόσβασης που χρησιμοποιείται για το κλείδωμα του υδατογραφήματος.


**Returns:**
java.lang.String - Ένας κωδικός πρόσβασης που χρησιμοποιείται για το κλείδωμα του υδατογραφήματος.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίζει έναν κωδικό πρόσβασης που χρησιμοποιείται για το κλείδωμα του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Ένας κωδικός πρόσβασης που χρησιμοποιείται για το κλείδωμα του υδατογραφήματος. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Λαμβάνει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος.


**Returns:**
int[] - Οι αριθμοί σελίδων για την προσθήκη του υδατογραφήματος.

<br />

*** ** * ** ***

Όλοι οι αριθμοί πρέπει να είναι μεγαλύτεροι ή ίσοι με 1. Αυτή η ιδιότητα χρησιμοποιείται μόνο όταν προστίθεται το υδατογράφημα σε ένα έγγραφο. Εάν αυτή η τιμή είναι  null , το υδατογράφημα προστίθεται σε όλες τις σελίδες.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ορίζει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int[] | Οι αριθμοί σελίδων για την προσθήκη του υδατογραφήματος. |

<br />

*** ** * ** ***

Όλοι οι αριθμοί πρέπει να είναι μεγαλύτεροι ή ίσοι με 1. Αυτή η ιδιότητα χρησιμοποιείται μόνο όταν προστίθεται το υδατογράφημα σε ένα έγγραφο. Εάν αυτή η τιμή είναι  null , το υδατογράφημα προστίθεται σε όλες τις σελίδες.

<br />

|

