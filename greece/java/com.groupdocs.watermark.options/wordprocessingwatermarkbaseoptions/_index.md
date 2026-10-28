---
title: "WordProcessingWatermarkBaseOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Βασική κλάση για τις επιλογές προσθήκης υδατογραφήματος σε ένα έγγραφο Word."
type: docs
weight: 73
url: /el/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Βασική κλάση για τις επιλογές προσθήκης υδατογραφήματος σε ένα έγγραφο Word.

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
|  | [getName()](#getName--) | Λαμβάνει το όνομα ενός σχήματος. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα ενός σχήματος. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
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
int - Ο τύπος κλειδώματος του υδατογραφήματος `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | Ο τύπος κλειδώματος του υδατογραφήματος `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα ενός σχήματος.


**Returns:**
java.lang.String - Το όνομα του σχήματος.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ορίζει το όνομα ενός σχήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το όνομα του σχήματος. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα.


**Returns:**
java.lang.String - Το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. |
|

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

