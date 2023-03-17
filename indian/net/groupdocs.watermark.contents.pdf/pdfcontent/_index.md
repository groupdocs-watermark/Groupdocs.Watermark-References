---
title: PdfContent
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: एक पडएफ दस्तवेज़ क प्रतनधत्व करत है जहं वटरमर्क रख ज सकत है
type: docs
weight: 610
url: /hi/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

एक पीडीएफ दस्तावेज़ का प्रतिनिधित्व करता है जहां वॉटरमार्क रखा जा सकता है।

```csharp
public class PdfContent : Content
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | इसके सभी अनुलग्नकों का संग्रह प्राप्त करता है[`PdfContent`](../pdfcontent) . |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | वॉटरमार्क जोड़ने के दौरान उपयोग किए जाने वाले पीडीएफ पेज मार्जिन को प्राप्त या सेट करता है। |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | इसके सभी पृष्ठों का संग्रह प्राप्त करता है[`PdfContent`](../pdfcontent) . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | सामग्री को डिक्रिप्ट करता है। |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | वर्तमान उदाहरण का निपटान करता है। |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | उपयोगकर्ता पासवर्ड और स्वामी पासवर्ड के समान पासवर्ड का उपयोग करके दस्तावेज़ को एन्क्रिप्ट करता है। |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | सामग्री को एन्क्रिप्ट करता है। |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | सामग्री में सभी छवियों को ढूँढता है। में निर्दिष्ट वस्तुओं में खोज की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | निर्दिष्ट खोज मानदंड के अनुसार छवियां ढूंढता है। खोज निर्दिष्ट वस्तुओं में आयोजित की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | सभी सामग्री पृष्ठों को छवियों में परिवर्तित करता है। |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | सामग्री में सभी संभावित वॉटरमार्क ढूंढता है। खोज में निर्दिष्ट वस्तुओं में आयोजित किया जाता है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | निर्दिष्ट खोज मानदंड के अनुसार संभावित वॉटरमार्क ढूँढता है। खोज निर्दिष्ट वस्तुओं में आयोजित की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### टिप्पणियों

**और अधिक जानें:**

* [पीडीएफ दस्तावेजों में वॉटरमार्क जोड़ें](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [पीडीएफ दस्तावेज़ में मौजूदा वस्तुएं](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [दस्तावेज़ या पृष्ठ को व्यवस्थित करें](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [पीडीएफ दस्तावेज़ में वॉटरमार्क](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### यह सभी देखें

* class [Content](../../groupdocs.watermark.contents/content)
* नाम स्थान [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* सभा [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->