---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वॉटरमार्क आकार द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 57
url: /hi/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

वॉटरमार्क आकार द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।

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
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | निर्दिष्ट आयाम, प्रारंभिक मान और समाप्ति मान के साथ `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | प्रारंभिक मान प्राप्त करता है। |
|
|  | [getMaximum()](#getMaximum--) | समाप्ति मान प्राप्त करता है। |
|
|  | [getDimension()](#getDimension--) | खोज के लिए वॉटरमार्क का आयाम प्राप्त करता है। |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


निर्दिष्ट आयाम, प्रारंभिक मान और समाप्ति मान के साथ `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` क्लास का एक नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | dimension | int | खोज के लिए वॉटरमार्क का आयाम `[Dimension](../../com.groupdocs.watermark.common/dimension)`। |
|
|  | min | double | प्रारंभिक मान। |
|
|  | max | double | समाप्ति मान। |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


प्रारंभिक मान प्राप्त करता है।


**Returns:**
double - प्रारंभिक मान।

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


समाप्ति मान प्राप्त करता है।


**Returns:**
double - समाप्ति मान।

### getDimension() {#getDimension--}
```
public final int getDimension()
```


खोज के लिए वॉटरमार्क का आयाम प्राप्त करता है।


**Returns:**
int - वॉटरमार्क को खोजने के लिए आयाम।

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

