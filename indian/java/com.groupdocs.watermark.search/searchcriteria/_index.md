---
title: "SearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वॉटरमार्क खोजते समय मानदंड बनाने के लिए उपयोग की जा सकने वाली क्लास।"
type: docs
weight: 53
url: /hi/java/com.groupdocs.watermark.search/searchcriteria/
---
**Inheritance:**
java.lang.Object
```
public abstract class SearchCriteria
```

वॉटरमार्क खोजते समय मानदंड बनाने के लिए उपयोग की जा सकने वाली क्लास।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [and(SearchCriteria other)](#and-com.groupdocs.watermark.search.SearchCriteria-) | इस `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` को अन्य मानदंडों के साथ लॉजिकल AND ऑपरेटर का उपयोग करके संयोजित करता है। |
|
|  | [or(SearchCriteria other)](#or-com.groupdocs.watermark.search.SearchCriteria-) | इस `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` को अन्य मानदंडों के साथ लॉजिकल OR ऑपरेटर का उपयोग करके संयोजित करता है। |
|
|  | [not()](#not--) | इस `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` को नकारता है। |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### and(SearchCriteria other) {#and-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria and(SearchCriteria other)
```


इस `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` को अन्य मानदंडों के साथ लॉजिकल AND ऑपरेटर का उपयोग करके संयोजित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | संयोजन के लिए खोज मानदंड। |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### or(SearchCriteria other) {#or-com.groupdocs.watermark.search.SearchCriteria-}
```
public final SearchCriteria or(SearchCriteria other)
```


इस `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` को अन्य मानदंडों के साथ लॉजिकल OR ऑपरेटर का उपयोग करके संयोजित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | other | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | संयोजन के लिए खोज मानदंड। |
|

**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### not() {#not--}
```
public final SearchCriteria not()
```


इस `[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)` को नकारता है।


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - Combined search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public abstract boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public abstract void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

