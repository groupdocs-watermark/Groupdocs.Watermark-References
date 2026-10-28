---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά γωνία περιστροφής του υδατογραφήματος."
type: docs
weight: 52
url: /el/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

Αντιπροσωπεύει κριτήρια που επιτρέπουν το φιλτράρισμα κατά γωνία περιστροφής του υδατογραφήματος.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | Αρχικοποιεί μια νέα παρουσία της κλάσης `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` με μια αρχική γωνία και μια τελική γωνία. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | Λαμβάνει την αρχική γωνία σε μοίρες. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | Λαμβάνει την τελική γωνία σε μοίρες. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` με μια αρχική γωνία και μια τελική γωνία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | minAngle | double | Η αρχική γωνία σε μοίρες. |
|
|  | maxAngle | double | Η τελική γωνία σε μοίρες. |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


Λαμβάνει την αρχική γωνία σε μοίρες.


**Returns:**
double - Η αρχική γωνία.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


Λαμβάνει την τελική γωνία σε μοίρες.


**Returns:**
double - Η τελική γωνία.

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

