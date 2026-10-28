---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά επιλογές κατά την προσθήκη υδατογραφήματος σχήματος σε ένα φύλλο εργασίας Spreadsheet."
type: docs
weight: 60
url: /el/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Αναπαριστά επιλογές κατά την προσθήκη υδατογραφήματος σχήματος σε ένα φύλλο εργασίας Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα σε ένα συγκεκριμένο φύλλο εργασίας ενός εγγράφου Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
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
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Αποκτά τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ορίζει τον δείκτη του φύλλου εργασίας για την προσθήκη του υδατογραφήματος. |
|
|  | [getEffects()](#getEffects--) | Αποκτά μια τιμή του `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ή του `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Αποκτά ή ορίζει μια τιμή του `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ή του `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`.


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

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Αποκτά μια τιμή του `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ή του `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Αποκτά ή ορίζει μια τιμή του `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ή του `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | Το `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` ή `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` για εφέ που πρέπει να εφαρμοστούν στο υδατογράφημα. |
|

