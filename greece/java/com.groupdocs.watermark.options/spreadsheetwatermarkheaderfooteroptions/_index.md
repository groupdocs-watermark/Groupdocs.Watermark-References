---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά επιλογές κατά την προσθήκη του υδατογραφήματος σε κεφαλίδα/υποσέλιδο Spreadsheet."
type: docs
weight: 57
url: /el/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

Αναπαριστά επιλογές κατά την προσθήκη του υδατογραφήματος σε κεφαλίδα/υποσέλιδο Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα κειμένου στην κεφαλίδα φύλλου εργασίας του Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Αποκτά τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ορίζει τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Αποκτά τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος.


**Returns:**
int - Ο δείκτης του φύλλου εργασίας για την προσθήκη του υδατογραφήματος.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Ορίζει τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο δείκτης του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

