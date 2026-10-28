---
title: "IsImageSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Suchkriterien zum Filtern ausschließlich von Bildwasserzeichen dar."
type: docs
weight: 34
url: /de/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

Stellt Suchkriterien zum Filtern ausschließlich von Bildwasserzeichen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | Initialisiert eine neue Instanz der Klasse `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


Initialisiert eine neue Instanz der Klasse `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`.


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

