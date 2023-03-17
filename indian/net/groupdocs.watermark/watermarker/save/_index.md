---
title: Save
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: दस्तवेज़ डेट क अंतर्नहत स्ट्रम में सहेजत है.
type: docs
weight: 100
url: /hi/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है.

```csharp
public void Save()
```

### टिप्पणियों

दस्तावेज़ों को सहेजने के बारे में अधिक जानें [दस्तावेजों को सहेजना](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### उदाहरण

ईमेल संदेश के मुख्य भाग/विषय से विशेष पाठ खंड निकालें और ईमेल संदेश सहेजें।

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // नोट, खोज तभी की जाती है जब आप TextSearchCriteria उदाहरण को खोज विधि में पास करते हैं
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // पाए गए पाठ के टुकड़े निकालें
    watermarker.Remove(watermarks);
    // परिवर्तनों को सुरक्षित करें
    watermarker.Save();
}
```

### यह सभी देखें

* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

```csharp
public void Save(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ डेटा को सहेजने के लिए फ़ाइल पथ। |

### टिप्पणियों

दस्तावेज़ों को सहेजने के बारे में अधिक जानें [दस्तावेजों को सहेजना](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### उदाहरण

वॉटरमार्क जोड़ें और दस्तावेज़ को दूसरी फ़ाइल में सहेजें.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### यह सभी देखें

* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | दस्तावेज़ डेटा को सहेजने के लिए स्ट्रीम। |

### टिप्पणियों

दस्तावेज़ों को सहेजने के बारे में अधिक जानें [दस्तावेजों को सहेजना](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### उदाहरण

वॉटरमार्क जोड़ें और दस्तावेज़ को मेमोरी स्ट्रीम में सहेजें.

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

### यह सभी देखें

* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

सेव ऑप्शन का उपयोग करके दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

```csharp
public void Save(SaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | SaveOptions | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियों

दस्तावेज़ों को सहेजने के बारे में अधिक जानें [दस्तावेजों को सहेजना](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### उदाहरण

वॉटरमार्क जोड़ें और दस्तावेज़ को डिफ़ॉल्ट रूप से सहेजें[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### यह सभी देखें

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

सहेजें विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

```csharp
public void Save(string filePath, SaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ डेटा को सहेजने के लिए फ़ाइल पथ। |
| options | SaveOptions | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियों

दस्तावेज़ों को सहेजने के बारे में अधिक जानें [दस्तावेजों को सहेजना](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### उदाहरण

वॉटरमार्क जोड़ें और दस्तावेज़ को डिफ़ॉल्ट रूप से किसी अन्य फ़ाइल में सहेजें[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### यह सभी देखें

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

सहेजें विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream document, SaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | दस्तावेज़ डेटा को सहेजने के लिए स्ट्रीम। |
| options | SaveOptions | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियों

दस्तावेज़ों को सहेजने के बारे में अधिक जानें [दस्तावेजों को सहेजना](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### उदाहरण

वॉटरमार्क जोड़ें और दस्तावेज़ को डिफ़ॉल्ट रूप से मेमोरी स्ट्रीम में सहेजें[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

### यह सभी देखें

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
