---
title: WatermarkableImage
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: एक दस्तवेज़ के अंदर एक छव क प्रतनधत्व करत है
type: docs
weight: 420
url: /hi/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

एक दस्तावेज़ के अंदर एक छवि का प्रतिनिधित्व करता है।

```csharp
public abstract class WatermarkableImage : ContentPart
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | इसकी ऊंचाई प्राप्त करता है[`WatermarkableImage`](../watermarkableimage) पिक्सेल में. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | इसकी चौड़ाई प्राप्त करता है[`WatermarkableImage`](../watermarkableimage) पिक्सेल में. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | इसमें वॉटरमार्क जोड़ता है[`WatermarkableImage`](../watermarkableimage) . यह विधि मानती है कि वॉटरमार्क ऑफ़सेट और आकार पिक्सेल में मापा जाता है (यदि उन्हें असाइन किया गया है)। |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | सामग्री में सभी छवियों को ढूँढता है। में निर्दिष्ट वस्तुओं में खोज की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | निर्दिष्ट खोज मानदंड के अनुसार छवियां ढूंढता है। खोज निर्दिष्ट वस्तुओं में आयोजित की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | छवि को बाइट सरणी के रूप में प्राप्त करता है। |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | सामग्री में सभी संभावित वॉटरमार्क ढूंढता है। खोज में निर्दिष्ट वस्तुओं में आयोजित किया जाता है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | निर्दिष्ट खोज मानदंड के अनुसार संभावित वॉटरमार्क ढूँढता है। खोज निर्दिष्ट वस्तुओं में आयोजित की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### टिप्पणियों

**और अधिक जानें:**

* [दस्तावेज़ के अंदर छवियों में वॉटरमार्क जोड़ना](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### उदाहरण

किसी भी समर्थित प्रकार के दस्तावेज़ के अंदर सभी छवियों में वॉटरमार्क जोड़ें.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // टेक्स्ट या इमेज वॉटरमार्क को इनिशियलाइज़ करें।
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // सामग्री में सभी चित्र खोजें।
    WatermarkableImageCollection images = watermarker.GetImages();

    // वॉटरमार्क जोड़ें।
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // परिवर्तनों को सुरक्षित करें।
    watermarker.Save(@"D:\output.doc");
}
```

### यह सभी देखें

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* नाम स्थान [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* सभा [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->