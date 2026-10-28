---
title: "OfficeLineFormat"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τη μορφή γραμμής σχήματος."
type: docs
weight: 47
url: /el/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Αντιπροσωπεύει τη μορφή γραμμής σχήματος.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWeight()](#getWeight--) | Λαμβάνει το πάχος του πινέλου που σχεδιάζει τη διαδρομή ενός σχήματος. |
|
|  | [setWeight(double value)](#setWeight-double-) | Ορίζει το πάχος του πινέλου που σχεδιάζει τη διαδρομή ενός σχήματος. |
|
|  | [getColor()](#getColor--) | Λαμβάνει το χρώμα της γραμμής. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Ορίζει το χρώμα της γραμμής. |
|
|  | [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια της γραμμής. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Ορίζει τη διαφάνεια της γραμμής. |
|
|  | [getEnabled()](#getEnabled--) | Λαμβάνει μια τιμή που υποδεικνύει εάν ένα σχήμα θα σχεδιαστεί. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν ένα σχήμα θα σχεδιαστεί. |
|
|  | [getDashStyle()](#getDashStyle--) | Λαμβάνει το μοτίβο σημείων και παύλων για μια γραμμή. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Ορίζει το μοτίβο σημείων και παύλων για μια γραμμή. |
|
|  | [getLineStyle()](#getLineStyle--) | Λαμβάνει το στυλ της γραμμής. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Ορίζει το στυλ της γραμμής. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Λαμβάνει το πάχος του πινέλου που σχεδιάζει τη διαδρομή ενός σχήματος.


**Returns:**
double - Το πάχος της γραμμής σε σημεία. Η προεπιλεγμένη τιμή είναι 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Ορίζει το πάχος του πινέλου που σχεδιάζει τη διαδρομή ενός σχήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Το πάχος της γραμμής σε σημεία. Η προεπιλεγμένη τιμή είναι 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Λαμβάνει το χρώμα της γραμμής.

Η προεπιλεγμένη τιμή είναι `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Ορίζει το χρώμα της γραμμής.

Η προεπιλεγμένη τιμή είναι `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Το χρώμα της γραμμής. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Λαμβάνει τη διαφάνεια της γραμμής.


**Returns:**
double - Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η προεπιλεγμένη τιμή είναι 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Ορίζει τη διαφάνεια της γραμμής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η προεπιλεγμένη τιμή είναι 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν ένα σχήμα θα σχεδιαστεί.


**Returns:**
boolean - Η προεπιλεγμένη τιμή είναι false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν ένα σχήμα θα σχεδιαστεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Η προεπιλεγμένη τιμή είναι false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Λαμβάνει το μοτίβο σημείων και παύλων για μια γραμμή.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Ορίζει το μοτίβο σημείων και παύλων για μια γραμμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Λαμβάνει το στυλ της γραμμής.

Η προεπιλεγμένη τιμή είναι `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - Το στυλ γραμμής.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Ορίζει το στυλ της γραμμής.

Η προεπιλεγμένη τιμή είναι `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Το στυλ γραμμής. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
