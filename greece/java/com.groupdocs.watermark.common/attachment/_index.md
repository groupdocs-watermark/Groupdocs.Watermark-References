---
title: "Attachment"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά ένα αρχείο που επισυνάπτεται σε ένα έγγραφο."
type: docs
weight: 10
url: /el/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Αναπαριστά ένα αρχείο που επισυνάπτεται σε ένα έγγραφο.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Λαμβάνει τις πληροφορίες σχετικά με ένα έγγραφο που αποθηκεύεται στο συνημμένο αρχείο. |
|
|  | [getContent()](#getContent--) | Λαμβάνει το περιεχόμενο του συνημμένου αρχείου. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ορίζει το περιεχόμενο του συνημμένου αρχείου. |
|
|  | [createWatermarker()](#createWatermarker--) | Φορτώνει περιεχόμενο από το συνημμένο αρχείο. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης και ρυθμίσεις. |
|
|  | [getContentStream()](#getContentStream--) | Λαμβάνει μια ροή από το συνημμένο αρχείο. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Ενημερώνει το συνημμένο αρχείο από μια ροή. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Ενημερώνει το συνημμένο περιεχόμενο. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Λαμβάνει τις πληροφορίες σχετικά με ένα έγγραφο που αποθηκεύεται στο συνημμένο αρχείο.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Λαμβάνει το περιεχόμενο του συνημμένου αρχείου.


**Returns:**
byte[] - Το περιεχόμενο του συνημμένου αρχείου.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Ορίζει το περιεχόμενο του συνημμένου αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte[] | Το περιεχόμενο του συνημμένου αρχείου. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Φορτώνει περιεχόμενο από το συνημμένο αρχείο.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση του περιεχομένου ενός συνημμένου. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης και ρυθμίσεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση του περιεχομένου ενός συνημμένου. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Λαμβάνει μια ροή από το συνημμένο αρχείο.


**Returns:**
com.aspose.ms.System.IO.Stream - Η ροή για ανάγνωση του περιεχομένου του αρχείου.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Ενημερώνει το συνημμένο αρχείο από μια ροή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ροή | com.aspose.ms.System.IO.Stream | Η ροή για ενημέρωση του συνημμένου αρχείου. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Ενημερώνει το συνημμένο περιεχόμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | Η ενημερωμένη έκδοση του περιεχομένου. |
|

