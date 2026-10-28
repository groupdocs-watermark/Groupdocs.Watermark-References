---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος στις σελίδες εγγράφου Word."
type: docs
weight: 76
url: /el/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος στις σελίδες εγγράφου Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα σε συγκεκριμένη σελίδα ενός εγγράφου Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Λαμβάνει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ορίζει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Λαμβάνει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος.


**Returns:**
int[] - Οι αριθμοί σελίδων για την προσθήκη του υδατογραφήματος.

<br />

*** ** * ** ***

Όλοι οι αριθμοί πρέπει να είναι μεγαλύτεροι ή ίσοι του 1. Αυτή η ιδιότητα χρησιμοποιείται μόνο όταν προστίθεται το υδατογράφημα σε ένα έγγραφο. Εάν αυτή η τιμή είναι  null  ή κενή, το υδατογράφημα προστίθεται σε όλες τις σελίδες.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ορίζει τους αριθμούς σελίδων για την προσθήκη του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int[] | Οι αριθμοί σελίδων για την προσθήκη του υδατογραφήματος. |

<br />

*** ** * ** ***

Όλοι οι αριθμοί πρέπει να είναι μεγαλύτεροι ή ίσοι του 1. Αυτή η ιδιότητα χρησιμοποιείται μόνο όταν προστίθεται το υδατογράφημα σε ένα έγγραφο. Εάν αυτή η τιμή είναι  null  ή κενή, το υδατογράφημα προστίθεται σε όλες τις σελίδες.

<br />

|

