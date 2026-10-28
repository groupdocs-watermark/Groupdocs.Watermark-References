---
title: "LoadOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές φόρτωσης εγγράφου κατά τη φόρτωση ενός εγγράφου."
type: docs
weight: 24
url: /el/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Αντιπροσωπεύει τις επιλογές φόρτωσης εγγράφου κατά τη φόρτωση ενός εγγράφου.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Δημιουργεί ένα νέο αντικείμενο της κλάσης `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Δημιουργεί ένα νέο αντικείμενο της κλάσης `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` με καθορισμένο κωδικό πρόσβασης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Λαμβάνει τον κωδικό πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Λάβετε την οικογένεια μορφής του εγγράφου, υποδεικνύοντας τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Ορίστε την οικογένεια μορφής του εγγράφου, υποδεικνύοντας τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.). |
|
|  | [getFileType()](#getFileType--) | Λάβετε τον τύπο του αρχείου, υποδεικνύοντας τον τύπο του (π.χ., docx, pdf, xlsx κ.λπ.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Ορίστε τον τύπο του αρχείου, υποδεικνύοντας τον τύπο του (π.χ., docx, pdf, xlsx κ.λπ.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Δημιουργεί ένα νέο αντικείμενο της κλάσης `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Δημιουργεί ένα νέο αντικείμενο της κλάσης `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` με καθορισμένο κωδικό πρόσβασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κωδικός πρόσβασης | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα κρυπτογραφημένου περιεχομένου. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει τον κωδικό πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου.


**Returns:**
java.lang.String - Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου.

Ο κωδικός πρόσβασης μπορεί να είναι null ή κενή συμβολοσειρά. Η προεπιλεγμένη τιμή είναι null.
Εάν το περιεχόμενο δεν είναι κρυπτογραφημένο, ορίστε το σε null ή κενή συμβολοσειρά.

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε ένα έγγραφο προστατευμένο με κωδικό πρόσβασης.
>
> ````
> ```
>
>    LoadOptions loadOptions = new LoadOptions();
>    loadOptions.setPassword("pwd123");
>  
>    Watermarker watermarker = new Watermarker("D:\\doc.vsdx", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Λάβετε την οικογένεια μορφής του εγγράφου, υποδεικνύοντας τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.).


**Returns:**
int - formatFamily Ο τύπος του αρχείου.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Ορίστε την οικογένεια μορφής του εγγράφου, υποδεικνύοντας τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | formatFamily | int | Ο τύπος του αρχείου. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Λάβετε τον τύπο του αρχείου, υποδεικνύοντας τον τύπο του (π.χ., docx, pdf, xlsx κ.λπ.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Ορίστε τον τύπο του αρχείου, υποδεικνύοντας τον τύπο του (π.χ., docx, pdf, xlsx κ.λπ.).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Ο τύπος του αρχείου. |
|

