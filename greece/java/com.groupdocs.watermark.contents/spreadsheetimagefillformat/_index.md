---
title: "SpreadsheetImageFillFormat"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις ρυθμίσεις μορφής γεμίσματος εικόνας σε ένα έγγραφο Excel."
type: docs
weight: 114
url: /el/java/com.groupdocs.watermark.contents/spreadsheetimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class SpreadsheetImageFillFormat extends OfficeImageFillFormat<SpreadsheetWatermarkableImage>
```

Αντιπροσωπεύει τις ρυθμίσεις μορφής γεμίσματος εικόνας σε ένα έγγραφο Excel.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο. |
|
|  | [getTransparency()](#getTransparency--) | Λαμβάνει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) |
μέχρι 1.0 (πλήρως διαφανής).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ορίζει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) |
μέχρι 1.0 (πλήρως διαφανής).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Λαμβάνει την εικόνα φόντου. |
|
|  | [setBackgroundImage(SpreadsheetWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Ορίζει την εικόνα φόντου. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο.


**Returns:**
boolean - True εάν η εικόνα επαναλαμβάνεται σε όλο το φόντο· διαφορετικά, false (η εικόνα τεντώνεται).

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | True εάν η εικόνα επαναλαμβάνεται σε όλο το φόντο· διαφορετικά, false (η εικόνα τεντώνεται). |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Λαμβάνει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής)
μέχρι 1.0 (πλήρως διαφανής).


**Returns:**
double - Η διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) μέχρι 1.0 (πλήρως διαφανής).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Ορίζει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής)
μέχρι 1.0 (πλήρως διαφανής).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) μέχρι 1.0 (πλήρως διαφανής). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public SpreadsheetWatermarkableImage getBackgroundImage()
```


Λαμβάνει την εικόνα φόντου.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(SpreadsheetWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public void setBackgroundImage(SpreadsheetWatermarkableImage value)
```


Ορίζει την εικόνα φόντου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Η εικόνα φόντου. Επιστρέφει null εάν η εικόνα δεν έχει οριστεί. |
|

