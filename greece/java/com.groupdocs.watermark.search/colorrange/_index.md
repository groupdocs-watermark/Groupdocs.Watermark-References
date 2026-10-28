---
title: "ColorRange"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει το πιθανό υδατογράφημα σε σχόλιο εγγράφου Visio."
type: docs
weight: 12
url: /el/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

Αναπαριστά ένα εύρος χρωμάτων. Καθορίζει τα εύρη χρησιμοποιώντας την αναπαράσταση HSB του χρώματος RGB.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`. |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` με ένα καθορισμένο ακριβές χρώμα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | Λαμβάνει την αρχική τιμή απόχρωσης, σε μοίρες. |
|
|  | [setMinHue(float value)](#setMinHue-float-) | Ορίζει την αρχική τιμή απόχρωσης, σε μοίρες. |
|
|  | [getMaxHue()](#getMaxHue--) | Λαμβάνει την τελική τιμή απόχρωσης, σε μοίρες. |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | Ορίζει την τελική τιμή απόχρωσης, σε μοίρες. |
|
|  | [getMinSaturation()](#getMinSaturation--) | Λαμβάνει την αρχική τιμή κορεσμού. |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | Ορίζει την αρχική τιμή κορεσμού. |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | Λαμβάνει την τελική τιμή κορεσμού. |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | Ορίζει την τελική τιμή κορεσμού. |
|
|  | [getMinBrightness()](#getMinBrightness--) | Λαμβάνει την αρχική τιμή φωτεινότητας. |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | Ορίζει την αρχική τιμή φωτεινότητας. |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | Λαμβάνει την τελική τιμή φωτεινότητας. |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | Ορίζει την τελική τιμή φωτεινότητας. |
|
|  | [isEmpty()](#isEmpty--) | Λαμβάνει μια τιμή που υποδεικνύει εάν μόνο το κενό χρώμα βρίσκεται εντός του εύρους. |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν μόνο το κενό χρώμα βρίσκεται εντός του εύρους. |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ColorRange](../../com.groupdocs.watermark.search/colorrange)`.


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` με ένα καθορισμένο ακριβές χρώμα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Το ακριβές χρώμα από το οποίο δημιουργείται το εύρος. |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


Λαμβάνει την αρχική τιμή απόχρωσης, σε μοίρες.


**Returns:**
float - Η αρχική τιμή απόχρωσης, σε μοίρες.

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


Ορίζει την αρχική τιμή απόχρωσης, σε μοίρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Η αρχική τιμή απόχρωσης, σε μοίρες. |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


Λαμβάνει την τελική τιμή απόχρωσης, σε μοίρες.


**Returns:**
float - Η τελική τιμή απόχρωσης, σε μοίρες.

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


Ορίζει την τελική τιμή απόχρωσης, σε μοίρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Η τελική τιμή απόχρωσης, σε μοίρες. |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


Λαμβάνει την αρχική τιμή κορεσμού.


**Returns:**
float - Ο κορεσμός κυμαίνεται από 0.0 έως 1.0, όπου 0.0 είναι σε αποχρώσεις του γκρι και 1.0 είναι ο μέγιστος κορεσμός.

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


Ορίζει την αρχική τιμή κορεσμού.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Ο κορεσμός κυμαίνεται από 0.0 έως 1.0, όπου 0.0 είναι σε αποχρώσεις του γκρι και 1.0 είναι ο μέγιστος κορεσμός. |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


Λαμβάνει την τελική τιμή κορεσμού.


**Returns:**
float - Ο κορεσμός κυμαίνεται από 0.0 έως 1.0, όπου 0.0 είναι σε αποχρώσεις του γκρι και 1.0 είναι ο μέγιστος κορεσμός.

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


Ορίζει την τελική τιμή κορεσμού.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Ο κορεσμός κυμαίνεται από 0.0 έως 1.0, όπου 0.0 είναι σε αποχρώσεις του γκρι και 1.0 είναι ο μέγιστος κορεσμός. |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


Λαμβάνει την αρχική τιμή φωτεινότητας.


**Returns:**
float - Η φωτεινότητα κυμαίνεται από 0.0 έως 1.0, όπου 0.0 αντιπροσωπεύει το μαύρο και 1.0 αντιπροσωπεύει το λευκό.

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


Ορίζει την αρχική τιμή φωτεινότητας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Η φωτεινότητα κυμαίνεται από 0.0 έως 1.0, όπου 0.0 αντιπροσωπεύει το μαύρο και 1.0 αντιπροσωπεύει το λευκό. |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


Λαμβάνει την τελική τιμή φωτεινότητας.


**Returns:**
float - Η φωτεινότητα κυμαίνεται από 0.0 έως 1.0, όπου 0.0 αντιπροσωπεύει το μαύρο και 1.0 αντιπροσωπεύει το λευκό.

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


Ορίζει την τελική τιμή φωτεινότητας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Η φωτεινότητα κυμαίνεται από 0.0 έως 1.0, όπου 0.0 αντιπροσωπεύει το μαύρο και 1.0 αντιπροσωπεύει το λευκό. |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν μόνο το κενό χρώμα βρίσκεται εντός του εύρους.


**Returns:**
boolean - Αληθές εάν μόνο το κενό χρώμα βρίσκεται εντός του εύρους (τα εύρη HSB αγνοούνται); διαφορετικά, ψευδές.

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν μόνο το κενό χρώμα βρίσκεται εντός του εύρους.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Αληθές εάν μόνο το κενό χρώμα βρίσκεται εντός του εύρους (τα εύρη HSB αγνοούνται); διαφορετικά, ψευδές. |
|

