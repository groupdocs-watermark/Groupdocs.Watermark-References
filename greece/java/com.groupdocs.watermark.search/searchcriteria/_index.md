---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Κλάση που μπορεί να χρησιμοποιηθεί για τη δημιουργία κριτηρίων κατά την αναζήτηση υδατογραφημάτων."
type: docs
weight: 53
url: /el/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

Κλάση που μπορεί να χρησιμοποιηθεί για τη δημιουργία κριτηρίων κατά την αναζήτηση υδατογραφημάτων.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | Συνδυάζει αυτό το `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή AND. |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | Συνδυάζει αυτό το `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή OR. |
|
|  | [not()](#not--) | Αναιρεί αυτό το `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


Συνδυάζει αυτό το `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή AND.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Κριτήρια αναζήτησης για συνδυασμό. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


Συνδυάζει αυτό το `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή OR.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Κριτήρια αναζήτησης για συνδυασμό. |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


Αναιρεί αυτό το `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)`.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

