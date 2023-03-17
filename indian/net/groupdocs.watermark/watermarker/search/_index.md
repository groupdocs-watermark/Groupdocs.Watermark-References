---
title: Search
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: दस्तवेज़ में सभ संभवत वटरमर्क खजत है
type: docs
weight: 110
url: /hi/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

दस्तावेज़ में सभी संभावित वॉटरमार्क खोजता है।

```csharp
public PossibleWatermarkCollection Search()
```

### प्रतिलाभ की मात्रा

संभावित वॉटरमार्क का संग्रह।

### टिप्पणियों

में निर्दिष्ट वस्तुओं में खोज की जाती है[`SearchableObjects`](../searchableobjects).

वॉटरमार्क खोजने के बारे में अधिक जानें [वॉटरमार्क खोज रहे हैं](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### उदाहरण

किसी समर्थित प्रकार के दस्तावेज़ में संभावित वॉटरमार्क की गणना करें.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### यह सभी देखें

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

निर्दिष्ट खोज मानदंड के अनुसार संभावित वॉटरमार्क खोजता है।

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchCriteria | SearchCriteria | उपयोग करने के लिए खोज मानदंड। |

### प्रतिलाभ की मात्रा

संभावित वॉटरमार्क का संग्रह।

### टिप्पणियों

में निर्दिष्ट वस्तुओं में खोज की जाती है[`SearchableObjects`](../searchableobjects).

वॉटरमार्क खोजने के बारे में अधिक जानें [वॉटरमार्क खोज रहे हैं](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### उदाहरण

किसी भी समर्थित प्रकार के दस्तावेज़ से विशेष पाठ या छवि वाले सभी संभावित वॉटरमार्क खोजें और निकालें।

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### यह सभी देखें

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* नाम स्थान [GroupDocs.Watermark](../../watermarker)
* सभा [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->