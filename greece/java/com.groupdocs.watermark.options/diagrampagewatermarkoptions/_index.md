---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά επιλογές προσθήκης υδατογραφήματος όταν προστίθεται υδατογράφημα σχήματος σε συγκεκριμένη σελίδα ενός εγγράφου Visio."
type: docs
weight: 11
url: /el/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Αναπαριστά επιλογές προσθήκης υδατογραφήματος όταν προστίθεται υδατογράφημα σχήματος σε συγκεκριμένη σελίδα ενός εγγράφου Visio.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα προστατευμένο υδατογράφημα στην πρώτη σελίδα ενός εγγράφου Visio.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Λαμβάνει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Ορίζει τον δείκτη σελίδας για την προσθήκη του υδατογραφήματος. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)`.


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

