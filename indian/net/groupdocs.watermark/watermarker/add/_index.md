---
title: Add
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: लड कए गए दस्तवेज़ में वटरमर्क जड़त है.
type: docs
weight: 30
url: /hi/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है.

```csharp
public void Add(Watermark watermark)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | Watermark | दस्तावेज़ में जोड़ने के लिए वॉटरमार्क। |

### टिप्पणियों

वॉटरमार्क जोड़ने के बारे में अधिक जानें: [वॉटरमार्क जोड़ना](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks) .

### उदाहरण

किसी भी समर्थित प्रकार के दस्तावेज़ में छवि और टेक्स्ट वॉटरमार्क जोड़ें.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.pdf"))
{
    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
    textWatermark.HorizontalAlignment = HorizontalAlignment.Center;
    textWatermark.VerticalAlignment = VerticalAlignment.Top;
    textWatermark.ConsiderParentMargins = true;
    textWatermark.ForegroundColor = Color.Red;
    textWatermark.IsBackground = true;
    textWatermark.Opacity = 0.5;
    watermarker.Add(textWatermark);

    using (ImageWatermark imageWatermark = new ImageWatermark(@"D:\draft.png"))
    {
        imageWatermark.HorizontalAlignment = HorizontalAlignment.Center;
        imageWatermark.VerticalAlignment = VerticalAlignment.Bottom;
        imageWatermark.ConsiderParentMargins = true;
        imageWatermark.IsBackground = true;
        imageWatermark.Opacity = 0.5;
        watermarker.Add(imageWatermark);
    }

    watermarker.Save(@"D:\output.pdf");
}
```

### यह सभी देखें

* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

वॉटरमार्क विकल्पों का उपयोग करके लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है.

```csharp
public void Add(Watermark watermark, WatermarkOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | Watermark | दस्तावेज़ में जोड़ने के लिए वॉटरमार्क। |
| options | WatermarkOptions | वॉटरमार्क जोड़ते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियों

वॉटरमार्क जोड़ने के बारे में अधिक जानें [वॉटरमार्क जोड़ना](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks) .

### उदाहरण

एक पीडीएफ दस्तावेज़ के एक विशेष पृष्ठ पर एक छवि वॉटरमार्क जोड़ें।

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### यह सभी देखें

* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->