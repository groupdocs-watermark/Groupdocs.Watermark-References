---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Βασική κλάση για τις επιλογές προσθήκης υδατογράφηματος σε ένα έγγραφο Παρουσίασης."
type: docs
weight: 39
url: /el/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Βασική κλάση για τις επιλογές προσθήκης υδατογράφηματος σε ένα έγγραφο Παρουσίασης.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα υδατογράφημα σε διαφορετικές διαφάνειες υπηρεσίας μιας παρουσίασης Power Point.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isLocked()](#isLocked--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι χαρακτήρες του κειμένου υδατογραφήματος αναμιγνύονται με μη αναγνώσιμους χαρακτήρες. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι χαρακτήρες του κειμένου υδατογραφήματος αναμιγνύονται με μη αναγνώσιμους χαρακτήρες. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα ενός σχήματος. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα ενός σχήματος. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. |
|
|  | [getEffects()](#getEffects--) | Λαμβάνει μια τιμή του `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ή του `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | Ορίζει μια τιμή του `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ή του `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη.


**Returns:**
boolean - Εάν η τιμή είναι true, η επεξεργασία του σχήματος θα είναι απαγορευμένη. Από προεπιλογή, η τιμή είναι false, το σχήμα μπορεί να επεξεργαστεί στο PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint είναι απαγορευμένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Εάν η τιμή είναι true, η επεξεργασία του σχήματος θα είναι απαγορευμένη. Από προεπιλογή, η τιμή είναι false, το σχήμα μπορεί να επεξεργαστεί στο PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι χαρακτήρες του κειμένου υδατογραφήματος αναμιγνύονται με μη αναγνώσιμους χαρακτήρες.

Αυτή η προστασία ισχύει μόνο όταν η μέθοδος `#isLocked().isLocked()` επιστρέφει `true`.


**Returns:**
boolean - Μια τιμή που υποδεικνύει εάν οι χαρακτήρες του κειμένου υδατογραφήματος αναμιγνύονται με μη αναγνώσιμους χαρακτήρες.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι χαρακτήρες του κειμένου υδατογραφήματος αναμιγνύονται με μη αναγνώσιμους χαρακτήρες.

Αυτή η προστασία ισχύει μόνο όταν η μέθοδος `#isLocked().isLocked()` επιστρέφει `true`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Μια τιμή που υποδεικνύει εάν οι χαρακτήρες υδατογράφησης κειμένου είναι αναμεμιγμένοι με μη αναγνώσιμους χαρακτήρες. |
|

### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα ενός σχήματος.


**Returns:**
java.lang.String - Το όνομα του σχήματος.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ορίζει το όνομα ενός σχήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το όνομα του σχήματος. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Λαμβάνει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα.


**Returns:**
java.lang.String - Το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ορίζει το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


Λαμβάνει μια τιμή του `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ή του `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


Ορίζει μια τιμή του `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ή του `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | Η τιμή του `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` ή του `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` για τις επιδράσεις που πρέπει να εφαρμοστούν στο υδατογράφημα. |
|

