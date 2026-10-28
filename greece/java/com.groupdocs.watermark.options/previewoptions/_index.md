---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης."
type: docs
weight: 47
url: /el/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` που προκαλεί το κλείσιμο του ροής εξόδου. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` που επιστρέφει τη ροή εξόδου στον πελάτη για περαιτέρω χρήση. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος της προεπισκόπησης σελίδας. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος της προεπισκόπησης σελίδας. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος της προεπισκόπησης σελίδας. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος της προεπισκόπησης σελίδας. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Λαμβάνει έναν πίνακα αριθμών σελίδων για τη δημιουργία προεπισκοπήσεων. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ορίζει έναν πίνακα αριθμών σελίδων για τη δημιουργία προεπισκοπήσεων. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Λαμβάνει τη μορφή εικόνας προεπισκόπησης. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Ορίζει τη μορφή εικόνας προεπισκόπησης. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Λαμβάνει μια παρουσία της κλάσης δημιουργίας ροής σελίδας. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Ορίζει μια παρουσία της κλάσης δημιουργίας ροής σελίδας. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Λαμβάνει μια παρουσία της κλάσης ολοκλήρωσης προεπισκόπησης σελίδας. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Ορίζει μια παρουσία της κλάσης ολοκλήρωσης προεπισκόπησης σελίδας. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` που προκαλεί το κλείσιμο του ροής εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` που επιστρέφει τη ροή εξόδου στον πελάτη για περαιτέρω χρήση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Ειδοποιεί ότι η δημιουργία της προεπισκόπησης σελίδας ολοκληρώθηκε και λαμβάνει το ρεύμα εξόδου. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος της προεπισκόπησης σελίδας.


**Returns:**
int - Το πλάτος της προεπισκόπησης σελίδας.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το πλάτος της προεπισκόπησης σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Το πλάτος της προεπισκόπησης σελίδας. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος της προεπισκόπησης σελίδας.


**Returns:**
int - Το ύψος της προεπισκόπησης σελίδας.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το ύψος της προεπισκόπησης σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Το ύψος της προεπισκόπησης σελίδας. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Λαμβάνει έναν πίνακα αριθμών σελίδων για τη δημιουργία προεπισκοπήσεων.


**Returns:**
int[] - Ο πίνακας αριθμών σελίδων για τη δημιουργία προεπισκοπήσεων.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ορίζει έναν πίνακα αριθμών σελίδων για τη δημιουργία προεπισκοπήσεων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int[] | Ο πίνακας αριθμών σελίδων για τη δημιουργία προεπισκοπήσεων. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Λαμβάνει τη μορφή εικόνας προεπισκόπησης.


**Returns:**
int - Η μορφή εικόνας προεπισκόπησης.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Ορίζει τη μορφή εικόνας προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η μορφή εικόνας προεπισκόπησης. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Λαμβάνει μια παρουσία της κλάσης δημιουργίας ροής σελίδας.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Ορίζει μια παρουσία της κλάσης δημιουργίας ροής σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Το στιγμιότυπο της κλάσης δημιουργίας ροής σελίδας. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Λαμβάνει μια παρουσία της κλάσης ολοκλήρωσης προεπισκόπησης σελίδας.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Ορίζει μια παρουσία της κλάσης ολοκλήρωσης προεπισκόπησης σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Το στιγμιότυπο του αντιπροσώπου ολοκλήρωσης προεπισκόπησης σελίδας. |
|

