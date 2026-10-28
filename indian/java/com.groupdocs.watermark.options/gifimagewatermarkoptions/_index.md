---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "GIF छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 21
url: /hi/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

GIF छवि में वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

निम्न उदाहरण दिखाता है कि GIF छवि के किसी विशेष फ्रेम में वॉटरमार्क कैसे जोड़ा जाए।
>
> ````
> ```
>
>    GifImageLoadOptions loadOptions = new GifImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
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
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` क्लास का एक नया इंस्टेंस निर्दिष्ट फ्रेम इंडेक्स के साथ इनिशियलाइज़ करता है। |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


`[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


`[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` क्लास का एक नया इंस्टेंस निर्दिष्ट फ्रेम इंडेक्स के साथ इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | frameIndex | int | वॉटरमार्क जोड़ने के लिए फ्रेम का इंडेक्स। |
|

