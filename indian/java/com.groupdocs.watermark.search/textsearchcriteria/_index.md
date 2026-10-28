---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "वॉटरमार्क टेक्स्ट द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 67
url: /hi/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

वॉटरमार्क टेक्स्ट द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

निम्न उदाहरण दर्शाता है कि खोज मानदंड का उपयोग करके वॉटरमार्क को कैसे खोजें और हटाएँ।
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
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | निर्दिष्ट रेगुलर एक्सप्रेशन के साथ `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` क्लास की नई इंस्टेंस को प्रारंभ करता है। |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | एक खोज स्ट्रिंग और तुलना के लिए एक फ़्लैग के साथ `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` क्लास की नई इंस्टेंस को प्रारंभ करता है। |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | एक खोज स्ट्रिंग के साथ `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` क्लास की नई इंस्टेंस को प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPattern()](#getPattern--) | खोज पैटर्न प्राप्त करता है। |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रिंग तुलना के दौरान अपठनीय अक्षरों को छोड़ दिया जाएगा। |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | एक मान सेट करता है जो दर्शाता है कि स्ट्रिंग तुलना के दौरान अपठनीय अक्षरों को छोड़ दिया जाएगा। |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


निर्दिष्ट रेगुलर एक्सप्रेशन के साथ `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` क्लास की नई इंस्टेंस को प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पैटर्न | java.util.regex.Pattern | मैच करने के लिए रेगुलर एक्सप्रेशन। |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पैटर्न | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


एक खोज स्ट्रिंग और तुलना के लिए एक फ़्लैग के साथ `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` क्लास की नई इंस्टेंस को प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | searchString | java.lang.String | खोज के लिए सटीक स्ट्रिंग। |
|
|  | isMatchCase | boolean | `false` तुलना के दौरान केस को अनदेखा करने के लिए; अन्यथा, `true`। |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


एक खोज स्ट्रिंग के साथ `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` क्लास की नई इंस्टेंस को प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | searchString | java.lang.String | खोज के लिए सटीक स्ट्रिंग। |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


खोज पैटर्न प्राप्त करता है।


**Returns:**
java.util.regex.Pattern - मैच करने के लिए रेगुलर एक्सप्रेशन पैटर्न।

### getPatternInternal() {#getPatternInternal--}
```
public final System.Text.RegularExpressions.Regex getPatternInternal()
```




**Returns:**
com.aspose.ms.System.Text.RegularExpressions.Regex
### getSkipUnreadableCharacters() {#getSkipUnreadableCharacters--}
```
public final boolean getSkipUnreadableCharacters()
```


एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रिंग तुलना के दौरान अपठनीय अक्षरों को छोड़ दिया जाएगा।


**Returns:**
boolean - एक मान जो दर्शाता है कि स्ट्रिंग तुलना के दौरान अपठनीय अक्षरों को छोड़ दिया जाएगा।

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि स्ट्रिंग तुलना के दौरान अपठनीय अक्षरों को छोड़ दिया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | एक मान जो दर्शाता है कि स्ट्रिंग तुलना के दौरान अपठनीय अक्षरों को छोड़ दिया जाएगा। |
|

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

