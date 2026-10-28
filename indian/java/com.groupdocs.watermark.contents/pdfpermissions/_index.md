---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक PDF दस्तावेज़ के लिए उपयोगकर्ताओं की अनुमतियों का प्रतिनिधित्व करता है।"
type: docs
weight: 68
url: /hi/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

PDF दस्तावेज़ के लिए उपयोगकर्ता की अनुमतियों का प्रतिनिधित्व करता है।

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | सामग्री प्रिंट करें। |
|
|  | [ModifyContent](#ModifyContent) | सामग्री संशोधित करें। |
|
|  | [ExtractContent](#ExtractContent) | दस्तावेज़ से पाठ और ग्राफ़िक्स को कॉपी करें या अन्यथा निकालें। |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | पाठ एनोटेशन जोड़ें या संशोधित करें। |
|
|  | [FillForm](#FillForm) | मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड भरें। |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | पाठ और ग्राफ़िक्स निकालें। |
|
|  | [AssembleDocument](#AssembleDocument) | सामग्री को संयोजित करें। |
|
|  | [PrintingQuality](#PrintingQuality) | सामग्री को ऐसी प्रस्तुति में प्रिंट करें जिससे PDF दस्तावेज़ की एक सटीक डिजिटल कॉपी बनाई जा सके। |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


सामग्री प्रिंट करें।

संस्करण 2 के सुरक्षा हैंडलर: सामग्री प्रिंट करें।

संस्करण 3 या उससे अधिक के सुरक्षा हैंडलर: सामग्री प्रिंट करें
(संभवतः उच्चतम गुणवत्ता स्तर पर नहीं, इस पर निर्भर करता है कि
`#PrintingQuality.PrintingQuality` भी सेट है)।


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


सामग्री संशोधित करें।

दस्तावेज़ की सामग्री को अन्य ऑपरेशनों द्वारा संशोधित करें
उनके द्वारा नियंत्रित ऑपरेशनों से, `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`।


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


दस्तावेज़ से पाठ और ग्राफ़िक्स को कॉपी करें या अन्यथा निकालें।

संस्करण 2 के सुरक्षा हैंडलर: सामग्री से पाठ और ग्राफ़िक्स को कॉपी करें या अन्यथा निकालें,
पाठ और ग्राफ़िक्स निकालने सहित (उपयोगकर्ताओं की पहुँच समर्थन के लिए
विकलांगता या अन्य उद्देश्यों के लिए)।

संस्करण 3 या उससे अधिक के सुरक्षा हैंडलर: सामग्री से पाठ और ग्राफ़िक्स को कॉपी करें या अन्यथा निकालें
सामग्री को उन ऑपरेशनों द्वारा जो इसके द्वारा नियंत्रित नहीं हैं
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`।


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


पाठ एनोटेशन जोड़ें या संशोधित करें।

पाठ एनोटेशन जोड़ें या संशोधित करें, इंटरैक्टिव फ़ॉर्म फ़ील्ड भरें,
और, यदि `#ModifyContent.ModifyContent` भी सेट है,
इंटरैक्टिव फ़ॉर्म फ़ील्ड बनाएं या संशोधित करें (सिग्नेचर फ़ील्ड सहित)।


### FillForm {#FillForm}
```
public static final int FillForm
```


मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड भरें।

संस्करण 3 या उससे अधिक के सुरक्षा हैंडलर: मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड भरें
(सिग्नेचर फ़ील्ड सहित), यहाँ तक कि यदि `#ModifyTextAnnotations.ModifyTextAnnotations` स्पष्ट है।


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


पाठ और ग्राफ़िक्स निकालें।

संस्करण 3 या उससे अधिक के सुरक्षा हैंडलर: पाठ और ग्राफ़िक्स निकालें
(विकलांग उपयोगकर्ताओं की पहुँच या अन्य उद्देश्यों के समर्थन में)।


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


सामग्री को संयोजित करें।

संस्करण 3 या उससे अधिक के सुरक्षा हैंडलर: सामग्री को व्यवस्थित करें (पृष्ठ सम्मिलित करें, घुमाएँ, या हटाएँ
और बुकमार्क या थंबनेल इमेज बनाएं), यहाँ तक कि यदि `#ModifyContent.ModifyContent` स्पष्ट है।


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


सामग्री को ऐसी प्रस्तुति में प्रिंट करें जिससे PDF दस्तावेज़ की एक सटीक डिजिटल कॉपी बनाई जा सके।

संस्करण 3 या उससे अधिक के सुरक्षा हैंडलर: सामग्री को ऐसी प्रस्तुति में प्रिंट करें जिससे एक विश्वसनीय
PDF दस्तावेज़ की डिजिटल कॉपी उत्पन्न की जा सके। जब यह बिट स्पष्ट हो (और `#PrintDocument.PrintDocument`
सेट हो), प्रिंटिंग को उपस्थिति की निम्न-स्तरीय प्रस्तुति तक सीमित किया जाता है, संभवतः घटी हुई गुणवत्ता के साथ।


