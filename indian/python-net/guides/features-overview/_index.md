---
title: "विशेषताओं का अवलोकन"
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python via .NET एकल, फ़ॉर्मेट-स्वतंत्र API के माध्यम से टेक्स्ट और इमेज वॉटरमार्क को जोड़ता, खोजता और हटाता है — फ़ॉर्मेट-विशिष्ट प्लेसमेंट, कंटेंट-ट्री संपादन, लॉकिंग, और रास्टराइज़ेशन के साथ।"
type: docs
url: /hi/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark for Python via .NET व्यापक रेंज के [समर्थित दस्तावेज़ फ़ॉर्मेट्स](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) में वॉटरमार्क जोड़ता, खोजता और हटाता है। प्रत्येक ऑपरेशन समान वर्कफ़्लो का पालन करता है: एक दस्तावेज़ को [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) के साथ खोलें, `add()`, `search()` या `remove()` कॉल करें, फिर `save()` करके परिणाम को उसके मूल फ़ॉर्मेट में वापस सहेजें। नीचे दी गई क्षमताओं को एक ही पास में स्वतंत्र रूप से संयोजित किया जा सकता है।

## Text and image watermarks

फ़ॉन्ट, रंग, अपारदर्शिता, घूर्णन, संरेखण और आकार पर पूर्ण नियंत्रण के साथ स्टाइल किए गए टेक्स्ट या इमेज वॉटरमार्क जोड़ें। इमेज वॉटरमार्क को फ़ाइल या स्ट्रीम से लोड किया जा सकता है। देखें [Add text watermarks](/watermark/python-net/guides/add-text/) और [Add image watermarks](/watermark/python-net/guides/add-image/).

## Customization and tiling

वॉटरमार्क को निरपेक्ष निर्देशांक या पैरेंट-रिलेटिव संरेखण और मार्जिन के साथ स्थित करें, पृष्ठ के सापेक्ष स्केल करें, घुमाएँ, और पूरे पृष्ठ पर दोहराव पैटर्न में टाइल करें। देखें [Customize watermarks](/watermark/python-net/guides/customize/), [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/), और [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

प्रत्येक फ़ॉर्मेट के अनुरूप विकल्पों का उपयोग करके वॉटरमार्क रखें — PDF आर्टिफैक्ट्स, एनोटेशन, और प्रिंट-ओनली एनोटेशन; प्रेज़ेंटेशन स्लाइड्स, मास्टर, लेआउट और नोट्स; स्प्रेडशीट वर्कशीट्स, बैकग्राउंड और हेडर/फ़ूटर; Visio पेज; और लॉक्ड Word सेक्शन और पेज। देखें [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) और [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/) में अन्य फ़ॉर्मेट विषय।

## Searching, modifying, and removing

दस्तावेज़ में पहले से मौजूद वॉटरमार्क खोजें — जिसमें थर्ड-पार्टी टूल्स द्वारा जोड़े गए भी शामिल हैं — सटीक टेक्स्ट, रेगुलर एक्सप्रेशन, इमेज समानता, या टेक्स्ट फ़ॉर्मेटिंग द्वारा, और मानदंडों को `and_`/`or_`/`not_` के साथ संयोजित करें। एक बार मिलने पर, उनका टेक्स्ट या इमेज बदलें, या उन्हें हटाएँ। देखें [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), और [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` एक फ़ॉर्मेट-विशिष्ट कंटेंट ट्री प्रदान करता है ताकि आप मौजूदा शैप्स, PDF XObjects/आर्टिफैक्ट्स/एनोटेशन्स, अटैचमेंट्स, बैकग्राउंड्स, और हेडर/फ़ूटर की जांच और संपादन कर सकें — और आप `get_images()` के साथ दस्तावेज़ में एम्बेडेड इमेजेज़ पर वॉटरमार्क लगा सकते हैं। देखें [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

वॉटरमार्क को हटाना कठिन बनाने के लिए उन्हें लॉक करें, Word दस्तावेज़ों की सुरक्षा करें, प्रिंट-ओनली PDF एनोटेशन्स जोड़ें, या PDF पेज़ को रास्टराइज़ करें ताकि वॉटरमार्क को संपादित नहीं किया जा सके। देखें [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) और [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

दस्तावेज़ के फ़ाइल प्रकार, पेज़ काउंट, और आकार को बिना संशोधित किए पढ़ें, और लाइब्रेरी द्वारा समर्थित सभी फ़ाइल फ़ॉर्मेट की सूची देखें। देखें [Get document info](/watermark/python-net/guides/get-document-info/) और [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark for Python via .NET पूरी तरह से आपके अपने इन्फ्रास्ट्रक्चर पर चलता है — आपके दस्तावेज़ कभी भी आपके वातावरण से बाहर नहीं जाते। पैकेज एक स्व-निहित व्हील है जो सभी आवश्यक चीज़ें बंडल करता है, इसलिए कोई Microsoft Office, OpenOffice, या अलग रनटाइम स्थापित करने की आवश्यकता नहीं है। देखें [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) समर्थित प्लेटफ़ॉर्म और नेटिव डिपेंडेंसीज़ के लिए।
