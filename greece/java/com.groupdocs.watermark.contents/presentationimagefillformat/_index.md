---
title: "PresentationImageFillFormat"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά τις ρυθμίσεις μορφής γεμίσματος εικόνας σε ένα έγγραφο PowerPoint."
type: docs
weight: 85
url: /el/java/com.groupdocs.watermark.contents/presentationimagefillformat/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.contents.OfficeImageFillFormat
```
public class PresentationImageFillFormat extends OfficeImageFillFormat<PresentationWatermarkableImage>
```

Αναπαριστά τις ρυθμίσεις μορφής γεμίσματος εικόνας σε ένα έγγραφο PowerPoint.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTileAsTexture()](#getTileAsTexture--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο. |
|
|  | [setTileAsTexture(boolean value)](#setTileAsTexture-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο. |
|
|  | [getTransparency()](#getTransparency--) | Λαμβάνει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0 |
(πλήρως διαφανές).
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ορίζει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0 |
(πλήρως διαφανές).
|
|  | [getBackgroundImage()](#getBackgroundImage--) | Λαμβάνει την εικόνα φόντου. |
|
|  | [setBackgroundImage(PresentationWatermarkableImage value)](#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-) | Ορίζει την εικόνα φόντου. |
|
### getTileAsTexture() {#getTileAsTexture--}
```
public boolean getTileAsTexture()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο.


**Returns:**
boolean - True εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο· διαφορετικά, false (η εικόνα τεντώνεται). Η προεπιλεγμένη τιμή είναι false.

### setTileAsTexture(boolean value) {#setTileAsTexture-boolean-}
```
public void setTileAsTexture(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | True εάν η εικόνα είναι επαναλαμβανόμενη στο φόντο· διαφορετικά, false (η εικόνα τεντώνεται). Η προεπιλεγμένη τιμή είναι false. |
|

### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Λαμβάνει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0
(πλήρως διαφανές).


**Returns:**
double - Η διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) μέχρι 1.0 (πλήρως διαφανής).

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Ορίζει τη διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) έως 1.0
(πλήρως διαφανές).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η διαφάνεια της εικόνας φόντου ως τιμή από 0.0 (αδιαφανής) μέχρι 1.0 (πλήρως διαφανής). |
|

### getBackgroundImage() {#getBackgroundImage--}
```
public PresentationWatermarkableImage getBackgroundImage()
```


Λαμβάνει την εικόνα φόντου.


**Returns:**
[PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) - The background image. Returns null if the image is not set.

### setBackgroundImage(PresentationWatermarkableImage value) {#setBackgroundImage-com.groupdocs.watermark.contents.PresentationWatermarkableImage-}
```
public void setBackgroundImage(PresentationWatermarkableImage value)
```


Ορίζει την εικόνα φόντου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PresentationWatermarkableImage](../../com.groupdocs.watermark.contents/presentationwatermarkableimage) | Η εικόνα φόντου. Επιστρέφει null εάν η εικόνα δεν έχει οριστεί. |
|

