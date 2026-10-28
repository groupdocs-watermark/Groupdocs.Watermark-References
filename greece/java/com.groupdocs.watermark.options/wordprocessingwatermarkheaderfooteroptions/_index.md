---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά τις επιλογές κατά την προσθήκη του υδατογραφήματος στην κεφαλίδα/υποσέλιδο ενότητας Word."
type: docs
weight: 74
url: /el/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Αναπαριστά τις επιλογές κατά την προσθήκη του υδατογραφήματος στην κεφαλίδα/υποσέλιδο ενότητας Word.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Λαμβάνει τον δείκτη μιας ενότητας για την προσθήκη του υδατογραφήματος. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Ορίζει τον δείκτη μιας ενότητας για την προσθήκη του υδατογραφήματος. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Λαμβάνει την τιμή που προσδιορίζει τον τύπο της κεφαλίδας ή του υποσέλιδου για την προσθήκη του υδατογραφήματος. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Ορίζει την τιμή που προσδιορίζει τον τύπο της κεφαλίδας ή του υποσέλιδου για την προσθήκη του υδατογραφήματος. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Λαμβάνει τον δείκτη μιας ενότητας για την προσθήκη του υδατογραφήματος.


**Returns:**
int - Ο δείκτης μιας ενότητας για την προσθήκη του υδατογραφήματος.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Ορίζει τον δείκτη μιας ενότητας για την προσθήκη του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο δείκτης μιας ενότητας για την προσθήκη του υδατογραφήματος. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Λαμβάνει την τιμή που προσδιορίζει τον τύπο της κεφαλίδας ή του υποσέλιδου για την προσθήκη του υδατογραφήματος.


**Returns:**
int - Η τιμή τύπου `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` που προσδιορίζει τον τύπο της κεφαλίδας ή του υποσέλιδου για την προσθήκη του υδατογραφήματος.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Ορίζει την τιμή που προσδιορίζει τον τύπο της κεφαλίδας ή του υποσέλιδου για την προσθήκη του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | int | Η τιμή τύπου `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` που προσδιορίζει τον τύπο της κεφαλίδας ή του υποσέλιδου για την προσθήκη του υδατογραφήματος. |
|

