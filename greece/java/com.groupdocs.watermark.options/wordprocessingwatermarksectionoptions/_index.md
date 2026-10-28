---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά τις επιλογές κατά την προσθήκη σχήματος υδατογραφήματος σε μια ενότητα εγγράφου Word."
type: docs
weight: 77
url: /el/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Αναπαριστά τις επιλογές κατά την προσθήκη σχήματος υδατογραφήματος σε μια ενότητα εγγράφου Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα σε ένα συγκεκριμένο τμήμα ενός εγγράφου Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Λαμβάνει τον δείκτη μιας ενότητας για την προσθήκη του υδατογραφήματος. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Ορίζει τον δείκτη μιας ενότητας για την προσθήκη του υδατογραφήματος. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)`.


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

