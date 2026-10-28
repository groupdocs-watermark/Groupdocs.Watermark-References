---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος XObject σε ένα έγγραφο PDF."
type: docs
weight: 34
url: /el/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος XObject σε ένα έγγραφο PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα σε μια συγκεκριμένη σελίδα ενός εγγράφου pdf.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Λαμβάνει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Ορίζει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Λαμβάνει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος.


**Returns:**
int - Ο δείκτης σελίδας για την προσθήκη του υδατογραφήματος.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Ορίζει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο δείκτης σελίδας για την προσθήκη του υδατογραφήματος. |
|

