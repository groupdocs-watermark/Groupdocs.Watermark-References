---
title: Remove
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: दस्तवेज़ से वटरमर्क नकलत है.
type: docs
weight: 90
url: /hi/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

दस्तावेज़ से वॉटरमार्क निकालता है.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | हटाने के लिए वॉटरमार्क। |

### टिप्पणियों

वॉटरमार्क हटाने के बारे में अधिक जानें: [पाए गए वॉटरमार्क को हटाना](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks) .

### उदाहरण

किसी भी समर्थित प्रकार के दस्तावेज़ से विशेष पाठ या छवि वाले पहले संभावित वॉटरमार्क को ढूंढें और निकालें।

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### यह सभी देखें

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

दस्तावेज़ से संग्रह में सभी वॉटरमार्क हटा देता है।

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | हटाने के लिए वॉटरमार्क का संग्रह। |

### टिप्पणियों

वॉटरमार्क हटाने के बारे में अधिक जानें [पाए गए वॉटरमार्क को हटाना](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks) .

### उदाहरण

किसी भी समर्थित प्रकार के दस्तावेज़ से विशेष पाठ या छवि वाले सभी संभावित वॉटरमार्क खोजें और निकालें।

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### यह सभी देखें

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
