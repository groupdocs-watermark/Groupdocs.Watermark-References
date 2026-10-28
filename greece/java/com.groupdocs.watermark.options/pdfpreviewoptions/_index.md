---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης εγγράφου PDF."
type: docs
weight: 31
url: /el/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης εγγράφου PDF.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` προκαλώντας το κλείσιμο του ρεύματος εξόδου. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` προκαλώντας την επιστροφή του ρεύματος εξόδου στον πελάτη για περαιτέρω χρήση. |
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
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` προκαλώντας το κλείσιμο του ρεύματος εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` προκαλώντας την επιστροφή του ρεύματος εξόδου στον πελάτη για περαιτέρω χρήση.


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

Η προεπιλεγμένη τιμή είναι 150.

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

Η προεπιλεγμένη τιμή είναι 150.

<br />

|

