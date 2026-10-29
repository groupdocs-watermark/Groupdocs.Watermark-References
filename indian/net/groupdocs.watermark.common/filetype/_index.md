---
title: "फ़ाइलप्रकार"
second_title: "GroupDocs.Watermark for .NET API संदर्भ"
description: "फ़ाइल प्रकार का प्रतिनिधित्व करता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.watermark.common/filetype/
---
## FileType class

फ़ाइल प्रकार का प्रतिनिधित्व करता है।

```csharp
public sealed class FileType : IEquatable<FileType>
```

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | फ़ाइल नाम प्रत्यय (बिंदु "." सहित) प्राप्त करता है, उदाहरण के लिए ".doc"। |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | फ़ाइल प्रकार का नाम प्राप्त करता है, उदाहरण के लिए "Microsoft Word Document"। |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | फ़ॉर्मेट परिवार प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मिलाता है। |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | निर्धारित करता है कि वर्तमान [`FileType`](../filetype) निर्दिष्ट [`FileType`](../filetype) वस्तु के समान है या नहीं। |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | निर्धारित करता है कि वर्तमान [`FileType`](../filetype) निर्दिष्ट वस्तु के समान है या नहीं। |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | वर्तमान [`FileType`](../filetype) वस्तु के लिए एक हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | वर्तमान वस्तु को दर्शाने वाली स्ट्रिंग लौटाता है। |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | समर्थित फ़ाइल प्रकारों को प्राप्त करता है। |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | निर्धारित करता है कि दो [`FileType`](../filetype) वस्तुएँ समान हैं या नहीं। |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | निर्धारित करता है कि दो [`FileType`](../filetype) वस्तुएँ समान नहीं हैं या नहीं। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | .BMP एक्सटेंशन वाली फ़ाइलें बिटमैप इमेज फ़ाइलें होती हैं जो बिटमैप डिजिटल इमेज को संग्रहीत करने के लिए उपयोग की जाती हैं। ये इमेज ग्राफ़िक्स एडाप्टर से स्वतंत्र होती हैं और इन्हें डिवाइस इंडिपेंडेंट बिटमैप (DIB) फ़ाइल फ़ॉर्मेट भी कहा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/image/bmp/) देखें। |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | .doc एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड या अन्य वर्ड प्रोसेसिंग एप्लिकेशन द्वारा बाइनरी फ़ाइल फ़ॉर्मेट में उत्पन्न दस्तावेज़ों को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing/doc/) देखें। |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM फ़ाइलें माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर के संस्करणों द्वारा उत्पन्न दस्तावेज़ हैं जिनमें मैक्रो चलाने की क्षमता होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing/docm/) देखें। |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। 2007 में माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज़ के साथ प्रस्तुत किया गया, इस नए दस्तावेज़ फ़ॉर्मेट की संरचना साधारण बाइनरी से बदलकर XML और बाइनरी फ़ाइलों के संयोजन में कर दी गई। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing/docx/) देखें। |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | .DOT एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dot/) देखें। |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | DOTM एक्सटेंशन वाली फ़ाइल माइक्रोसॉफ्ट वर्ड 2007 या उससे ऊपर के संस्करणों द्वारा बनाई गई टेम्प्लेट फ़ाइल को दर्शाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dotm/) देखें। |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | .DOTX एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जिनमें आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/word-processing/dotx/) देखें। |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML फ़ाइल फ़ॉर्मेट Outlook और अन्य संबंधित एप्लिकेशन द्वारा सहेजे गए ईमेल संदेशों को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/email/eml/) देखें। |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX फ़ाइल फ़ॉर्मेट Apple द्वारा लागू और विकसित किया गया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/email/emlx/) देखें। |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML को ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल (.xml) में संग्रहीत किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) देखें। |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML मैक्रो-सक्षम दस्तावेज़ को ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल (.xml) में संग्रहीत किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) देखें। |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML टेम्प्लेट (मैक्रो-रहित) को ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल (.xml) में संग्रहीत किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) देखें। |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML मैक्रो-सक्षम टेम्प्लेट को ज़िप पैकेज के बजाय एक फ्लैट XML फ़ाइल (.xml) में संग्रहीत किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) देखें। |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF या ग्राफ़िकल इंटरचेंज फ़ॉर्मेट एक अत्यधिक संकुचित इमेज प्रकार है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/image/gif/) देखें। |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG एक इमेज फ़ॉर्मेट प्रकार है जिसे लॉसी कॉम्प्रेशन विधि से सहेजा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/image/jpeg/) देखें। |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज कॉम्प्रेशन मानक है। वेवलेट तकनीक का उपयोग करके डिज़ाइन किया गया, JPEG 2000 किसी भी गुणवत्ता में एक साथ लॉसलेस कंटेंट को कोड कर सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/image/jp2/) देखें। |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG एक इमेज फ़ॉर्मेट प्रकार है जिसे लॉसी कॉम्प्रेशन विधि से सहेजा जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानकारी के लिए [यहाँ](https://wiki.fileformat.com/image/jpeg/) देखें। |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज संपीड़न मानक है। वेवलेट तकनीक का उपयोग करके डिज़ाइन किया गया, JPEG 2000 किसी भी गुणवत्ता में एक साथ लॉसलेस सामग्री को कोड कर सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/image/jp2/) देखें। |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज संपीड़न मानक है। वेवलेट तकनीक का उपयोग करके डिज़ाइन किया गया, JPEG 2000 किसी भी गुणवत्ता में एक साथ लॉसलेस सामग्री को कोड कर सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/image/jp2/) देखें। |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG एक फ़ाइल फ़ॉर्मेट है जिसका उपयोग Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, नियुक्ति या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/msg/) देखें। |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो OpenDocument टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित वर्ड प्रोसेसिंग एप्लिकेशन से बनाई जाती हैं। इन्हें मुफ्त OpenOffice Writer जैसे वर्ड प्रोसेसर एप्लिकेशन से बनाया जा सकता है और इनमें टेक्स्ट, इमेज, ऑब्जेक्ट और स्टाइल जैसी सामग्री रखी जा सकती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/word-processing/odt/) देखें। |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | .OFT एक्सटेंशन वाली फ़ाइलें Microsoft Outlook का उपयोग करके बनाई गई संदेश टेम्पलेट फ़ाइलें होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/email/oft/) देखें। |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office Open XML फ़ाइल (.ooxml)। |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) एक प्रकार का दस्तावेज़ है जिसे Adobe ने 1990 के दशक में बनाया था। इस फ़ाइल फ़ॉर्मेट का उद्देश्य दस्तावेज़ों और अन्य संदर्भ सामग्री का प्रतिनिधित्व करने के लिए एक मानक प्रस्तुत करना था, जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/view/pdf/) देखें। |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, एक प्रकार का रास्टर इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस संपीड़न का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/image/png/) देखें। |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | POTM एक्सटेंशन वाली फ़ाइलें Microsoft PowerPoint टेम्पलेट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। POTM फ़ाइलें PowerPoint 2007 या उसके बाद के संस्करणों से बनाई जाती हैं और डिफ़ॉल्ट सेटिंग्स रखती हैं जिन्हें आगे की प्रस्तुति फ़ाइलें बनाने के लिए उपयोग किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/potm/) देखें। |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | .POTX एक्सटेंशन वाली फ़ाइलें Microsoft PowerPoint टेम्पलेट प्रस्तुतियाँ हैं जो Microsoft PowerPoint 2007 और उसके बाद के संस्करणों से बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/potx/) देखें। |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slide Show, फ़ाइलें Microsoft PowerPoint का उपयोग करके स्लाइड शो उद्देश्य के लिए बनाई जाती हैं। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/pps/) देखें। |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | PPSM एक्सटेंशन वाली फ़ाइलें मैक्रो-सक्षम स्लाइड शो फ़ाइल फ़ॉर्मेट हैं जो Microsoft PowerPoint 2007 या उससे उच्च संस्करणों से बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/ppsm/) देखें। |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, फ़ाइलें Microsoft PowerPoint 2007 और उसके बाद के संस्करणों का उपयोग करके स्लाइड शो उद्देश्य के लिए बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/ppsx/) देखें। |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | PPT एक्सटेंशन वाली फ़ाइल PowerPoint फ़ाइल को दर्शाती है जिसमें स्लाइडों का संग्रह होता है जिसे स्लाइडशो के रूप में प्रदर्शित किया जाता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/ppt/) देखें। |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM एक्सटेंशन वाली फ़ाइलें मैक्रो-सक्षम प्रस्तुति फ़ाइलें हैं जो Microsoft PowerPoint 2007 या उच्च संस्करणों से बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/pptm/) देखें। |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | PPTX एक्सटेंशन वाली फ़ाइलें प्रस्तुति फ़ाइलें हैं जो लोकप्रिय Microsoft PowerPoint एप्लिकेशन से बनाई गई हैं। पहले के प्रस्तुति फ़ाइल फ़ॉर्मेट PPT जो बाइनरी था, के विपरीत, PPTX फ़ॉर्मेट Microsoft PowerPoint Open XML प्रस्तुति फ़ाइल फ़ॉर्मेट पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://wiki.fileformat.com/presentation/pptx/) देखें। |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft द्वारा प्रस्तुत और प्रलेखित, Rich Text Format (RTF) एक विधि का प्रतिनिधित्व करता है जो फ़ॉर्मेटेड टेक्स्ट और ग्राफ़िक्स को एन्कोड करने के लिए उपयोगी है। यह फ़ॉर्मेट अन्य Microsoft उत्पादों के साथ क्रॉस‑प्लेटफ़ॉर्म दस्तावेज़ विनिमय को सुविधाजनक बनाता है, जिससे इंटरऑपरेबिलिटी का उद्देश्य पूरा होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF या TIF, Tagged Image File Format, रास्टर इमेजेज़ का प्रतिनिधित्व करता है जो विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF या TIF, Tagged Image File Format, रास्टर इमेजेज़ का प्रतिनिधित्व करता है जो विभिन्न उपकरणों पर उपयोग के लिए बनाए गए हैं जो इस फ़ाइल फ़ॉर्मेट मानक का पालन करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW Visio Graphics Service फ़ाइल फ़ॉर्मेट है जो वेब ड्राइंग को रेंडर करने के लिए आवश्यक स्ट्रीम्स और स्टोरेज को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio में बनाई गई कोई भी ड्राइंग या चार्ट, लेकिन XML फ़ॉर्मेट में सहेजी गई, .VDX एक्सटेंशन रखती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD फ़ाइलें Microsoft Visio एप्लिकेशन से बनाई गई ड्राइंग्स हैं जो विभिन्न ग्राफ़िकल ऑब्जेक्ट्स और उनके बीच के कनेक्शन को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | VSDM एक्सटेंशन वाली फ़ाइलें Microsoft Visio एप्लिकेशन से बनाई गई ड्राइंग फ़ाइलें हैं जो मैक्रो को सपोर्ट करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | .VSDX एक्सटेंशन वाली फ़ाइलें Microsoft Visio फ़ाइल फ़ॉर्मेट हैं जो Microsoft Office 2013 से प्रस्तुत किए गए हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS स्टेंसिल फ़ाइलें Microsoft Visio 2007 और उससे पहले के संस्करणों से बनाई गई हैं। स्टेंसिल फ़ाइलें ड्राइंग ऑब्जेक्ट्स प्रदान करती हैं जिन्हें .VSD Visio ड्राइंग में शामिल किया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | .VSSM एक्सटेंशन वाली फ़ाइलें Microsoft Visio स्टेंसिल फ़ाइलें हैं जो मैक्रो को सपोर्ट करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | .VSSX एक्सटेंशन वाली फ़ाइलें ड्राइंग स्टेंसिल हैं जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST एक्सटेंशन वाली फ़ाइलें वेक्टर इमेज फ़ाइलें हैं जो Microsoft Visio से बनाई गई हैं और आगे की फ़ाइलें बनाने के लिए टेम्पलेट के रूप में कार्य करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM एक्सटेंशन वाली फ़ाइलें टेम्पलेट फ़ाइलें हैं जो Microsoft Visio से बनाई गई हैं और मैक्रो को सपोर्ट करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | VSTX एक्सटेंशन वाली फ़ाइलें ड्राइंग टेम्पलेट फ़ाइलें हैं जो Microsoft Visio 2013 और उसके बाद के संस्करणों से बनाई गई हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | .VSX एक्सटेंशन वाली फ़ाइलें स्टेंसिल को संदर्भित करती हैं जिनमें ड्राइंग और शैप्स होते हैं जो Microsoft Visio में डायग्राम बनाने के लिए उपयोग किए जाते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX एक्सटेंशन वाली फ़ाइल Microsoft Visio ड्राइंग टेम्पलेट है जो XML फ़ाइल फ़ॉर्मेट में डिस्क पर सहेजी जाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, Google द्वारा प्रस्तुत, एक आधुनिक रास्टर वेब इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस और लॉसी संपीड़न पर आधारित है। यह समान इमेज गुणवत्ता प्रदान करता है जबकि इमेज आकार को काफी कम करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | XLS एक्सटेंशन वाली फ़ाइलें Excel बाइनरी फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करती हैं। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा भी बनाई जा सकती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB फ़ाइल फ़ॉर्मेट Excel बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड्स और संरचनाओं का संग्रह है जो Excel वर्कबुक सामग्री को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | XLSM एक्सटेंशन वाली फ़ाइलें स्प्रेडशीट फ़ाइलों का एक प्रकार हैं जो मैक्रो का समर्थन करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है जिसे माइक्रोसॉफ्ट ने माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज़ के साथ पेश किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | फ़ाइलें जिनका एक्सटेंशन .XLT है, माइक्रोसॉफ्ट एक्सेल द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जो एक स्प्रेडशीट एप्लिकेशन है और माइक्रोसॉफ्ट ऑफिस सूट का हिस्सा है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों को दर्शाता है जो माइक्रोसॉफ्ट एक्सेल द्वारा मैक्रो-सक्षम टेम्प्लेट फ़ाइलों के रूप में उत्पन्न की जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | XLTX एक्सटेंशन वाली फ़ाइलें माइक्रोसॉफ्ट एक्सेल टेम्प्लेट फ़ाइलें हैं जो Office OpenXML फ़ाइल फ़ॉर्मेट विशिष्टियों पर आधारित हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### टिप्पणियाँ

यह क्लास सभी फ़ाइल प्रकारों की सूची प्राप्त करने के लिए मेथड्स प्रदान करती है जो **GroupDocs.Watermark** द्वारा समर्थित हैं।**और अधिक जानें**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### संबंधित देखें

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
