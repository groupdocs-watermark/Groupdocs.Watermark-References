---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά επιλογές κατά την προσθήκη σύγχρονου υδατογραφήματος word art σε ένα φύλλο εργασίας Spreadsheet."
type: docs
weight: 58
url: /el/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Αναπαριστά επιλογές κατά την προσθήκη σύγχρονου υδατογραφήματος word art σε ένα φύλλο εργασίας Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα σύγχρονο υδατογράφημα WordArt σε ένα έγγραφο Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Αποκτά τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ορίζει τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`.


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

