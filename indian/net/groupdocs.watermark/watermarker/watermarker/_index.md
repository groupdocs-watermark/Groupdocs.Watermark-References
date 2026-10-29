---
title: "वॉटरमार्कर"
second_title: "GroupDocs.Watermark for .NET API संदर्भ"
description: "निर्दिष्ट दस्तावेज़ पथ के साथ Watermarkergroupdocs.watermark/watermarker क्लास का एक नया इंस्टेंस प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

निर्दिष्ट दस्तावेज़ पथ के साथ [`Watermarker`](../../watermarker) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(string filePath)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड करना](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### उदाहरण

किसी भी समर्थित फ़ॉर्मेट की सामग्री को लोड और सहेजता है।

```csharp
// फ़ाइल से सामग्री लोड करता है।
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // वॉटरमार्कर क्लास की विधियों का उपयोग करके वॉटरमार्क जोड़ें, खोजें या हटाएँ।

    // दस्तावेज़ सहेजें।
    watermarker.Save("D:\\output.pdf");
}
```

### संबंधित देखें

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ [`Watermarker`](../../watermarker) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड करना](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### उदाहरण

पासवर्ड का उपयोग करके एन्क्रिप्टेड PDF दस्तावेज़ लोड करें।

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

निर्दिष्ट दस्तावेज़ पथ और सेटिंग्स के साथ [`Watermarker`](../../watermarker) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड करना](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### उदाहरण

खोज योग्य ऑब्जेक्ट्स को वैश्विक रूप से सेट करें (उन सभी दस्तावेज़ों के लिए जो उसके बाद लोड किए जाएंगे)।

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // पाए गए वॉटरमार्क के साथ काम करने के लिए कोड यहाँ जाता है।
    }
}
```

### संबंधित देखें

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

निर्दिष्ट दस्तावेज़ पथ, लोड विकल्प और सेटिंग्स के साथ [`Watermarker`](../../watermarker) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड करना](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### उदाहरण

ईमेल संदेश के बॉडी/विषय में विशेष टेक्स्ट अंश खोजें।

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // ध्यान दें, खोज केवल तभी की जाती है जब आप TextSearchCriteria इंस्टेंस को Search मेथड में पास करें
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // पाए गए टेक्स्ट अंशों को हटाएँ
    watermarks.Clear();
    // परिवर्तनों को सहेजें
    watermarker.Save();
}
```

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

निर्दिष्ट स्ट्रीम के साथ [`Watermarker`](../../watermarker) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(Stream document)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)।

### उदाहरण

किसी भी समर्थित फ़ॉर्मेट का दस्तावेज़ लोड और सहेजें।

```csharp
// स्ट्रीम से सामग्री लोड करें।
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // वॉटरमार्कर क्लास की विधियों का उपयोग करके वॉटरमार्क जोड़ें, खोजें या हटाएँ।

    // परिवर्तनों को सहेजें।
    watermarker.Save(outputStream);
}
```

### संबंधित देखें

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

निर्दिष्ट स्ट्रीम और लोड विकल्पों के साथ [`Watermarker`](../../watermarker) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)।

### उदाहरण

पासवर्ड का उपयोग करके एन्क्रिप्टेड PDF दस्तावेज़ लोड करें

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ [`Watermarker`](../../watermarker) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)।

### उदाहरण

खोज योग्य ऑब्जेक्ट्स को वैश्विक रूप से सेट करें (उन सभी दस्तावेज़ों के लिए जो उसके बाद लोड किए जाएंगे)।

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // पाए गए वॉटरमार्क के साथ काम करने के लिए कोड यहाँ जाता है।
    }
}
```

### संबंधित देखें

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

निर्दिष्ट स्ट्रीम, लोड विकल्प और सेटिंग्स के साथ [`Watermarker`](../../watermarker) क्लास का नया इंस्टेंस प्रारंभ करता है।

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| पैरामीटर | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | प्रदान किया गया पासवर्ड गलत है। |

### टिप्पणियाँ

दस्तावेज़ लोड करने के बारे में अधिक जानें [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)।

### उदाहरण

ईमेल संदेश के बॉडी/विषय में विशेष टेक्स्ट अंश खोजें।

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // ध्यान दें, खोज केवल तभी की जाती है जब आप TextSearchCriteria इंस्टेंस को Search मेथड में पास करें
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // पाए गए टेक्स्ट अंशों को हटाएँ
    watermarks.Clear();
    // परिवर्तनों को सहेजें
    watermarker.Save();
}
```

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
