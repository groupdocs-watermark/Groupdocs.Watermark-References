---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος αντικειμένου σε ένα έγγραφο PDF."
type: docs
weight: 29
url: /el/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Αντιπροσωπεύει τις επιλογές προσθήκης υδατογράφηματος κατά την προσθήκη υδατογραφήματος αντικειμένου σε ένα έγγραφο PDF.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα εικόνας σε ένα έγγραφο PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Λαμβάνει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Ορίζει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


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

