---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά κείμενο υδατογραφήματος."
type: docs
weight: 67
url: /el/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά κείμενο υδατογραφήματος.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Το παρακάτω παράδειγμα δείχνει πώς να βρείτε και να αφαιρέσετε το υδατογράφημα χρησιμοποιώντας κριτήρια αναζήτησης.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
>    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
>    TextSearchCriteria textCriteria = new TextSearchCriteria(Pattern.compile("^Test watermark$"));
>
>    PossibleWatermarkCollection watermarks = watermarker.search(textCriteria.and(widthRange.or(rotateAngle)));
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
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` με μια καθορισμένη κανονική έκφραση. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` με μια συμβολοσειρά αναζήτησης και μια σημαία για σύγκριση. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` με μια συμβολοσειρά αναζήτησης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPattern()](#getPattern--) | Λαμβάνει το πρότυπο αναζήτησης. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Λαμβάνει μια τιμή που υποδεικνύει ότι οι μη αναγνώσιμα χαρακτήρες θα παραλειφθούν κατά τη σύγκριση συμβολοσειρών. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Ορίζει μια τιμή που υποδεικνύει ότι οι μη αναγνώσιμα χαρακτήρες θα παραλειφθούν κατά τη σύγκριση συμβολοσειρών. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` με μια καθορισμένη κανονική έκφραση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pattern | java.util.regex.Pattern | Η κανονική έκφραση για αντιστοίχιση. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pattern | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` με μια συμβολοσειρά αναζήτησης και μια σημαία για σύγκριση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | searchString | java.lang.String | Η ακριβής συμβολοσειρά για αναζήτηση. |
|
|  | isMatchCase | boolean | `false` για να αγνοηθεί η διάκριση πεζών-κεφαλαίων κατά τη σύγκριση· διαφορετικά, `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` με μια συμβολοσειρά αναζήτησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | searchString | java.lang.String | Η ακριβής συμβολοσειρά για αναζήτηση. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Λαμβάνει το πρότυπο αναζήτησης.


**Returns:**
java.util.regex.Pattern - Το πρότυπο κανονικής έκφρασης για αντιστοίχιση.

### getPatternInternal() {#getPatternInternal--}
```
public final System.Text.RegularExpressions.Regex getPatternInternal()
```




**Returns:**
com.aspose.ms.System.Text.RegularExpressions.Regex
### getSkipUnreadableCharacters() {#getSkipUnreadableCharacters--}
```
public final boolean getSkipUnreadableCharacters()
```


Λαμβάνει μια τιμή που υποδεικνύει ότι οι μη αναγνώσιμα χαρακτήρες θα παραλειφθούν κατά τη σύγκριση συμβολοσειρών.


**Returns:**
boolean - Μια τιμή που υποδεικνύει ότι οι μη αναγνώσιμα χαρακτήρες θα παραλειφθούν κατά τη σύγκριση συμβολοσειρών.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει ότι οι μη αναγνώσιμα χαρακτήρες θα παραλειφθούν κατά τη σύγκριση συμβολοσειρών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Μια τιμή που υποδεικνύει ότι οι μη αναγνώσιμοι χαρακτήρες θα παραλειφθούν κατά τη σύγκριση συμβολοσειρών. |
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

