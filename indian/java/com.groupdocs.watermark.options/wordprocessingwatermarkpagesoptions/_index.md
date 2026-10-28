---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word दस्तावेज़ के पृष्ठों में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 76
url: /hi/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Word दस्तावेज़ के पृष्ठों में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

निम्न उदाहरण दर्शाता है कि Word दस्तावेज़ के किसी विशेष पृष्ठ पर वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` क्लास का नया उदाहरण आरंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ प्राप्त करता है। |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ सेट करता है। |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


`[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` क्लास का नया उदाहरण आरंभ करता है।


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ प्राप्त करता है।


**Returns:**
int[] - वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ।

<br />

*** ** * ** ***

सभी संख्याएँ 1 या उससे अधिक होनी चाहिए। यह प्रॉपर्टी केवल दस्तावेज़ में वॉटरमार्क जोड़ते समय उपयोग की जाती है। यदि यह मान null या खाली है, तो वॉटरमार्क सभी पृष्ठों पर जोड़ा जाता है।

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int[] | वॉटरमार्क जोड़ने के लिए पृष्ठ संख्याएँ। |

<br />

*** ** * ** ***

सभी संख्याएँ 1 या उससे अधिक होनी चाहिए। यह प्रॉपर्टी केवल दस्तावेज़ में वॉटरमार्क जोड़ते समय उपयोग की जाती है। यदि यह मान null या खाली है, तो वॉटरमार्क सभी पृष्ठों पर जोड़ा जाता है।

<br />

|

