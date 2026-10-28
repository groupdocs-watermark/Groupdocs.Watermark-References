---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Visio दस्तावेज़ में आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प का प्रतिनिधित्व करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Visio दस्तावेज़ में आकार वॉटरमार्क जोड़ते समय वॉटरमार्क जोड़ने के विकल्प का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

निम्न उदाहरण दर्शाता है कि Visio दस्तावेज़ के सभी पृष्ठों में संरक्षित वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
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
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` क्लास का नया उदाहरण आरंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | वॉटरमार्क किन पृष्ठों पर जोड़ा जाना चाहिए, यह निर्दिष्ट करने वाला मान प्राप्त करता है। |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | वॉटरमार्क किन पृष्ठों पर जोड़ा जाना चाहिए, यह निर्दिष्ट करने वाला मान प्राप्त करता है या सेट करता है। |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


`[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` क्लास का नया उदाहरण आरंभ करता है।


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


वॉटरमार्क किन पृष्ठों पर जोड़ा जाना चाहिए, यह निर्दिष्ट करने वाला मान प्राप्त करता है।


**Returns:**
int - वह `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, जो निर्धारित करता है कि वॉटरमार्क किन पृष्ठों पर जोड़ा जाना चाहिए।

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


वॉटरमार्क किन पृष्ठों पर जोड़ा जाना चाहिए, यह निर्दिष्ट करने वाला मान प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | int | वह `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, जो निर्धारित करता है कि वॉटरमार्क किन पृष्ठों पर जोड़ा जाना चाहिए। |
|

