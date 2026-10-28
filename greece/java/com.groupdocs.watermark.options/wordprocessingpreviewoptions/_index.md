---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης εγγράφου WordProcessing."
type: docs
weight: 69
url: /el/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης εγγράφου WordProcessing.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` που προκαλεί το κλείσιμο του ρεύματος εξόδου. |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` που επιστρέφει το ρεύμα εξόδου στον πελάτη για περαιτέρω χρήση. |
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
|  | [setResolution(float value)](#setResolution-float-) | Ορίζει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |
|
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` που προκαλεί το κλείσιμο του ρεύματος εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` που επιστρέφει το ρεύμα εξόδου στον πελάτη για περαιτέρω χρήση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Ειδοποιεί ότι η δημιουργία της προεπισκόπησης σελίδας ολοκληρώθηκε και λαμβάνει το ρεύμα εξόδου. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Προεπιλεγμένη ανάλυση σε κουκκίδες ανά ίντσα.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Λαμβάνει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.


**Returns:**
float - Η ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.

<br />

*** ** * ** ***

Η προεπιλεγμένη τιμή είναι 96.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Ορίζει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Η ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |

<br />

*** ** * ** ***

Η προεπιλεγμένη τιμή είναι 96.

<br />

|

