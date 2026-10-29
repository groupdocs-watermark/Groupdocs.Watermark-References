---
title: "IsTextSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar sökkriterier för att endast filtrera textvattenstämplar."
type: docs
weight: 35
url: /sv/java/com.groupdocs.watermark.search/istextsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsTextSearchCriteria extends SearchCriteria
```

Representerar sökkriterier för att endast filtrera textvattenstämplar.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [IsTextSearchCriteria()](#IsTextSearchCriteria--) | Initierar en ny instans av klassen `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsTextSearchCriteria() {#IsTextSearchCriteria--}
```
public IsTextSearchCriteria()
```


Initierar en ny instans av klassen `[IsTextSearchCriteria](../../com.groupdocs.watermark.search/istextsearchcriteria)`.


### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

