---
title: IsImageSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents search criteria for filtering image watermarks only.
type: docs
weight: 34
url: /java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

Represents search criteria for filtering image watermarks only.
## Constructors

| Constructor | Description |
| --- | --- |
| [IsImageSearchCriteria()](#IsImageSearchCriteria--) | Initializes a new instance of the `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` class. |
## Methods

| Method | Description |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


Initializes a new instance of the `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` class.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | com.groupdocs.watermark.internal.ICriteriaVisitor |  |

