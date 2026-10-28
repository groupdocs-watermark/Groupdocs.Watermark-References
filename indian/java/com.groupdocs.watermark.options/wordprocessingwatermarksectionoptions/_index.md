---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word दस्तावेज़ सेक्शन में शैप वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 77
url: /hi/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Word दस्तावेज़ सेक्शन में शैप वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

निम्न उदाहरण दिखाता है कि कैसे एक Word दस्तावेज़ के किसी विशेष अनुभाग में वॉटरमार्क जोड़ा जाए।
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` क्लास का नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक प्राप्त करता है। |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक सेट करता है। |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


`[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` क्लास का नया उदाहरण प्रारंभ करता है।


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए सेक्शन का इंडेक्स।

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


वॉटरमार्क जोड़ने के लिए अनुभाग का सूचकांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए सेक्शन का इंडेक्स। |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

