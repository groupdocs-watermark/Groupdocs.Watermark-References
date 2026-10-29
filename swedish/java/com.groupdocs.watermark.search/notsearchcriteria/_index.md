---
title: "NotSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar NOT‑sammansatta sökkriterier."
type: docs
weight: 36
url: /sv/java/com.groupdocs.watermark.search/notsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class NotSearchCriteria extends SearchCriteria
```

Representerar NOT‑sammansatta sökkriterier.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWrapped()](#getWrapped--) |  |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getWrapped() {#getWrapped--}
```
public final SearchCriteria getWrapped()
```




**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
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

