---
title: "encrypt मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ को उसी पासवर्ड का उपयोग करके एन्क्रिप्ट करता है जो उपयोगकर्ता पासवर्ड और मालिक पासवर्ड दोनों के समान है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

दस्तावेज़ को उसी पासवर्ड का उपयोग करके एन्क्रिप्ट करता है जो उपयोगकर्ता पासवर्ड और मालिक पासवर्ड दोनों के समान है।

```python
def encrypt(self, password):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| password | `str` | उपयोगकर्ता और मालिक पासवर्ड। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

सामग्री को एन्क्रिप्ट करता है।

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| user_password | `str` | उपयोगकर्ता पासवर्ड। |
| owner_password | `str` | मालिक पासवर्ड। |
| permissions | `PdfPermissions` | सामग्री अनुमतियाँ। |
| crypto_algorithm | `PdfCryptoAlgorithm` | क्रिप्टोग्राफिक एल्गोरिदम। |

### संबंधित देखें
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
