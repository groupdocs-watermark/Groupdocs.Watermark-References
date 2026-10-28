---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει μια συλλογή κεφαλίδων και υποσέλιδων σε ένα έγγραφο Word."
type: docs
weight: 132
url: /el/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Αντιπροσωπεύει μια συλλογή κεφαλίδων και υποσέλιδων σε ένα έγγραφο Word.

Αυτή η συλλογή περιέχει τα στοιχεία του τύπου `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Λαμβάνει την κεφαλίδα ή το υποσέλιδο του καθορισμένου τύπου. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Συνδέει ή αποσυνδέει όλες τις κεφαλίδες και υποσέλιδα με τα αντίστοιχα |
κεφαλίδες και υποσέλιδα στην προηγούμενη ενότητα.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Λαμβάνει την κεφαλίδα ή το υποσέλιδο του καθορισμένου τύπου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | headerFooterType | int | Μια τιμή `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` που καθορίζει τον τύπο της κεφαλίδας/υποσέλιδου που θα ληφθεί. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Συνδέει ή αποσυνδέει όλες τις κεφαλίδες και υποσέλιδα με τα αντίστοιχα
κεφαλίδες και υποσέλιδα στην προηγούμενη ενότητα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | True για σύνδεση των κεφαλίδων και υποσέλιδων με την προηγούμενη ενότητα· false για αποσύνδεση. |
|

