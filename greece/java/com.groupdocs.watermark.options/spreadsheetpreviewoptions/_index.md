---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης εγγράφου Spreadsheet."
type: docs
weight: 52
url: /el/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης εγγράφου Spreadsheet.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` που προκαλεί το κλείσιμο του ρεύματος εξόδου. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` που επιστρέφει το ρεύμα εξόδου στον πελάτη για περαιτέρω χρήση. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Προεπιλεγμένη ανάλυση σε κουκκίδες ανά ίντσα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getResolution()](#getResolution--) | Λαμβάνει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |
|
|  | [setResolution(int value)](#setResolution-int-) | Ορίζει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |
|
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Λαμβάνει τη σημαία για απόδοση μόνο της περιοχής δεδομένων χωρίς κεφαλίδες, υποσέλιδα, περιθώρια. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Ορίζει τη σημαία για απόδοση μόνο της περιοχής δεδομένων χωρίς κεφαλίδες, υποσέλιδα, περιθώρια. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` που προκαλεί το κλείσιμο του ρεύματος εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` που επιστρέφει το ρεύμα εξόδου στον πελάτη για περαιτέρω χρήση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Ειδοποιεί ότι η δημιουργία της προεπισκόπησης σελίδας ολοκληρώθηκε και λαμβάνει το ρεύμα εξόδου. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Προεπιλεγμένη ανάλυση σε κουκκίδες ανά ίντσα.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Λαμβάνει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.


**Returns:**
int - Η ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.

<br />

*** ** * ** ***

Η προεπιλεγμένη τιμή είναι 96.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Ορίζει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |

<br />

*** ** * ** ***

Η προεπιλεγμένη τιμή είναι 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Λαμβάνει τη σημαία για απόδοση μόνο της περιοχής δεδομένων χωρίς κεφαλίδες, υποσέλιδα, περιθώρια.


**Returns:**
boolean - Η σημαία για απόδοση μόνο της περιοχής δεδομένων χωρίς κεφαλίδες, υποσέλιδα, περιθώρια.

<br />

*** ** * ** ***

Αυτή η σημαία οδηγεί στην απόδοση ολόκληρου του φύλλου εργασίας σε μία σελίδα. Η προεπιλεγμένη τιμή είναι false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Ορίζει τη σημαία για απόδοση μόνο της περιοχής δεδομένων χωρίς κεφαλίδες, υποσέλιδα, περιθώρια.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Η σημαία για απόδοση μόνο της περιοχής δεδομένων χωρίς κεφαλίδες, υποσέλιδα, περιθώρια. |

<br />

*** ** * ** ***

Αυτή η σημαία οδηγεί στην απόδοση ολόκληρου του φύλλου εργασίας σε μία σελίδα. Η προεπιλεγμένη τιμή είναι false.

<br />

|

