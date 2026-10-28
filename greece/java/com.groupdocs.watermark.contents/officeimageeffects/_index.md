---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει εφέ που μπορούν να εφαρμοστούν σε υδατογράφημα εικόνας για περιεχόμενο γραφείου."
type: docs
weight: 45
url: /el/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Αντιπροσωπεύει εφέ που μπορούν να εφαρμοστούν σε υδατογράφημα εικόνας για περιεχόμενο γραφείου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Λαμβάνει τις ρυθμίσεις μορφής γραμμής για το περίγραμμα της εικόνας. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Ορίζει τις ρυθμίσεις μορφής γραμμής για το περίγραμμα της εικόνας. |
|
|  | [getGrayScale()](#getGrayScale--) | Λαμβάνει μια τιμή που υποδεικνύει εάν μια εικόνα θα εμφανίζεται σε λειτουργία γκρι κλίμακας. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν μια εικόνα θα εμφανίζεται σε λειτουργία γκρι κλίμακας. |
|
|  | [getChromaKey()](#getChromaKey--) | Λαμβάνει την τιμή χρώματος της εικόνας που θα θεωρηθεί διαφανής. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Ορίζει την τιμή χρώματος της εικόνας που θα θεωρηθεί διαφανής. |
|
|  | [getBrightness()](#getBrightness--) | Λαμβάνει τη φωτεινότητα της εικόνας. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Ορίζει τη φωτεινότητα της εικόνας. |
|
|  | [getContrast()](#getContrast--) | Λαμβάνει την αντίθεση για την καθορισμένη εικόνα. |
|
|  | [setContrast(double value)](#setContrast-double-) | Ορίζει την αντίθεση για την καθορισμένη εικόνα. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Λαμβάνει τις ρυθμίσεις μορφής γραμμής για το περίγραμμα της εικόνας.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Ορίζει τις ρυθμίσεις μορφής γραμμής για το περίγραμμα της εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Παράδειγμα της κλάσης OfficeLineFormat, που αντιπροσωπεύει τη μορφή γραμμής σχήματος. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν μια εικόνα θα εμφανίζεται σε λειτουργία γκρι κλίμακας.


**Returns:**
boolean - Η προεπιλεγμένη τιμή είναι false.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν μια εικόνα θα εμφανίζεται σε λειτουργία γκρι κλίμακας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Η προεπιλεγμένη τιμή είναι false. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Λαμβάνει την τιμή χρώματος της εικόνας που θα θεωρηθεί διαφανής.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Ορίζει την τιμή χρώματος της εικόνας που θα θεωρηθεί διαφανής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Η προεπιλεγμένη τιμή είναι πλήρως διαφανές χρώμα. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Λαμβάνει τη φωτεινότητα της εικόνας. Η τιμή για αυτήν την ιδιότητα πρέπει
να είναι αριθμός από 0.0 (σκοτεινότερο) έως 1.0 (φωτεινότερο).


**Returns:**
double - Η προεπιλεγμένη τιμή είναι 0.5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Ορίζει τη φωτεινότητα της εικόνας. Η τιμή για αυτήν την ιδιότητα πρέπει
να είναι αριθμός από 0.0 (σκοτεινότερο) έως 1.0 (φωτεινότερο).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η προεπιλεγμένη τιμή είναι 0.5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Λαμβάνει την αντίθεση για την καθορισμένη εικόνα. Η τιμή για αυτήν την ιδιότητα
πρέπει να είναι ένας αριθμός από 0.0 (η ελάχιστη αντίθεση) έως 1.0 (η μέγιστη αντίθεση).


**Returns:**
double - Η προεπιλεγμένη τιμή είναι 0.5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Ορίζει την αντίθεση για την καθορισμένη εικόνα. Η τιμή για αυτήν την ιδιότητα
πρέπει να είναι ένας αριθμός από 0.0 (η ελάχιστη αντίθεση) έως 1.0 (η μέγιστη αντίθεση).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η προεπιλεγμένη τιμή είναι 0.5. |
|

