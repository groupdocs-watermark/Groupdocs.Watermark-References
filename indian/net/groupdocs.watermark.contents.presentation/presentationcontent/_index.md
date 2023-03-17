---
title: PresentationContent
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: एक PowerPoint दस्तवेज़ क प्रतनधत्व करत है जहँ वटरमर्क रख ज सकत है
type: docs
weight: 830
url: /hi/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

एक PowerPoint दस्तावेज़ का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।

```csharp
public class PresentationContent : Content
```

## गुण

| नाम | विवरण |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | इसके सभी लेआउट स्लाइड्स का संग्रह प्राप्त करता है[`PresentationContent`](../presentationcontent) . |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | इसका मास्टर हैंडआउट स्लाइड प्राप्त करता है[`PresentationContent`](../presentationcontent) . |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | इसके सभी नोट्स स्लाइड के लिए मास्टर स्लाइड प्राप्त करता है[`PresentationContent`](../presentationcontent) . |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | इसकी सभी मास्टर स्लाइड्स का संग्रह प्राप्त करता है[`PresentationContent`](../presentationcontent) . |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | पॉइंट्स में नोट्स स्लाइड की ऊंचाई प्राप्त करता है। |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | बिंदुओं में नोट स्लाइड की चौड़ाई प्राप्त करता है। |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | पॉइंट्स में स्लाइड की ऊंचाई प्राप्त करता है। |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | इसकी सभी स्लाइड्स का संग्रह प्राप्त करता है[`PresentationContent`](../presentationcontent) . |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | बिंदुओं में स्लाइड की चौड़ाई प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | दस्तावेज़ को डिक्रिप्ट करता है. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | वर्तमान उदाहरण का निपटान करता है। |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | दस्तावेज़ को एन्क्रिप्ट करता है. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | सामग्री में सभी छवियों को ढूँढता है। में निर्दिष्ट वस्तुओं में खोज की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | निर्दिष्ट खोज मानदंड के अनुसार छवियां ढूंढता है। खोज निर्दिष्ट वस्तुओं में आयोजित की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | सामग्री में सभी संभावित वॉटरमार्क ढूंढता है। खोज में निर्दिष्ट वस्तुओं में आयोजित किया जाता है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | निर्दिष्ट खोज मानदंड के अनुसार संभावित वॉटरमार्क ढूँढता है। खोज निर्दिष्ट वस्तुओं में आयोजित की जाती है[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### टिप्पणियों

**और अधिक जानें:**

* [प्रस्तुति दस्तावेज़ों में वॉटरमार्क जोड़ें](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [स्लाइड पृष्ठभूमि के साथ काम करना](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### उदाहरण

किसी भी समर्थित प्रकार के PowerPoint दस्तावेज़ को लोड करें और सहेजें.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // किसी विशेष स्लाइड या सभी स्लाइड्स में वॉटरमार्क जोड़ने के लिए ऐड मेथड का उपयोग करें।

    // परिवर्तनों को सुरक्षित करें।
    watermarker.Save(@"D:\output.ppt");
}
```

### यह सभी देखें

* class [Content](../../groupdocs.watermark.contents/content)
* नाम स्थान [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* सभा [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->