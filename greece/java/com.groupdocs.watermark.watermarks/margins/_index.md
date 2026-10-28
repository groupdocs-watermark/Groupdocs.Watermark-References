---
title: "Περιθώρια"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά τις ρυθμίσεις περιθωρίων για κάθε άκρο ενός αντικειμένου."
type: docs
weight: 15
url: /el/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Αναπαριστά τις ρυθμίσεις περιθωρίων για κάθε άκρο ενός αντικειμένου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Margins()](#Margins--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Margins](../../com.groupdocs.watermark.watermarks/margins)`. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[Margins](../../com.groupdocs.watermark.watermarks/margins)` με τον καθορισμένο τύπο, θέση και μέγεθος. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Λαμβάνει το `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Ορίζει το `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Λαμβάνει το αριστερό περιθώριο. |
|
|  | [setLeft(double value)](#setLeft-double-) | Ορίζει το αριστερό περιθώριο. |
|
|  | [getRight()](#getRight--) | Λαμβάνει το δεξί περιθώριο. |
|
|  | [setRight(double value)](#setRight-double-) | Ορίζει το δεξί περιθώριο. |
|
|  | [getTop()](#getTop--) | Λαμβάνει το άνω περιθώριο. |
|
|  | [setTop(double value)](#setTop-double-) | Ορίζει το άνω περιθώριο. |
|
|  | [getBottom()](#getBottom--) | Λαμβάνει το κάτω περιθώριο. |
|
|  | [setBottom(double value)](#setBottom-double-) | Ορίζει το κάτω περιθώριο. |
|
### Margins() {#Margins--}
```
public Margins()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Margins](../../com.groupdocs.watermark.watermarks/margins)`.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[Margins](../../com.groupdocs.watermark.watermarks/margins)` με τον καθορισμένο τύπο, θέση και μέγεθος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | marginType | int | Το `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Καθορίζει πώς πρέπει να ερμηνευτούν οι τιμές των περιθωρίων. |
|
|  | αριστερά | double | Η τιμή του αριστερού περιθωρίου. |
|
|  | δεξιά | double | Η τιμή του δεξιού περιθωρίου. |
|
|  | πάνω | double | Η τιμή του άνω περιθωρίου. |
|
|  | κάτω | double | Η τιμή του κάτω περιθωρίου. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Λαμβάνει το `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Ορίζοντας μια νέα τιμή σε αυτήν την ιδιότητα, επαναφέρει αυτόματα όλα τα περιθώρια στις προεπιλεγμένες τιμές τους (μηδέν).

Η προεπιλεγμένη τιμή είναι το `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`.


**Returns:**
int - Η τιμή που καθορίζει πώς πρέπει να ερμηνευτούν τα περιθώρια.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Ορίζει το `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Ορίζοντας μια νέα τιμή σε αυτήν την ιδιότητα, επαναφέρει αυτόματα όλα τα περιθώρια στις προεπιλεγμένες τιμές τους (μηδέν).

Η προεπιλεγμένη τιμή είναι το `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η τιμή που καθορίζει πώς πρέπει να ερμηνευτούν τα περιθώρια. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Λαμβάνει το αριστερό περιθώριο.


**Returns:**
double - Οριζόντια μετατόπιση από το αριστερό όριο του γονέα.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Ορίζει το αριστερό περιθώριο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Οριζόντια μετατόπιση από το αριστερό όριο του γονέα. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Λαμβάνει το δεξί περιθώριο.


**Returns:**
double - Οριζόντια μετατόπιση από το δεξιό όριο του γονέα.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Ορίζει το δεξί περιθώριο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Οριζόντια μετατόπιση από το δεξιό όριο του γονέα. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Λαμβάνει το άνω περιθώριο.


**Returns:**
double - Οριζόντια μετατόπιση από το άνω όριο του γονέα.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Ορίζει το άνω περιθώριο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Οριζόντια μετατόπιση από το άνω όριο του γονέα. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Λαμβάνει το κάτω περιθώριο.


**Returns:**
double - Οριζόντια μετατόπιση από το κάτω όριο του γονέα.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Ορίζει το κάτω περιθώριο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Οριζόντια μετατόπιση από το κάτω όριο του γονέα. |
|

