---
title: "IsTextSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Suchkriterien zum Filtern ausschließlich von Textwasserzeichen dar."
type: docs
weight: 35
url: /de/java/com.groupdocs.watermark.search/istextsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsTextSearchCriteria extends SearchCriteria
```

Stellt Suchkriterien zum Filtern ausschließlich von Textwasserzeichen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [IsTextSearchCriteria()](#IsTextSearchCriteria--) | Initialisiert eine neue Instanz der Klasse `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsTextSearchCriteria() {#IsTextSearchCriteria--}
```
public IsTextSearchCriteria()
```


Initialisiert eine neue Instanz der Klasse `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`.


### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

