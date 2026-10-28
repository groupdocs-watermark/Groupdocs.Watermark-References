---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "प्रेजेंटेशन दस्तावेज़ स्लाइड में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 46
url: /hi/java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

प्रेजेंटेशन दस्तावेज़ स्लाइड में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

निम्नलिखित उदाहरण दर्शाता है कि Power Point प्रस्तुति की किसी विशिष्ट स्लाइड में वॉटरमार्क कैसे जोड़ा जाए।
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.ppt", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>  
>    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
>    options.setSlideIndex(0);
>    options.setLocked(false); // default
>    options.setProtectWithUnreadableCharacters(false); // default
>    options.setName(null); // default
>    options.setAlternativeText(null); // default
>    
>    watermarker.save("C:\\Documents\\watermarked_test.ppt");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)` क्लास का नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | वॉटरमार्क जोड़ने के लिए स्लाइड का सूचकांक प्राप्त करता है। |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | वॉटरमार्क जोड़ने के लिए स्लाइड का सूचकांक सेट करता है। |
|
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


`[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)` क्लास का नया उदाहरण प्रारंभ करता है।


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


वॉटरमार्क जोड़ने के लिए स्लाइड का सूचकांक प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए स्लाइड का सूचकांक।

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


वॉटरमार्क जोड़ने के लिए स्लाइड का सूचकांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए स्लाइड का सूचकांक। |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

