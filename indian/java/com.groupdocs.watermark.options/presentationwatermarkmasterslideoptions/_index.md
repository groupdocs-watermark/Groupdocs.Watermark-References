---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Presentation दस्तावेज़ मास्टर स्लाइड में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 43
url: /hi/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Presentation दस्तावेज़ मास्टर स्लाइड में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

`[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)` में उपयोग उदाहरण देखें।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | एक नया उदाहरण आरंभ करता है `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` वर्ग का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | वॉटरमार्क जोड़ने के लिए मास्टर स्लाइड का सूचकांक प्राप्त करता है। |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | वॉटरमार्क जोड़ने के लिए मास्टर स्लाइड का सूचकांक सेट करता है। |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


एक नया उदाहरण आरंभ करता है `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` वर्ग का।


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


वॉटरमार्क जोड़ने के लिए मास्टर स्लाइड का सूचकांक प्राप्त करता है।


**Returns:**
int - वह सूचकांक जो वॉटरमार्क जोड़ने के लिए मास्टर स्लाइड को दर्शाता है।

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


वॉटरमार्क जोड़ने के लिए मास्टर स्लाइड का सूचकांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए मास्टर स्लाइड का सूचकांक। |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

