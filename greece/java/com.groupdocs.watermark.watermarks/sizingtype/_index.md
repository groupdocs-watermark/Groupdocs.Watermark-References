---
title: "SizingType"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Καθορίζει πώς πρέπει να υπολογιστεί το μέγεθος του υδατογραφήματος."
type: docs
weight: 16
url: /el/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Καθορίζει πώς πρέπει να υπολογιστεί το μέγεθος του υδατογραφήματος.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Auto](#Auto) | Το υδατογράφημα πρέπει να διαμορφώνεται αυτόματα σύμφωνα με το περιεχόμενό του. |
|
|  | [Absolute](#Absolute) | Το υδατογράφημα πρέπει να διαμορφώνεται σε ακριβές `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
και `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Το υδατογράφημα πρέπει να κλιμακωθεί σε σχέση με τις διαστάσεις του γονέα χρησιμοποιώντας |
το καθορισμένο `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Το υδατογράφημα πρέπει να κλιμακωθεί σε σχέση με την περιοχή του γονέα χρησιμοποιώντας το καθορισμένο `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Επιστρέφει μια αναπαράσταση συμβολοσειράς της τιμής `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Αναλύει μια συμβολοσειρά σε μια τιμή απαρίθμησης `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
### Auto {#Auto}
```
public static final int Auto
```


Το υδατογράφημα πρέπει να διαμορφώνεται αυτόματα σύμφωνα με το περιεχόμενό του.


### Absolute {#Absolute}
```
public static final int Absolute
```


Το υδατογράφημα πρέπει να διαμορφώνεται σε ακριβές `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
και `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Το υδατογράφημα πρέπει να κλιμακωθεί σε σχέση με τις διαστάσεις του γονέα χρησιμοποιώντας
το καθορισμένο `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Το υδατογράφημα πρέπει να κλιμακωθεί σε σχέση με την περιοχή του γονέα χρησιμοποιώντας το καθορισμένο `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς της τιμής `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Η τιμή για μετατροπή. |
|

**Returns:**
java.lang.String - Η αναπαράσταση συμβολοσειράς της τιμής `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Αναλύει μια συμβολοσειρά σε μια τιμή απαρίθμησης `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Η συμβολοσειρά για ανάλυση. |
|

**Returns:**
int - Η τιμή απαρίθμησης `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

