---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει επιλογές για τον καθορισμό απαιτήσεων και διαχειριστών ροής για τη δημιουργία προεπισκόπησης του εγγράφου Παρουσίασης."
type: docs
weight: 12
url: /el/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Παρέχει επιλογές για τον καθορισμό απαιτήσεων και διαχειριστών ροής για τη δημιουργία προεπισκόπησης του εγγράφου Παρουσίασης.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Δημιουργεί μια νέα παρουσία της `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` κλάσης, προκαλώντας το κλείσιμο της ροής εξόδου. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Δημιουργεί μια νέα παρουσία της `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` κλάσης, προκαλώντας την επιστροφή της ροής εξόδου στον πελάτη για περαιτέρω χρήση. |
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
|  | [setResolution(long value)](#setResolution-long-) | Ορίζει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Δημιουργεί μια νέα παρουσία της `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` κλάσης, προκαλώντας το κλείσιμο της ροής εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Δημιουργεί μια νέα παρουσία της `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` κλάσης, προκαλώντας την επιστροφή της ροής εξόδου στον πελάτη για περαιτέρω χρήση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Δημιουργεί ένα ρεύμα για μια συγκεκριμένη προεπισκόπηση σελίδας. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Ειδοποιεί ότι η δημιουργία της προεπισκόπησης σελίδας ολοκληρώθηκε και λαμβάνει το ρεύμα εξόδου. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Προεπιλεγμένη ανάλυση σε κουκκίδες ανά ίντσα.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Λαμβάνει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.


**Returns:**
long - Η ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Ορίζει την ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | long | Η ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |
|

