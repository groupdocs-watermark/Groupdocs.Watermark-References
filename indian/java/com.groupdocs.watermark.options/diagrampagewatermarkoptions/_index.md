---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Visio दस्तावेज़ के किसी विशेष पृष्ठ पर आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Visio दस्तावेज़ के किसी विशेष पृष्ठ पर आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

निम्न उदाहरण दर्शाता है कि Visio दस्तावेज़ के पहले पृष्ठ पर संरक्षित वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` क्लास का नया उदाहरण आरंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक प्राप्त करता है। |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक सेट करता है। |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


`[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` क्लास का नया उदाहरण आरंभ करता है।


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक।

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए पृष्ठ सूचकांक। |
|

