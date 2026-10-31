---
title: "from_argb विधि"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक 32-बिट ARGB मान से Color संरचना बनाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

एक 32-बिट ARGB मान से Color संरचना बनाता है।

```python
def from_argb(cls, argb):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| argb | `int` | 32‑बिट ARGB मान को निर्दिष्ट करने वाला मान। |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

निर्दिष्ट बेस Color से, लेकिन नई अल्फा मान के साथ, Color संरचना बनाता है।

हालांकि यह विधि अल्फा मान के लिए 32‑बिट मान पास करने की अनुमति देती है, यह मान 8 बिट तक सीमित है।

```python
def from_argb(cls, alpha, base_color):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| alpha | `int` | नए Color के लिए अल्फा मान। मान्य मान 0 से 255 तक हैं। |
| base_color | `Color` | वह Color जिससे नया Color बनाया जाएगा। |

**Returns:** Color: The Color that this method creates.

| उठाता है | विवरण |
| :- | :- |
| `ValueError` | अल्फा 0 से कम या 255 से अधिक है। |

### उदाहरण

```python
from groupdocs.watermark.watermarks import Color

# अर्ध‑पारदर्शी लाल रंग बनाएं (अल्फा 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

निर्दिष्ट 8‑बिट लाल, हरा, और नीले मानों से [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) बनाता है, जिसमें अल्फा चैनल को स्वचालित रूप से 255 (पूर्णतः अपारदर्शी) पर सेट किया जाता है।

हालांकि यह विधि प्रत्येक रंग घटक के लिए 32‑बिट मान पास करने की अनुमति देती है, प्रत्येक घटक 8 बिट तक सीमित है।

```python
def from_argb(cls, red, green, blue):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| red | `int` | नए `Color` के लिए लाल घटक मान। मान्य मान 0 से 255 तक हैं। |
| green | `int` | नए `Color` के लिए हरा घटक मान। मान्य मान 0 से 255 तक हैं। |
| blue | `int` | नए `Color` के लिए नीला घटक मान। मान्य मान 0 से 255 तक हैं। |

**Returns:** Color: The color that this method creates.

| उठाता है | विवरण |
| :- | :- |
| `ValueError` | लाल, हरा या नीला 0 से कम या 255 से अधिक है। |

## from_argb {#alpha-red-green-blue}

चार ARGB घटक मानों (अल्फा, लाल, हरा, और नीला) से [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) बनाता है।

हालांकि यह विधि प्रत्येक घटक के लिए 32‑बिट मान पास करने की अनुमति देती है, प्रत्येक घटक का मान 8 बिट तक सीमित है।

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| alpha | `int` | नए `Color` के लिए अल्फा घटक मान। मान्य मान 0 से 255 तक हैं। |
| red | `int` | नए `Color` के लिए लाल घटक मान। मान्य मान 0 से 255 तक हैं। |
| green | `int` | नए `Color` के लिए हरा घटक मान। मान्य मान 0 से 255 तक हैं। |
| blue | `int` | नए `Color` के लिए नीला घटक मान। मान्य मान 0 से 255 तक हैं। |

**Returns:** Color: The `Color` that this method creates.

| उठाता है | विवरण |
| :- | :- |
| `ValueError` | लाल, हरा या नीला 0 से कम या 255 से अधिक है। |

### उदाहरण

```python
from groupdocs.watermark.watermarks import Color

# पूरी तरह अपारदर्शी लाल रंग बनाएं
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### संबंधित देखें
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
