---
title: "IsImageSearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt zoekcriteria voor het alleen filteren van afbeeldingswatermerken voor."
type: docs
weight: 34
url: /nl/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

Stelt zoekcriteria voor het alleen filteren van afbeeldingswatermerken voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | Initialiseert een nieuw exemplaar van de `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


Initialiseert een nieuw exemplaar van de `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` klasse.


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

