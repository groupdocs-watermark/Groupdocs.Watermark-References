---
title: "OrSearchCriteria"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά σύνθετα κριτήρια αναζήτησης OR."
type: docs
weight: 37
url: /el/java/com.groupdocs.watermark.search/orsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IBinaryOperation](../../com.groupdocs.watermark.internal/ibinaryoperation)
```
public class OrSearchCriteria extends SearchCriteria implements IBinaryOperation
```

Αναπαριστά σύνθετα κριτήρια αναζήτησης OR.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getLeft()](#getLeft--) | Λαμβάνει το αριστερό κριτήριο αναζήτησης. |
|
|  | [getRight()](#getRight--) | Λαμβάνει το δεξί κριτήριο αναζήτησης. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getLeft() {#getLeft--}
```
public final SearchCriteria getLeft()
```


Λαμβάνει το αριστερό κριτήριο αναζήτησης.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The left search criteria.

### getRight() {#getRight--}
```
public final SearchCriteria getRight()
```


Λαμβάνει το δεξί κριτήριο αναζήτησης.


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The right search criteria.

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

