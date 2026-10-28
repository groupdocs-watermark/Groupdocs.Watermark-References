---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει σχήμα υδατογραφήματος σε περιεχόμενο οποιασδήποτε υποστηριζόμενης μορφής."
type: docs
weight: 55
url: /el/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Αντιπροσωπεύει σχήμα υδατογραφήματος σε περιεχόμενο οποιασδήποτε υποστηριζόμενης μορφής.


T
: Ο τύπος του σχήματος.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής του σχήματος σε μοίρες. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου του σχήματος. |
|
|  | [getText()](#getText--) | Λαμβάνει το κείμενο του σχήματος. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ορίζει το κείμενο του σχήματος. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής του σχήματος σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής του σχήματος σε μοίρες.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Λαμβάνει τη συλλογή των μορφοποιημένων τμημάτων κειμένου του σχήματος.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Λαμβάνει το κείμενο του σχήματος.


**Returns:**
java.lang.String - Το κείμενο του σχήματος.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ορίζει το κείμενο του σχήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το κείμενο του σχήματος. |
|

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




