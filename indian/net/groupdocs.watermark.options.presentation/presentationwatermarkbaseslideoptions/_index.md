---
title: PresentationWatermarkBaseSlideOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: प्रस्तुत दस्तवेज़ में वटरमर्क जड़ने के वकल्प के लए आधर वर्ग.
type: docs
weight: 1990
url: /hi/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

प्रस्तुति दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्प के लिए आधार वर्ग.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | उस वर्णनात्मक (वैकल्पिक) पाठ को प्राप्त या सेट करता है जो किसी आकृति से जुड़ा होगा। |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | का मान प्राप्त या सेट करता है[`PresentationImageEffects`](../presentationimageeffects) या [`PresentationTextEffects`](../presentationtexteffects) वॉटरमार्क पर लागू होने वाले प्रभावों के लिए. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | यह इंगित करने वाला मान प्राप्त या सेट करता है कि क्या PowerPoint में आकृति का संपादन प्रतिबंधित है। |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | नाम को आकार देता है या सेट करता है। |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि टेक्स्ट वॉटरमार्क वर्ण अपठनीय वर्णों के साथ मिश्रित हैं या नहीं। |

### टिप्पणियों

**और अधिक जानें:**

* [प्रस्तुति दस्तावेज़ों में वॉटरमार्क जोड़ें](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### उदाहरण

पावर प्वाइंट प्रस्तुति की विभिन्न सर्विस स्लाइड्स में वॉटरमार्क जोड़ें।

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // सभी मास्टर स्लाइड्स में वॉटरमार्क जोड़ें
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // गलती करना
    watermarker.Add(watermark, masterSlideOptions);

    // सभी लेआउट स्लाइड्स में वॉटरमार्क जोड़ें
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // गलती करना
    watermarker.Add(watermark, layoutSlideOptions);

    // सभी नोट्स स्लाइड्स में वॉटरमार्क जोड़ें
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // गलती करना
    watermarker.Add(watermark, noteSlideOptions);

    // हैंडआउट मास्टर में वॉटरमार्क जोड़ें
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // नोट्स मास्टर में वॉटरमार्क जोड़ें
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### यह सभी देखें

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* नाम स्थान [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* सभा [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
