---
title: "IsImageSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar sökkriterier för att endast filtrera bildvattenstämplar."
type: docs
weight: 34
url: /sv/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

Representerar sökkriterier för att endast filtrera bildvattenstämplar.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | Initierar en ny instans av klassen `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


Initierar en ny instans av klassen `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)`.


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

