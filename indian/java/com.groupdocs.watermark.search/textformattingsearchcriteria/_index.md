---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "टेक्स्ट फ़ॉर्मेटिंग द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 66
url: /hi/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

टेक्स्ट फ़ॉर्मेटिंग द्वारा फ़िल्टर करने की अनुमति देने वाले मानदंड का प्रतिनिधित्व करता है।

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

निम्न उदाहरण दर्शाता है कि कैसे किसी विशेष
पाठ स्वरूपण (दस्तावेज़ प्रकार की परवाह किए बिना)।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.doc");
>    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
>
>    criteria.setForegroundColorRange(new ColorRange());
>    criteria.getForegroundColorRange().setMinHue(-5);
>    criteria.getForegroundColorRange().setMaxHue(10);
>    criteria.getForegroundColorRange().setMinBrightness(0.01f);
>    criteria.getForegroundColorRange().setMaxBrightness(0.99f);
>    criteria.setBackgroundColorRange(new ColorRange());
>    criteria.getBackgroundColorRange().setEmpty(true);
>    criteria.setFontName("Arial");
>    criteria.setMinFontSize(19);
>    criteria.setMaxFontSize(42);
>    criteria.setFontBold(true);
>
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
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
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | एक नया उदाहरण प्रारंभ करता है `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | पाठ अग्रभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा प्राप्त करता है। |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | पाठ अग्रभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा सेट करता है। |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | पाठ पृष्ठभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा प्राप्त करता है। |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | पाठ पृष्ठभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा सेट करता है। |
|
|  | [getFontName()](#getFontName--) | संभव वॉटरमार्क पाठ स्वरूपण में उपयोग किए जाने वाले फ़ॉन्ट का नाम प्राप्त करता है। |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | संभावित वॉटरमार्क पाठ स्वरूपण में उपयोग किए जाने वाले फ़ॉन्ट का नाम सेट करता है। |
|
|  | [getMinFontSize()](#getMinFontSize--) | फ़ॉन्ट आकार का प्रारंभिक मान प्राप्त करता है। |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | फ़ॉन्ट आकार का प्रारंभिक मान सेट करता है। |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | फ़ॉन्ट आकार का अंतिम मान प्राप्त करता है। |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | फ़ॉन्ट आकार का अंतिम मान सेट करता है। |
|
|  | [getFontBold()](#getFontBold--) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के बोल्ड होने का संकेत देने वाला मान प्राप्त करता है। |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के बोल्ड होने का संकेत देने वाला मान सेट करता है। |
|
|  | [getFontItalic()](#getFontItalic--) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के इटैलिक होने का संकेत देने वाला मान प्राप्त करता है। |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के इटैलिक होने का संकेत देने वाला मान सेट करता है। |
|
|  | [getFontUnderline()](#getFontUnderline--) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के अंडरलाइन होने का संकेत देने वाला मान प्राप्त करता है। |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के अंडरलाइन होने का संकेत देने वाला मान सेट करता है। |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के स्ट्राइकआउट होने का संकेत देने वाला मान प्राप्त करता है। |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के स्ट्राइकआउट होने का संकेत देने वाला मान सेट करता है। |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


एक नया उदाहरण प्रारंभ करता है `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` क्लास का।


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


पाठ अग्रभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा प्राप्त करता है।


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


पाठ अग्रभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | पाठ अग्रभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा। |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


पाठ पृष्ठभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा प्राप्त करता है।


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


पाठ पृष्ठभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | पाठ पृष्ठभूमि रंग द्वारा वॉटरमार्क को फ़िल्टर करने के लिए उपयोग किए जाने वाले रंगों की सीमा। |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


संभव वॉटरमार्क पाठ स्वरूपण में उपयोग किए जाने वाले फ़ॉन्ट का नाम प्राप्त करता है।


**Returns:**
java.lang.String - डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है।

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


संभावित वॉटरमार्क पाठ स्वरूपण में उपयोग किए जाने वाले फ़ॉन्ट का नाम सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है। |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


फ़ॉन्ट आकार का प्रारंभिक मान प्राप्त करता है।


**Returns:**
float - फ़ॉन्ट आकार का प्रारंभिक मान।

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


फ़ॉन्ट आकार का प्रारंभिक मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | फ़ॉन्ट आकार का प्रारंभिक मान। |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


फ़ॉन्ट आकार का अंतिम मान प्राप्त करता है।


**Returns:**
float - फ़ॉन्ट आकार का अंतिम मान।

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


फ़ॉन्ट आकार का अंतिम मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | फ़ॉन्ट आकार का अंतिम मान। |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के बोल्ड होने का संकेत देने वाला मान प्राप्त करता है।


**Returns:**
java.lang.Boolean - डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है।

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के बोल्ड होने का संकेत देने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Boolean | डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है। |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के इटैलिक होने का संकेत देने वाला मान प्राप्त करता है।


**Returns:**
java.lang.Boolean - डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है।

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के इटैलिक होने का संकेत देने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Boolean | डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है। |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के अंडरलाइन होने का संकेत देने वाला मान प्राप्त करता है।


**Returns:**
java.lang.Boolean - डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है।

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के अंडरलाइन होने का संकेत देने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Boolean | डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है। |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के स्ट्राइकआउट होने का संकेत देने वाला मान प्राप्त करता है।


**Returns:**
java.lang.Boolean - डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है।

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


वॉटरमार्क पाठ स्वरूपण में उपयोग किए गए फ़ॉन्ट के स्ट्राइकआउट होने का संकेत देने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Boolean | डिफ़ॉल्ट मान null है, जिसका अर्थ है कि फ़िल्टर लागू नहीं किया गया है। |
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

