---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά επιλογές κατά την προσθήκη του υδατογραφήματος ως φόντο σε ένα φύλλο εργασίας Spreadsheet."
type: docs
weight: 49
url: /el/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Αναπαριστά επιλογές κατά την προσθήκη του υδατογραφήματος ως φόντο σε ένα φύλλο εργασίας Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα κειμένου σε ένα φύλλο εργασίας εγγράφου Excel ως φόντο.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Λάβετε το δείκτη του φύλλου εργασίας στο οποίο θα προστεθεί το υδατογράφημα. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ορίζει τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Λάβετε το επιθυμητό πλάτος της εικόνας φόντου σε εικονοστοιχεία. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Ορίζει το επιθυμητό πλάτος της εικόνας φόντου σε εικονοστοιχεία. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Λαμβάνει ή ορίζει το επιθυμητό ύψος της εικόνας φόντου σε εικονοστοιχεία. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Λαμβάνει ή ορίζει το επιθυμητό ύψος της εικόνας φόντου σε εικονοστοιχεία. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Λάβετε το δείκτη του φύλλου εργασίας στο οποίο θα προστεθεί το υδατογράφημα.

-1 means every worksheet.


**Returns:**
int - Ο δείκτης του φύλλου εργασίας για την προσθήκη του υδατογραφήματος.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Ορίζει τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος.

-1 means every worksheet.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο δείκτης του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Λάβετε το επιθυμητό πλάτος της εικόνας φόντου σε εικονοστοιχεία.


**Returns:**
int - Το επιθυμητό πλάτος της εικόνας φόντου σε εικονοστοιχεία.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Ορίζει το επιθυμητό πλάτος της εικόνας φόντου σε εικονοστοιχεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Το επιθυμητό πλάτος της εικόνας φόντου σε εικονοστοιχεία. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Λαμβάνει ή ορίζει το επιθυμητό ύψος της εικόνας φόντου σε εικονοστοιχεία.


**Returns:**
int - Το επιθυμητό ύψος της εικόνας φόντου σε εικονοστοιχεία.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Λαμβάνει ή ορίζει το επιθυμητό ύψος της εικόνας φόντου σε εικονοστοιχεία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Το επιθυμητό ύψος της εικόνας φόντου σε εικονοστοιχεία. |
|

