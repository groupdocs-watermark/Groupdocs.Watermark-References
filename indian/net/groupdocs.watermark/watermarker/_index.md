---
title: Watermarker
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: एक दस्तवेज़ में वटरमर्क प्रबंधन के लए एक वर्ग क प्रतनधत्व करत है
type: docs
weight: 3060
url: /hi/net/groupdocs.watermark/watermarker/
---
## Watermarker class

एक दस्तावेज़ में वॉटरमार्क प्रबंधन के लिए एक वर्ग का प्रतिनिधित्व करता है।

```csharp
public class Watermarker : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker) वर्ग के साथ निर्दिष्ट स्ट्रीम. |
| [Watermarker](watermarker#constructor_4)(string) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker) वर्ग निर्दिष्ट दस्तावेज़ पथ के साथ. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker) निर्दिष्ट स्ट्रीम और लोड विकल्प के साथ वर्ग। |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker) वर्ग के साथ निर्दिष्ट stream और सेटिंग्स. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker)वर्ग निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ। |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker) निर्दिष्ट दस्तावेज़ पथ और सेटिंग्स के साथ वर्ग। |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker) वर्ग निर्दिष्ट धारा के साथ, लोड विकल्प और सेटिंग्स. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | का एक नया उदाहरण प्रारंभ करता है[`Watermarker`](../watermarker) वर्ग निर्दिष्ट दस्तावेज़ पथ, लोड विकल्प और सेटिंग्स के साथ। |

## गुण

| नाम | विवरण |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | वॉटरमार्क खोज में शामिल किए जाने वाले सामग्री ऑब्जेक्ट को प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | वॉटरमार्क विकल्पों का उपयोग करके लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | वर्तमान उदाहरण का निपटान करता है। |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | दस्तावेज़ के लिए पूर्वावलोकन छवियां उत्पन्न करता है. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | लौटाता है[`Content`](../../groupdocs.watermark.contents/content) लोड किए गए दस्तावेज़ के लिए ऑब्जेक्ट. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | लोड किए गए दस्तावेज़ के प्रारूप के बारे में जानकारी प्राप्त करता है। |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | दस्तावेज़ में सभी छवियों को ढूँढता है। |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | निर्दिष्ट खोज मापदंड के अनुसार छवियां ढूंढता है। |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | दस्तावेज़ से वॉटरमार्क निकालता है. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | दस्तावेज़ से संग्रह में सभी वॉटरमार्क हटा देता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | सेव ऑप्शन का उपयोग करके दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | सहेजें विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | सहेजें विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | दस्तावेज़ में सभी संभावित वॉटरमार्क खोजता है। |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | निर्दिष्ट खोज मानदंड के अनुसार संभावित वॉटरमार्क खोजता है। |

### उदाहरण

किसी भी समर्थित प्रारूप की सामग्री लोड करें और सहेजें.

```csharp
// फ़ाइल से सामग्री लोड करें।
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // वॉटरमार्क जोड़ने, खोजने या हटाने के लिए वॉटरमार्कर वर्ग के तरीकों का उपयोग करें।

    // परिवर्तनों को सुरक्षित करें।
    watermarker.Save("D:\\output.pdf");
}
```

### यह सभी देखें

* नाम स्थान [GroupDocs.Watermark](../../groupdocs.watermark)
* सभा [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
