---
title: "Υδατογράφημα"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ένα υδατογράφημα που θα προστεθεί σε ένα έγγραφο."
type: docs
weight: 13
url: /el/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

Αναπαριστά ένα υδατογράφημα που θα προστεθεί σε ένα έγγραφο.

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | Λαμβάνει ή ορίζει τη διαφάνεια αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Λαμβάνει ή ορίζει τη διαφάνεια αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getY()](#getY--) | Λαμβάνει τη συντεταγμένη y αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setY(double value)](#setY-double-) | Ορίζει τη συντεταγμένη y αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getX()](#getX--) | Λαμβάνει τη συντεταγμένη x αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setX(double value)](#setX-double-) | Ορίζει τη συντεταγμένη x αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Λαμβάνει την κατακόρυφη στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Ορίζει την κατακόρυφη στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Λαμβάνει την οριζόντια στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Ορίζει την οριζόντια στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Λαμβάνει τη γωνία περιστροφής αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)` σε μοίρες. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Ορίζει τη γωνία περιστροφής αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)` σε μοίρες. |
|
|  | [isBackground()](#isBackground--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το υδατογράφημα πρέπει να τοποθετηθεί στο παρασκήνιο. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν το υδατογράφημα πρέπει να τοποθετηθεί στο παρασκήνιο. |
|
|  | [getMargins()](#getMargins--) | Λαμβάνει τις ρυθμίσεις περιθωρίου αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | Ορίζει τις ρυθμίσεις περιθωρίου αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Λαμβάνει τις ρυθμίσεις διαμόρφωσης σελίδων αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | Ορίζει τις ρυθμίσεις διαμόρφωσης σελίδων αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το επιθυμητό ύψος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ορίζει το επιθυμητό ύψος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το επιθυμητό πλάτος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ορίζει το επιθυμητό πλάτος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|
|  | [getScaleFactor()](#getScaleFactor--) | Λαμβάνει μια τιμή που ορίζει πώς το μέγεθος του υδατογραφήματος εξαρτάται από το μέγεθος του γονέα. |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | Ορίζει μια τιμή που ορίζει πώς το μέγεθος του υδατογραφήματος εξαρτάται από το μέγεθος του γονέα. |
|
|  | [getSizingType()](#getSizingType--) | Λαμβάνει μια τιμή που καθορίζει τον τρόπο με τον οποίο πρέπει να διαστασιολογηθεί το υδατογράφημα. |
|
|  | [setSizingType(int value)](#setSizingType-int-) | Ορίζει μια τιμή που καθορίζει τον τρόπο με τον οποίο πρέπει να διαστασιολογηθεί το υδατογράφημα. |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται |
λαμβάνοντας υπόψη τα περιθώρια του γονέα.
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται |
λαμβάνοντας υπόψη τα περιθώρια του γονέα.
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Λαμβάνει ή ορίζει τη διαφάνεια αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Η τιμή της αδιαφάνειας πρέπει να είναι μεταξύ 0 και 1. Η προεπιλεγμένη τιμή είναι 1.


**Returns:**
double - Η αδιαφάνεια αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Λαμβάνει ή ορίζει τη διαφάνεια αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Η τιμή της αδιαφάνειας πρέπει να είναι μεταξύ 0 και 1. Η προεπιλεγμένη τιμή είναι 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η αδιαφάνεια αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Λαμβάνει τη συντεταγμένη y αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Η συντεταγμένη y αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ορίζει τη συντεταγμένη y αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη y αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Λαμβάνει τη συντεταγμένη x αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Η συντεταγμένη x αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ορίζει τη συντεταγμένη x αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η συντεταγμένη x αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Λαμβάνει την κατακόρυφη στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Η προεπιλεγμένη τιμή είναι `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Returns:**
int - Το `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Ορίζει την κατακόρυφη στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Η προεπιλεγμένη τιμή είναι `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)` αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Λαμβάνει την οριζόντια στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Η προεπιλεγμένη τιμή είναι `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Returns:**
int - Το `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Ορίζει την οριζόντια στοίχιση αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Η προεπιλεγμένη τιμή είναι `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Το `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)` αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Λαμβάνει τη γωνία περιστροφής αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)` σε μοίρες.


**Returns:**
double - Η γωνία περιστροφής αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)` σε μοίρες.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Ορίζει τη γωνία περιστροφής αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)` σε μοίρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Η γωνία περιστροφής αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)` σε μοίρες. |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το υδατογράφημα πρέπει να τοποθετηθεί στο παρασκήνιο.


**Returns:**
boolean - Εάν η τιμή είναι true, το υδατογράφημα θα τοποθετηθεί στο κάτω μέρος. Από προεπιλογή, η τιμή είναι false, το υδατογράφημα θα τοποθετηθεί στο πάνω μέρος.

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν το υδατογράφημα πρέπει να τοποθετηθεί στο παρασκήνιο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Εάν η τιμή είναι true, το υδατογράφημα θα τοποθετηθεί στο κάτω μέρος. Από προεπιλογή, η τιμή είναι false, το υδατογράφημα θα τοποθετηθεί στο πάνω μέρος. |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


Λαμβάνει τις ρυθμίσεις περιθωρίου αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


Ορίζει τις ρυθμίσεις περιθωρίου αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | Οι ρυθμίσεις περιθωρίων αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Λαμβάνει τις ρυθμίσεις διαμόρφωσης σελίδων αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Ορίζει τις ρυθμίσεις διαμόρφωσης σελίδων αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Οι ρυθμίσεις διαμόρφωσης σελίδων αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Λαμβάνει το επιθυμητό ύψος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Το επιθυμητό ύψος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ορίζει το επιθυμητό ύψος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Ο ορισμός αυτής της ιδιότητας θα αλλάξει επίσης την τιμή του `#getSizingType().getSizingType()`
ιδιότητα σε `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το επιθυμητό ύψος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Λαμβάνει το επιθυμητό πλάτος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.


**Returns:**
double - Το επιθυμητό πλάτος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ορίζει το επιθυμητό πλάτος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

Ο ορισμός αυτής της ιδιότητας θα αλλάξει επίσης την τιμή του `#getSizingType().getSizingType()`
ιδιότητα σε `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Το επιθυμητό πλάτος αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Λαμβάνει μια τιμή που ορίζει πώς το μέγεθος του υδατογραφήματος εξαρτάται από το μέγεθος του γονέα.

Η τιμή πρέπει να είναι μεταξύ 0 και 1.


**Returns:**
double - Ο συντελεστής κλίμακας αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


Ορίζει μια τιμή που ορίζει πώς το μέγεθος του υδατογραφήματος εξαρτάται από το μέγεθος του γονέα.

Η τιμή πρέπει να είναι μεταξύ 0 και 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | double | Ο συντελεστής κλίμακας αυτού του `[Watermark](../../com.groupdocs.watermark/watermark)`. |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


Λαμβάνει μια τιμή που καθορίζει τον τρόπο με τον οποίο πρέπει να διαστασιολογηθεί το υδατογράφημα.


**Returns:**
int - Ο τύπος μεγέθους.

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


Ορίζει μια τιμή που καθορίζει τον τρόπο με τον οποίο πρέπει να διαστασιολογηθεί το υδατογράφημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο τύπος μεγέθους. |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται
λαμβάνοντας υπόψη τα περιθώρια του γονέα.


**Returns:**
boolean - Εάν η τιμή είναι true, το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται λαμβάνοντας υπόψη τα περιθώρια του γονέα. Από προεπιλογή, η τιμή είναι false, τα περιθώρια του γονέα αγνοούνται.

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται
λαμβάνοντας υπόψη τα περιθώρια του γονέα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Εάν η τιμή είναι true, το μέγεθος και οι συντεταγμένες του υδατογραφήματος υπολογίζονται λαμβάνοντας υπόψη τα περιθώρια του γονέα. Από προεπιλογή, η τιμή είναι false, τα περιθώρια του γονέα αγνοούνται. |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
