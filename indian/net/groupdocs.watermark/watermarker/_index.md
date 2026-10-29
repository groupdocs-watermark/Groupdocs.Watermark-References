---
title: "वॉटरमार्कर"
second_title: "GroupDocs.Watermark for .NET API संदर्भ"
description: "दस्तावेज़ में वॉटरमार्क प्रबंधन के लिए एक क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 3140
url: /hi/net/groupdocs.watermark/watermarker/
---
## Watermarker class

दस्तावेज़ में वॉटरमार्क प्रबंधन के लिए एक क्लास का प्रतिनिधित्व करता है।

```csharp
public class Watermarker : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | निर्दिष्ट स्ट्रीम के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [Watermarker](watermarker#constructor_4)(string) | निर्दिष्ट दस्तावेज़ पथ के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | निर्दिष्ट स्ट्रीम और लोड विकल्पों के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | निर्दिष्ट दस्तावेज़ पथ और सेटिंग्स के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | निर्दिष्ट स्ट्रीम, लोड विकल्प और सेटिंग्स के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | निर्दिष्ट दस्तावेज़ पथ, लोड विकल्प और सेटिंग्स के साथ [`Watermarker`](../watermarker) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | वॉटरमार्क खोज में शामिल किए जाने वाले कंटेंट ऑब्जेक्ट्स को प्राप्त करता या सेट करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है। |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | वॉटरमार्क विकल्पों का उपयोग करके लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है। |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | वर्तमान instance को नष्ट करता है। |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | दस्तावेज़ के लिए प्रीव्यू इमेजेज उत्पन्न करता है। |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | लोड किए गए दस्तावेज़ के लिए [`Content`](../../groupdocs.watermark.contents/content) ऑब्जेक्ट लौटाता है। |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | लोड किए गए दस्तावेज़ के फ़ॉर्मेट के बारे में जानकारी प्राप्त करता है। |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | दस्तावेज़ में सभी इमेजेज खोजता है। |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | निर्दिष्ट खोज मानदंडों के अनुसार इमेजेज खोजता है। |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | दस्तावेज़ से वॉटरमार्क हटाता है। |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | संग्रह में सभी वॉटरमार्क को दस्तावेज़ से हटाता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | सेव विकल्पों का उपयोग करके दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | सेव विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | निर्दिष्ट फ़ाइल स्थान पर सहेज विकल्पों का उपयोग करके दस्तावेज़ को सहेजता है। |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | दस्तावेज़ में सभी संभावित वॉटरमार्क खोजता है। |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क खोजता है। |

### उदाहरण

किसी भी समर्थित फ़ॉर्मेट की सामग्री को लोड और सहेजता है।

```csharp
// फ़ाइल से सामग्री लोड करता है।
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // वॉटरमार्कर क्लास की विधियों का उपयोग करके वॉटरमार्क जोड़ें, खोजें या हटाएँ।

    // परिवर्तनों को सहेजें।
    watermarker.Save("D:\\output.pdf");
}
```

### संबंधित देखें

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
