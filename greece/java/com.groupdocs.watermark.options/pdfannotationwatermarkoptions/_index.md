---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος σχολίου σε ένα έγγραφο PDF."
type: docs
weight: 28
url: /el/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος σχολίου σε ένα έγγραφο PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα σημείωσης εικόνας σε ένα έγγραφο PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Λαμβάνει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Ορίζει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Λάβετε την τιμή που υποδεικνύει εάν η σημείωση θα εκτυπωθεί, αλλά δεν θα εμφανίζεται στην εφαρμογή προβολής PDF. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Ορίζει την τιμή που υποδεικνύει εάν η σημείωση θα εκτυπωθεί, αλλά δεν θα εμφανίζεται στην εφαρμογή προβολής PDF. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Λαμβάνει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος.


**Returns:**
int - Ο δείκτης σελίδας για την προσθήκη του υδατογραφήματος.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Ορίζει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο δείκτης σελίδας για την προσθήκη του υδατογραφήματος. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Λάβετε την τιμή που υποδεικνύει εάν η σημείωση θα εκτυπωθεί, αλλά δεν θα εμφανίζεται στην εφαρμογή προβολής PDF.


**Returns:**
boolean - Η τιμή που υποδεικνύει εάν η σημείωση θα εκτυπωθεί, αλλά δεν θα εμφανίζεται στην εφαρμογή προβολής PDF.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Ορίζει την τιμή που υποδεικνύει εάν η σημείωση θα εκτυπωθεί, αλλά δεν θα εμφανίζεται στην εφαρμογή προβολής PDF.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Η τιμή που υποδεικνύει εάν η σημείωση θα εκτυπωθεί, αλλά δεν θα εμφανίζεται στην εφαρμογή προβολής PDF. |
|

