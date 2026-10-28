---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά μέγεθος υδατογραφήματος."
type: docs
weight: 57
url: /el/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά μέγεθος υδατογραφήματος.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Το παρακάτω παράδειγμα δείχνει πώς να βρείτε και να αφαιρέσετε υδατογραφήματα χρησιμοποιώντας κριτήρια αναζήτησης.
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
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` με καθορισμένη διάσταση, μια αρχική τιμή και μια τελική τιμή. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Λαμβάνει την αρχική τιμή. |
|
|  | [getMaximum()](#getMaximum--) | Λαμβάνει την τελική τιμή. |
|
|  | [getDimension()](#getDimension--) | Λαμβάνει τη διάσταση του υδατογραφήματος με την οποία γίνεται η αναζήτηση. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` με καθορισμένη διάσταση, μια αρχική τιμή και μια τελική τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | dimension | int | Η διάσταση `[Dimension](../../com.groupdocs.watermark.common/dimension)` ενός υδατογραφήματος με την οποία γίνεται η αναζήτηση. |
|
|  | min | double | Η αρχική τιμή. |
|
|  | max | double | Η τελική τιμή. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Λαμβάνει την αρχική τιμή.


**Returns:**
double - Η αρχική τιμή.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Λαμβάνει την τελική τιμή.


**Returns:**
double - Η τελική τιμή.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Λαμβάνει τη διάσταση του υδατογραφήματος με την οποία γίνεται η αναζήτηση.


**Returns:**
int - Η διάσταση του υδατογραφήματος για αναζήτηση.

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

