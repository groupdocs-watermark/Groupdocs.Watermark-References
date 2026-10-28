---
title: "ImageSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει βασική κλάση για κριτήρια αναζήτησης εικόνων."
type: docs
weight: 32
url: /el/java/com.groupdocs.watermark.search/imagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public abstract class ImageSearchCriteria extends PageSearchCriteria
```

Παρέχει βασική κλάση για κριτήρια αναζήτησης εικόνων.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMaxDifference()](#getMaxDifference--) | Λαμβάνει τη μέγιστη επιτρεπόμενη διαφορά μεταξύ εικόνων. |
|
|  | [setMaxDifference(double value)](#setMaxDifference-double-) | Ορίζει τη μέγιστη επιτρεπόμενη διαφορά μεταξύ εικόνων. |
|
| [getStream()](#getStream--) |  |
| [getTrueImages()](#getTrueImages--) |  |
| [getFalseImages()](#getFalseImages--) |  |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
| [resetCache()](#resetCache--) |  |
### getMaxDifference() {#getMaxDifference--}
```
public final double getMaxDifference()
```


Λαμβάνει τη μέγιστη επιτρεπόμενη διαφορά μεταξύ εικόνων.


**Returns:**
double - Η τιμή πρέπει να είναι μεταξύ 0 και 1. Το 0 σημαίνει ότι θα βρεθούν μόνο ταυτόσημες εικόνες.

### setMaxDifference(double value) {#setMaxDifference-double-}
```
public final void setMaxDifference(double value)
```


Ορίζει τη μέγιστη επιτρεπόμενη διαφορά μεταξύ εικόνων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η τιμή πρέπει να είναι μεταξύ 0 και 1. Το 0 σημαίνει ότι θα βρεθούν μόνο ταυτόσημες εικόνες. |
|

### getStream() {#getStream--}
```
public final StreamContainer getStream()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getTrueImages() {#getTrueImages--}
```
public final System.Collections.Generic.List<WatermarkableImage> getTrueImages()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.groupdocs.watermark.contents.WatermarkableImage>
### getFalseImages() {#getFalseImages--}
```
public final System.Collections.Generic.List<WatermarkableImage> getFalseImages()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.groupdocs.watermark.contents.WatermarkableImage>
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

### resetCache() {#resetCache--}
```
public final void resetCache()
```




