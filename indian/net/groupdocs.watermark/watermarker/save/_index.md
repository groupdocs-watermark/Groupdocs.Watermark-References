---
title: "सहेजें"
second_title: "GroupDocs.Watermark for .NET API संदर्भ"
description: "दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है।"
type: docs
weight: 100
url: /hi/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

```csharp
public WatermarkResult Save()
```

### टिप्पणियाँ

दस्तावेज़ सहेजने के बारे में अधिक जानें [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)।

### उदाहरण

ईमेल संदेश के बॉडी/विषय से विशेष टेक्स्ट अंशों को हटाएँ और ईमेल संदेश को सहेजें।

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // ध्यान दें, खोज केवल तभी की जाती है जब आप TextSearchCriteria इंस्टेंस को Search मेथड में पास करें
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // पाए गए टेक्स्ट अंशों को हटाएँ
    watermarker.Remove(watermarks);
    // परिवर्तनों को सहेजें
    watermarker.Save();
}
```

### संबंधित देखें

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

```csharp
public WatermarkResult Save(string filePath)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ डेटा को सहेजने के लिए फ़ाइल पथ। |

### टिप्पणियाँ

दस्तावेज़ सहेजने के बारे में अधिक जानें [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)।

### उदाहरण

वॉटरमार्क जोड़ें और दस्तावेज़ को किसी अन्य फ़ाइल में सहेजें।

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### संबंधित देखें

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public WatermarkResult Save(Stream document)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | दस्तावेज़ डेटा को सहेजने के लिए स्ट्रीम। |

### टिप्पणियाँ

दस्तावेज़ सहेजने के बारे में अधिक जानें [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)।

### उदाहरण

वॉटरमार्क जोड़ें और दस्तावेज़ को मेमोरी स्ट्रीम में सहेजें।

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### संबंधित देखें

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

सेव विकल्पों का उपयोग करके दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

```csharp
public WatermarkResult Save(SaveOptions options)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| options | SaveOptions | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियाँ

दस्तावेज़ सहेजने के बारे में अधिक जानें [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)।

### उदाहरण

डिफ़ॉल्ट [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) के साथ वॉटरमार्क जोड़ें और दस्तावेज़ सहेजें।

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### संबंधित देखें

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

निर्दिष्ट फ़ाइल स्थान पर सहेज विकल्पों का उपयोग करके दस्तावेज़ को सहेजता है।

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ डेटा को सहेजने के लिए फ़ाइल पथ। |
| options | SaveOptions | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियाँ

दस्तावेज़ सहेजने के बारे में अधिक जानें [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)।

### उदाहरण

डिफ़ॉल्ट [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) के साथ वॉटरमार्क जोड़ें और दस्तावेज़ को किसी अन्य फ़ाइल में सहेजें।

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### संबंधित देखें

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

सेव विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | दस्तावेज़ डेटा को सहेजने के लिए स्ट्रीम। |
| options | SaveOptions | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियाँ

दस्तावेज़ सहेजने के बारे में अधिक जानें [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents)।

### उदाहरण

डिफ़ॉल्ट [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) के साथ वॉटरमार्क जोड़ें और दस्तावेज़ को मेमोरी स्ट्रीम में सहेजें।

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### संबंधित देखें

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
