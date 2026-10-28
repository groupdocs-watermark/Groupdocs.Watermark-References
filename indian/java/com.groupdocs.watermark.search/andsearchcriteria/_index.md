---
title: "AndSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "AND कॉम्पोज़िट सर्च मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.watermark.search/andsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IBinaryOperation](../../com.groupdocs.watermark.internal/ibinaryoperation)
```
public class AndSearchCriteria extends SearchCriteria implements IBinaryOperation
```

AND कॉम्पोज़िट सर्च मानदंड का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getRight()](#getRight--) | दाएँ खोज मानदंड प्राप्त करता है। |
|
|  | [getLeft()](#getLeft--) | बाएँ खोज मानदंड प्राप्त करता है। |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### getRight() {#getRight--}
```
public final SearchCriteria getRight()
```


दाएँ खोज मानदंड प्राप्त करता है।


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The right search criteria.

### getLeft() {#getLeft--}
```
public final SearchCriteria getLeft()
```


बाएँ खोज मानदंड प्राप्त करता है।


**Returns:**
[SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) - The left search criteria.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

