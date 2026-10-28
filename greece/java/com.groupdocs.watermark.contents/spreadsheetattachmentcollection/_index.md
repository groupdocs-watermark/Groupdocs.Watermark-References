---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει μια συλλογή συνημμένων σε ένα έγγραφο Excel."
type: docs
weight: 102
url: /el/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Αντιπροσωπεύει μια συλλογή συνημμένων σε ένα έγγραφο Excel.

Αυτή η συλλογή περιέχει τα στοιχεία τύπου `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Προσθέτει ένα συνημμένο στο `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Προσθέτει ένα συνημμένο μέσω συνδέσμου (το έγγραφο δεν θα περιέχει το περιεχόμενο του συνημμένου αρχείου). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Προσθέτει ένα συνημμένο στο `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileContent | byte[] | Το περιεχόμενο του αρχείου που θα προσαρτηθεί. |
|
|  | sourceFullName | java.lang.String | Το πλήρες όνομα του συνημμένου αρχείου (Η επέκταση χρησιμοποιείται για τον καθορισμό της κατάλληλης εφαρμογής για το άνοιγμα του αρχείου). |
|
|  | previewImageContent | byte[] | Η προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte. |
|
|  | x | double | Η συντεταγμένη x του πλαισίου του συνημμένου (σε σημεία). |
|
|  | y | double | Η συντεταγμένη y του πλαισίου του συνημμένου (σε σημεία). |
|
|  | πλάτος | double | Το πλάτος του πλαισίου επισύναψης σε points. |
|
|  | ύψος | double | Το ύψος του πλαισίου επισύναψης σε points. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Προσθέτει ένα συνημμένο μέσω συνδέσμου (το έγγραφο δεν θα περιέχει το περιεχόμενο του συνημμένου αρχείου).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Η διαδρομή του συνδεδεμένου αρχείου. |
|
|  | previewImageContent | byte[] | Η προεπισκόπηση του συνημμένου αρχείου ως πίνακα byte. |
|
|  | x | double | Η συντεταγμένη x του πλαισίου του συνημμένου (σε σημεία). |
|
|  | y | double | Η συντεταγμένη y του πλαισίου του συνημμένου (σε σημεία). |
|
|  | πλάτος | double | Το πλάτος του πλαισίου επισύναψης σε points. |
|
|  | ύψος | double | Το ύψος του πλαισίου επισύναψης σε points. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

