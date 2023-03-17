---
title: FileType
second_title: .NET API संदर्भ के लिए GroupDocs.Watermark
description: फ़इल प्रकर क प्रतनधत्व करत है
type: docs
weight: 40
url: /hi/net/groupdocs.watermark.common/filetype/
---
## FileType class

फ़ाइल प्रकार का प्रतिनिधित्व करता है।

```csharp
public sealed class FileType : IEquatable<FileType>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | फ़ाइल नाम प्रत्यय प्राप्त करता है (अवधि "।" सहित) उदाहरण के लिए, ".doc"। |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | फ़ाइल प्रकार का नाम प्राप्त करता है जैसे, "माइक्रोसॉफ्ट वर्ड दस्तावेज़"। |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | प्रारूप परिवार प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | निर्धारित करता है कि क्या वर्तमान[`FileType`](../filetype) निर्दिष्ट के समान है[`FileType`](../filetype) वस्तु. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | निर्धारित करता है कि क्या वर्तमान[`FileType`](../filetype) निर्दिष्ट वस्तु के समान है। |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | वर्तमान के लिए एक हैश कोड लौटाता है[`FileType`](../filetype) वस्तु. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | एक स्ट्रिंग लौटाता है जो वर्तमान वस्तु का प्रतिनिधित्व करता है। |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है। |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | निर्धारित करता है कि क्या दो[`FileType`](../filetype) वस्तुएं समान हैं। |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | निर्धारित करता है कि क्या दो[`FileType`](../filetype) वस्तुएं समान नहीं हैं। |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | एक्सटेंशन वाली फ़ाइलें। BMP बिटमैप छवि फ़ाइलों का प्रतिनिधित्व करती हैं जिनका उपयोग बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। ये छवियां ग्राफ़िक्स एडेप्टर से स्वतंत्र हैं और इन्हें डिवाइस स्वतंत्र बिटमैप (DIB) फ़ाइल प्रारूप भी कहा जाता है। इस फ़ाइल स्वरूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | .doc एक्सटेंशन वाली फ़ाइलें Microsoft Word या अन्य वर्ड प्रोसेसिंग दस्तावेज़ों को बाइनरी फ़ाइल स्वरूप में उत्पन्न करती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM फ़ाइलें Microsoft Word 2007 या उच्चतर जेनरेट किए गए दस्तावेज़ हैं जिनमें मैक्रोज़ चलाने की क्षमता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध प्रारूप है। Microsoft Office 2007 के रिलीज़ के साथ 2007 से पेश किया गया, इस नए दस्तावेज़ प्रारूप की संरचना को सादे बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दिया गया था। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | .DOT एक्सटेंशन वाली फ़ाइलें Microsoft Word द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं, जिनमें आगे DOC या DOCX फ़ाइलों को बनाने के लिए पूर्व-स्वरूपित सेटिंग होती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | DOTM एक्सटेंशन वाली फ़ाइल Microsoft Word 2007 या उच्चतर के साथ बनाई गई टेम्पलेट फ़ाइल का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | DOTX एक्सटेंशन वाली फाइलें Microsoft Word द्वारा बनाई गई टेम्प्लेट फाइलें हैं, जिनमें आगे DOCX फाइलों के निर्माण के लिए पूर्व-स्वरूपित सेटिंग्स हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | ईएमएल फ़ाइल प्रारूप आउटलुक और अन्य प्रासंगिक अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX फ़ाइल स्वरूप Apple द्वारा कार्यान्वित और विकसित किया गया है। ईमेल निर्यात करने के लिए Apple मेल एप्लिकेशन EMLX फ़ाइल स्वरूप का उपयोग करता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | ऑफिस ओपन एक्सएमएल वर्डप्रोसेसिंगएमएल जिप पैकेज (.एक्सएमएल) के बजाय एक फ्लैट एक्सएमएल फाइल में संग्रहीत है। इस फाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | ऑफिस ओपन एक्सएमएल वर्डप्रोसेसिंगएमएल मैक्रो-सक्षम दस्तावेज़ एक ज़िप पैकेज (.एक्सएमएल) के बजाय एक फ्लैट एक्सएमएल फ़ाइल में संग्रहीत है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | ऑफिस ओपन एक्सएमएल वर्डप्रोसेसिंगएमएल टेम्पलेट (मैक्रो-फ्री) जिप पैकेज (.एक्सएमएल) के बजाय एक फ्लैट एक्सएमएल फाइल में संग्रहित है। इस फाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | ऑफिस ओपन एक्सएमएल वर्डप्रोसेसिंगएमएल मैक्रो-इनेबल्ड टेम्प्लेट जिप पैकेज (.एक्सएमएल) के बजाय एक फ्लैट एक्सएमएल फाइल में स्टोर किया जाता है। इस फाइल फॉर्मेट के बारे में और जानें[यहाँ](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF या ग्राफ़िकल इंटरचेंज फ़ॉर्मेट अत्यधिक कंप्रेस की गई इमेज का एक प्रकार है. इस फ़ाइल फ़ॉर्मेट के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | एक जेपीईजी एक प्रकार का छवि प्रारूप है जिसे हानिकारक संपीड़न की विधि का उपयोग करके सहेजा जाता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज कंप्रेशन मानक है। डिज़ाइन किया गया, वेवलेट तकनीक का उपयोग कर जेपीईजी 2000 दोषरहित सामग्री को एक बार में किसी भी गुणवत्ता में कोड कर सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | एक जेपीईजी एक प्रकार का छवि प्रारूप है जिसे हानिकारक संपीड़न की विधि का उपयोग करके सहेजा जाता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज कंप्रेशन मानक है। डिज़ाइन किया गया, वेवलेट तकनीक का उपयोग कर जेपीईजी 2000 दोषरहित सामग्री को एक बार में किसी भी गुणवत्ता में कोड कर सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) एक इमेज कोडिंग सिस्टम और अत्याधुनिक इमेज कंप्रेशन मानक है। डिज़ाइन किया गया, वेवलेट तकनीक का उपयोग कर जेपीईजी 2000 दोषरहित सामग्री को एक बार में किसी भी गुणवत्ता में कोड कर सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG एक फ़ाइल स्वरूप है जिसका उपयोग माइक्रोसॉफ्ट आउटलुक और एक्सचेंज द्वारा ईमेल संदेशों, संपर्क, अपॉइंटमेंट, या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT फाइलें वर्ड प्रोसेसिंग एप्लिकेशन के साथ बनाए गए दस्तावेज़ हैं जो OpenDocument टेक्स्ट फ़ाइल प्रारूप पर आधारित हैं। ये वर्ड प्रोसेसर एप्लिकेशन के साथ बनाए गए हैं जैसे फ्री ओपनऑफिस राइटर और टेक्स्ट, इमेज, ऑब्जेक्ट्स और स्टाइल जैसी सामग्री रख सकते हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | .OFT एक्सटेंशन वाली फ़ाइलें संदेश टेम्पलेट फ़ाइलों का प्रतिनिधित्व करती हैं जो Microsoft Outlook का उपयोग करके बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | कार्यालय खुली एक्सएमएल फ़ाइल (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | पोर्टेबल डॉक्यूमेंट फॉर्मेट (पीडीएफ) 1990 के दशक में एडोब द्वारा बनाया गया एक प्रकार का दस्तावेज है। इस फ़ाइल प्रारूप का उद्देश्य में दस्तावेज़ों और अन्य संदर्भ सामग्री के प्रतिनिधित्व के लिए एक मानक पेश करना था, जो कि एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और साथ ही ऑपरेटिंग सिस्टम से स्वतंत्र है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, पोर्टेबल नेटवर्क ग्राफ़िक्स, एक प्रकार के रेखापुंज छवि फ़ाइल प्रारूप को संदर्भित करता है जो लूज़लेस संपीड़न का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | पीओटीएम एक्सटेंशन वाली फाइलें मैक्रोज़ के समर्थन के साथ माइक्रोसॉफ्ट पावरप्वाइंट टेम्पलेट फाइलें हैं। POTM files PowerPoint 2007 या इसके बाद के संस्करण के साथ बनाई गई हैं और इसमें डिफ़ॉल्ट सेटिंग्स हैं जिनका उपयोग आगे की प्रस्तुति फ़ाइलों को बनाने के लिए किया जा सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | .POTX एक्सटेंशन वाली फ़ाइलें Microsoft PowerPoint टेम्पलेट प्रस्तुतियों का प्रतिनिधित्व करती हैं जो Microsoft PowerPoint 2007 और इसके बाद के संस्करण के साथ बनाई गई हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint स्लाइड शो, फ़ाइलें स्लाइड शो के उद्देश्य के लिए Microsoft PowerPoint का उपयोग करके बनाई गई हैं। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | PPSM एक्सटेंशन वाली फ़ाइलें Microsoft PowerPoint 2007 या उच्चतर के साथ बनाए गए मैक्रो-सक्षम स्लाइड शो फ़ाइल स्वरूप का प्रतिनिधित्व करती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, पावर प्वाइंट स्लाइड शो, फ़ाइल स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint 2007 और इसके बाद के संस्करण का उपयोग करके बनाई गई है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | PPT एक्सटेंशन वाली एक फ़ाइल PowerPoint फ़ाइल का प्रतिनिधित्व करती है जिसमें स्लाइड शो के रूप में प्रदर्शित के लिए स्लाइड का संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | PPTM एक्सटेंशन वाली फ़ाइलें मैक्रो-सक्षम प्रस्तुति फ़ाइलें हैं जो Microsoft PowerPoint 2007 या उच्चतर संस्करणों के साथ बनाई गई हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | PPTX एक्सटेंशन वाली फ़ाइलें लोकप्रिय Microsoft PowerPoint एप्लिकेशन के साथ बनाई गई प्रस्तुति फ़ाइलें हैं। प्रस्तुति फ़ाइल स्वरूप PPT के पिछले संस्करण के विपरीत जो बाइनरी था, PPTX प्रारूप Microsoft PowerPoint ओपन XML प्रस्तुति फ़ाइल स्वरूप पर आधारित है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Microsoft द्वारा प्रस्तुत और प्रलेखित, रिच टेक्स्ट फॉर्मेट (RTF) अनुप्रयोगों के भीतर उपयोग के लिए एन्कोडिंग स्वरूपित पाठ और ग्राफिक्स की एक विधि का प्रतिनिधित्व करता है। प्रारूप अन्य Microsoft उत्पादों के साथ क्रॉस-प्लेटफ़ॉर्म दस्तावेज़ विनिमय की सुविधा देता है, इस प्रकार इंटरऑपरेबिलिटी के उद्देश्य को पूरा करता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF या TIF, टैग की गई छवि फ़ाइल प्रारूप, रेखापुंज छवियों का प्रतिनिधित्व करता है जो इस फ़ाइल प्रारूप मानक का अनुपालन करने वाले विभिन्न प्रकार के उपकरणों पर उपयोग के लिए हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF या TIF, टैग की गई छवि फ़ाइल प्रारूप, रेखापुंज छवियों का प्रतिनिधित्व करता है जो इस फ़ाइल प्रारूप मानक का अनुपालन करने वाले विभिन्न प्रकार के उपकरणों पर उपयोग के लिए हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW Visio ग्राफ़िक्स सेवा फ़ाइल स्वरूप है जो किसी वेब आरेखण को रेंडर करने के लिए के लिए आवश्यक स्ट्रीम और संग्रहण निर्दिष्ट करता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Microsoft Visio में बनाए गए, लेकिन XML स्वरूप में सहेजे गए किसी भी आरेखण या चार्ट में .VDX एक्सटेंशन होता है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | वीएसडी फाइलें विभिन्न प्रकार के ग्राफिकल ऑब्जेक्ट्स और इनके बीच इंटरकनेक्शन का प्रतिनिधित्व करने के लिए माइक्रोसॉफ्ट विसियो एप्लिकेशन के साथ बनाए गए चित्र हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | VSDM एक्सटेंशन वाली फ़ाइलें मैक्रोज़ का समर्थन करने वाले Microsoft Visio एप्लिकेशन के साथ बनाई गई फ़ाइलें खींच रही हैं. इस फ़ाइल स्वरूप के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | .VSDX एक्सटेंशन वाली फ़ाइलें Microsoft Office 2013 के बाद से पेश किए गए Microsoft Visio फ़ाइल स्वरूप का प्रतिनिधित्व करती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS Microsoft Visio 2007 और पहले के साथ बनाई गई स्टैंसिल फ़ाइलें हैं। स्टैंसिल फ़ाइलें Drawing ऑब्जेक्ट प्रदान करती हैं जिन्हें .VSD Visio आरेखण में शामिल किया जा सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | .VSSM एक्सटेंशन वाली फ़ाइलें Microsoft Visio स्टैंसिल फ़ाइलें हैं जो मैक्रोज़ के लिए समर्थन प्रदान करती हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | .VSSX एक्सटेंशन वाली फाइलें Microsoft Visio 2013 और इसके बाद के संस्करण के साथ बनाई गई स्टेंसिल खींच रही हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | VST एक्सटेंशन वाली फ़ाइलें Microsoft Visio के साथ बनाई गई वेक्टर इमेज फ़ाइलें हैं और आगे की फ़ाइलें बनाने के लिए टेम्पलेट के रूप में कार्य करती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | VSTM एक्सटेंशन वाली फ़ाइलें Microsoft Visio के साथ बनाई गई टेम्प्लेट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | VSTX एक्सटेंशन वाली फाइलें Microsoft Visio 2013 और इसके बाद के संस्करण के साथ बनाई गई टेम्प्लेट फाइलें खींच रही हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें [यहाँ](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | .VSX एक्सटेंशन वाली फ़ाइलें स्टेंसिल को संदर्भित करती हैं जिनमें ड्रॉइंग और आकार होते हैं जिनका उपयोग Microsoft Visio में आरेख बनाने के लिए किया जाता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | VTX एक्सटेंशन वाली फ़ाइल एक Microsoft Visio ड्रॉइंग टेम्प्लेट है जिसे XML फ़ाइल स्वरूप में डिस्क में सहेजा जाता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, Google द्वारा पेश किया गया, एक आधुनिक रेखापुंज वेब छवि फ़ाइल प्रारूप है जो दोषरहित और हानिपूर्ण संपीड़न पर आधारित है। यह छवि के आकार को काफी कम करते हुए समान छवि गुणवत्ता प्रदान करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | एक्सएलएस एक्सटेंशन वाली फाइलें एक्सेल बाइनरी फाइल फॉर्मेट का प्रतिनिधित्व करती हैं। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा बनाई जा सकती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB फ़ाइल स्वरूप एक्सेल बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है, जो रिकॉर्ड्स और संरचनाओं का एक संग्रह है जो एक्सेल कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | XLSM एक्सटेंशन वाली फ़ाइलें एक प्रकार की स्प्रैडशीट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX Microsoft Excel दस्तावेज़ों के लिए जाना-पहचाना फ़ॉर्मैट है जिसे Microsoft ने Microsoft Office 2007 के रिलीज़ के साथ पेश किया था। इस फ़ाइल फ़ॉर्मैट के बारे में और जानें[यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | .XLT एक्सटेंशन वाली फ़ाइलें Microsoft Excel के साथ बनाई गई टेम्प्लेट फ़ाइलें हैं जो एक स्प्रेडशीट एप्लिकेशन है जो Microsoft Office सुइट के हिस्से के रूप में आती है। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों का प्रतिनिधित्व करता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न होती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | XLTX एक्सटेंशन वाली फ़ाइलें Microsoft Excel टेम्पलेट फ़ाइलों का प्रतिनिधित्व करती हैं जो कि Office OpenXML फ़ाइल प्रारूप विनिर्देशों पर आधारित हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### टिप्पणियों

यह वर्ग द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने के तरीके प्रदान करता है**ग्रुप डॉक्स। वॉटरमार्क**.**और अधिक जानें**

* [समर्थित दस्तावेज़ प्रारूप](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [समर्थित फ़ाइल स्वरूप प्राप्त करें](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [दस्तावेज़ जानकारी प्राप्त करें](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### यह सभी देखें

* नाम स्थान [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* सभा [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
