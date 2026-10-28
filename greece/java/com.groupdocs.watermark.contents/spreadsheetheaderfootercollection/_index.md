---
title: "SpreadsheetHeaderFooterCollection"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει μια συλλογή κεφαλίδων και υποσέλιδων σε ένα έγγραφο Excel."
type: docs
weight: 110
url: /el/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Αντιπροσωπεύει μια συλλογή κεφαλίδων και υποσέλιδων σε ένα έγγραφο Excel.

Αυτή η συλλογή περιέχει τα στοιχεία του τύπου `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Λαμβάνει την κεφαλίδα ή το υποσέλιδο του καθορισμένου τύπου. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Λαμβάνει την κεφαλίδα ή το υποσέλιδο του καθορισμένου τύπου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | headerFooterType | int | Μια τιμή `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` που καθορίζει τον τύπο της κεφαλίδας/υποσέλιδου που θα ληφθεί. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

