---
title: "IsImageSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "केवल छवि वॉटरमार्क को फ़िल्टर करने के लिए खोज मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 34
url: /hi/java/com.groupdocs.watermark.search/isimagesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public final class IsImageSearchCriteria extends SearchCriteria
```

केवल छवि वॉटरमार्क को फ़िल्टर करने के लिए खोज मानदंड का प्रतिनिधित्व करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [IsImageSearchCriteria()](#IsImageSearchCriteria--) | नया उदाहरण `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` क्लास का प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### IsImageSearchCriteria() {#IsImageSearchCriteria--}
```
public IsImageSearchCriteria()
```


नया उदाहरण `[IsImageSearchCriteria](../../com.groupdocs.watermark.search/isimagesearchcriteria)` क्लास का प्रारंभ करता है।


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

