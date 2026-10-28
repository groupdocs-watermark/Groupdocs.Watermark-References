---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά μορφοποίηση κειμένου."
type: docs
weight: 66
url: /el/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά μορφοποίηση κειμένου.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Το παρακάτω παράδειγμα δείχνει πώς να αφαιρέσετε πιθανά υδατογραφήματα με ένα συγκεκριμένο
μορφοποίηση κειμένου (ανεξάρτητα από τον τύπο του εγγράφου).
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.doc");
>    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
>
>    criteria.setForegroundColorRange(new ColorRange());
>    criteria.getForegroundColorRange().setMinHue(-5);
>    criteria.getForegroundColorRange().setMaxHue(10);
>    criteria.getForegroundColorRange().setMinBrightness(0.01f);
>    criteria.getForegroundColorRange().setMaxBrightness(0.99f);
>    criteria.setBackgroundColorRange(new ColorRange());
>    criteria.getBackgroundColorRange().setEmpty(true);
>    criteria.setFontName("Arial");
>    criteria.setMinFontSize(19);
>    criteria.setMaxFontSize(42);
>    criteria.setFontBold(true);
>
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Λαμβάνει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα προσκηνίου κειμένου. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Ορίζει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα προσκηνίου κειμένου. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Λαμβάνει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα φόντου κειμένου. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Ορίζει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα φόντου κειμένου. |
|
|  | [getFontName()](#getFontName--) | Λαμβάνει το όνομα της γραμματοσειράς που χρησιμοποιείται σε πιθανή μορφοποίηση κειμένου υδατογραφήματος. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Ορίζει το όνομα της γραμματοσειράς που χρησιμοποιείται σε πιθανή μορφοποίηση κειμένου υδατογραφήματος. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Λαμβάνει την αρχική τιμή του μεγέθους γραμματοσειράς. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Ορίζει την αρχική τιμή του μεγέθους γραμματοσειράς. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Λαμβάνει την τελική τιμή του μεγέθους γραμματοσειράς. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Ορίζει την τελική τιμή του μεγέθους γραμματοσειράς. |
|
|  | [getFontBold()](#getFontBold--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι έντονη. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι έντονη. |
|
|  | [getFontItalic()](#getFontItalic--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι πλάγια. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι πλάγια. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι υπογραμμισμένη. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι υπογραμμισμένη. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι διαγραμμένη. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι διαγραμμένη. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Λαμβάνει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα προσκηνίου κειμένου.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Ορίζει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα προσκηνίου κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Η περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα προσκηνίου κειμένου. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Λαμβάνει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα φόντου κειμένου.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Ορίζει την περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα φόντου κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Η περιοχή των χρωμάτων που χρησιμοποιούνται για το φιλτράρισμα των υδατογραφημάτων κατά χρώμα φόντου κειμένου. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Λαμβάνει το όνομα της γραμματοσειράς που χρησιμοποιείται σε πιθανή μορφοποίηση κειμένου υδατογραφήματος.


**Returns:**
java.lang.String - Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Ορίζει το όνομα της γραμματοσειράς που χρησιμοποιείται σε πιθανή μορφοποίηση κειμένου υδατογραφήματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Λαμβάνει την αρχική τιμή του μεγέθους γραμματοσειράς.


**Returns:**
float - Η αρχική τιμή του μεγέθους γραμματοσειράς.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Ορίζει την αρχική τιμή του μεγέθους γραμματοσειράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Η αρχική τιμή του μεγέθους γραμματοσειράς. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Λαμβάνει την τελική τιμή του μεγέθους γραμματοσειράς.


**Returns:**
float - Η τελική τιμή του μεγέθους γραμματοσειράς.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Ορίζει την τελική τιμή του μεγέθους γραμματοσειράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | Η τελική τιμή του μεγέθους γραμματοσειράς. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι έντονη.


**Returns:**
java.lang.Boolean - Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι έντονη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Boolean | Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι πλάγια.


**Returns:**
java.lang.Boolean - Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι πλάγια.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Boolean | Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι υπογραμμισμένη.


**Returns:**
java.lang.Boolean - Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι υπογραμμισμένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Boolean | Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι διαγραμμένη.


**Returns:**
java.lang.Boolean - Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογραφήματος είναι διαγραμμένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Boolean | Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι το φίλτρο δεν εφαρμόζεται. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

