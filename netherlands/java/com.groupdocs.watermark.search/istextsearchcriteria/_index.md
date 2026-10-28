---
title: "IsTextSearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt zoekcriteria voor het alleen filteren van tekstwatermerken voor."
type: docs
weight: 35
url: /nl/java/com.groupdocs.watermark.search/istextsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsTextSearchCriteria extends SearchCriteria
```

Stelt zoekcriteria voor het alleen filteren van tekstwatermerken voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [IsTextSearchCriteria()](#IsTextSearchCriteria--) | Initialiseert een nieuw exemplaar van de klasse `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsTextSearchCriteria() {#IsTextSearchCriteria--}
```
public IsTextSearchCriteria()
```


Initialiseert een nieuw exemplaar van de klasse `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`.


### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

