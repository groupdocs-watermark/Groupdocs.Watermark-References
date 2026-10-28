---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει επιλογές για τον καθορισμό απαιτήσεων και διαχειριστών ροής για τη δημιουργία προεπισκόπησης του εγγράφου Διαγράμματος."
type: docs
weight: 12
url: /el/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Παρέχει επιλογές για τον καθορισμό απαιτήσεων και διαχειριστών ροής για τη δημιουργία προεπισκόπησης του εγγράφου Διαγράμματος.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` που προκαλεί το κλείσιμο της ροής εξόδου. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` που προκαλεί την επιστροφή της ροής εξόδου στον πελάτη για περαιτέρω χρήση. |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Λαμβάνει τη σημαία για απόδοση υψηλής ποιότητας. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Ορίζει τη σημαία για απόδοση υψηλής ποιότητας. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` που προκαλεί το κλείσιμο της ροής εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` που προκαλεί την επιστροφή της ροής εξόδου στον πελάτη για περαιτέρω χρήση.


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

Η προεπιλεγμένη τιμή είναι 300.

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

Η προεπιλεγμένη τιμή είναι 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Λαμβάνει τη σημαία για απόδοση υψηλής ποιότητας.


**Returns:**
boolean - Η σημαία για απόδοση υψηλής ποιότητας.

<br />

*** ** * ** ***

Η απόδοση υψηλής ποιότητας χρησιμοποιεί περισσότερους πόρους. Η προεπιλεγμένη τιμή είναι false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Ορίζει τη σημαία για απόδοση υψηλής ποιότητας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Η σημαία για απόδοση υψηλής ποιότητας. |

<br />

*** ** * ** ***

Η απόδοση υψηλής ποιότητας χρησιμοποιεί περισσότερους πόρους. Η προεπιλεγμένη τιμή είναι false.

<br />

|

