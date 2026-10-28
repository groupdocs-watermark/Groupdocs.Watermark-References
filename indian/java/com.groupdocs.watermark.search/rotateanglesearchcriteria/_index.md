---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वॉटरमार्क घुमाव कोण द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 52
url: /hi/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

वॉटरमार्क घुमाव कोण द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

निम्नलिखित उदाहरण दिखाता है कि खोज मानदंड का उपयोग करके वॉटरमार्क कैसे खोजें और हटाएँ।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
>    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
>    TextSearchCriteria textCriteria = new TextSearchCriteria(Pattern.compile("^Test watermark$"));
>
>    PossibleWatermarkCollection watermarks = watermarker.search(textCriteria.and(widthRange.or(rotateAngle)));
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | एक नई उदाहरण को प्रारंभ करता है `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` वर्ग का, जिसमें प्रारंभिक कोण और समाप्ति कोण होते हैं। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | डिग्री में प्रारंभिक कोण प्राप्त करता है। |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | डिग्री में समाप्ति कोण प्राप्त करता है। |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


एक नई उदाहरण को प्रारंभ करता है `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` वर्ग का, जिसमें प्रारंभिक कोण और समाप्ति कोण होते हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | minAngle | double | डिग्री में प्रारंभिक कोण। |
|
|  | maxAngle | double | डिग्री में समाप्ति कोण। |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


डिग्री में प्रारंभिक कोण प्राप्त करता है।


**Returns:**
double - प्रारंभिक कोण।

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


डिग्री में समाप्ति कोण प्राप्त करता है।


**Returns:**
double - समाप्ति कोण।

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

