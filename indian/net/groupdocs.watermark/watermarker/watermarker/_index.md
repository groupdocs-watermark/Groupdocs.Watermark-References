---
title: Watermarker
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: क एक नय उदहरण प्ररंभ करत हैWatermarkergroupdocs.watermark/watermarker वर्ग नर्दष्ट दस्तवेज़ पथ के सथ.
type: docs
weight: 10
url: /hi/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker) वर्ग निर्दिष्ट दस्तावेज़ पथ के साथ.

```csharp
public Watermarker(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ को लोड करने के लिए फ़ाइल पथ। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

किसी भी समर्थित प्रारूप की सामग्री लोड करें और सहेजें.

```csharp
// फ़ाइल से सामग्री लोड करें।
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // वॉटरमार्क जोड़ने, खोजने या हटाने के लिए वॉटरमार्कर वर्ग के तरीकों का उपयोग करें।

    // दस्तावेज़ को सहेजें।
    watermarker.Save("D:\\output.pdf");
}
```

### यह सभी देखें

* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker)वर्ग निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ।

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ को लोड करने के लिए फ़ाइल पथ। |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

पासवर्ड का उपयोग कर एन्क्रिप्टेड पीडीएफ दस्तावेज़ लोड करें।

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker) निर्दिष्ट दस्तावेज़ पथ और सेटिंग्स के साथ वर्ग।

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ को लोड करने के लिए फ़ाइल पथ। |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

विश्व स्तर पर खोजने योग्य ऑब्जेक्ट सेट करें (उसके बाद लोड किए जाने वाले सभी दस्तावेज़ों के लिए).

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

        // पाए गए वॉटरमार्क के साथ काम करने का कोड यहां जाता है।
    }
}
```

### यह सभी देखें

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker) वर्ग निर्दिष्ट दस्तावेज़ पथ, लोड विकल्प और सेटिंग्स के साथ।

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | दस्तावेज़ को लोड करने के लिए फ़ाइल पथ। |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें: [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

ईमेल संदेश के मुख्य भाग/विषय में विशेष पाठ खंड खोजें।

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
    // नोट, खोज तभी की जाती है जब आप TextSearchCriteria उदाहरण को खोज विधि में पास करते हैं
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // पाए गए पाठ के टुकड़े निकालें
    watermarks.Clear();
    // परिवर्तनों को सुरक्षित करें
    watermarker.Save();
}
```

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker) वर्ग के साथ निर्दिष्ट स्ट्रीम.

```csharp
public Watermarker(Stream document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | वह स्ट्रीम जिससे दस्तावेज़ लोड करना है. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

किसी भी समर्थित प्रारूप के दस्तावेज़ को लोड करें और सहेजें.

```csharp
// स्ट्रीम से सामग्री लोड करें।
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // वॉटरमार्क जोड़ने, खोजने या हटाने के लिए वॉटरमार्कर वर्ग के तरीकों का उपयोग करें।

    // परिवर्तनों को सुरक्षित करें।
    watermarker.Save(outputStream);
}
```

### यह सभी देखें

* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker) निर्दिष्ट स्ट्रीम और लोड विकल्प के साथ वर्ग।

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | वह स्ट्रीम जिससे दस्तावेज़ लोड करना है. |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

पासवर्ड का उपयोग कर एन्क्रिप्टेड पीडीएफ दस्तावेज़ लोड करें

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker) वर्ग के साथ निर्दिष्ट stream और सेटिंग्स.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | वह स्ट्रीम जिससे दस्तावेज़ लोड करना है. |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

विश्व स्तर पर खोजने योग्य ऑब्जेक्ट सेट करें (उसके बाद लोड किए जाने वाले सभी दस्तावेज़ों के लिए).

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

        // पाए गए वॉटरमार्क के साथ काम करने का कोड यहां जाता है।
    }
}
```

### यह सभी देखें

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../../watermarker) वर्ग निर्दिष्ट धारा के साथ, लोड विकल्प और सेटिंग्स.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | वह स्ट्रीम जिससे दस्तावेज़ लोड करना है. |
| options | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
| settings | WatermarkerSettings | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | आपूर्ति किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | दिया गया पासवर्ड गलत है। |

### टिप्पणियों

दस्तावेज़ लोड करने के बारे में अधिक जानें [दस्तावेज़ लोड हो रहे हैं](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### उदाहरण

ईमेल संदेश के मुख्य भाग/विषय में विशेष पाठ खंड खोजें।

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
    // नोट, खोज तभी की जाती है जब आप TextSearchCriteria उदाहरण को खोज विधि में पास करते हैं
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // पाए गए पाठ के टुकड़े निकालें
    watermarks.Clear();
    // परिवर्तनों को सुरक्षित करें
    watermarker.Save();
}
```

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
