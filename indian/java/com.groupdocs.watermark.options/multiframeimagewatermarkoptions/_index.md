---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "मल्टी-फ़्रेम छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 26
url: /hi/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

मल्टी-फ़्रेम छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

निम्न उदाहरण दर्शाता है कि मल्टी-फ़्रेम छवि के एक विशिष्ट फ्रेम में वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` क्लास का नया उदाहरण निर्दिष्ट फ्रेम इंडेक्स के साथ प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स प्राप्त करता है। |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स सेट करता है। |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


`[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` क्लास का नया उदाहरण प्रारंभ करता है।


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


`[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` क्लास का नया उदाहरण निर्दिष्ट फ्रेम इंडेक्स के साथ प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | frameIndex | int | वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स। |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स।

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स। |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

