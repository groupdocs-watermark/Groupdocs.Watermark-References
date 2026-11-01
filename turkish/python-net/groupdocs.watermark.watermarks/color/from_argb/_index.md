---
title: "from_argb metod"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "32 bitlik ARGB değerinden bir Color yapısı oluşturur."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

32 bitlik ARGB değerinden bir Color yapısı oluşturur.

```python
def from_argb(cls, argb):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb | `int` | 32-bit ARGB değerini belirten bir değer. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Belirtilen temel Color'dan, ancak yeni bir alfa değeriyle bir Color yapısı oluşturur.

Bu yöntem alfa değeri için 32‑bit bir değerin geçirilmesine izin verse de, değer 8 bit ile sınırlıdır.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alpha | `int` | Yeni Color için alfa değeri. Geçerli değerler 0 ile 255 arasındadır. |
| base_color | `Color` | Yeni Color oluşturulacak Color. |

**Returns:** Color: The Color that this method creates.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Alfa 0'dan küçük veya 255'ten büyüktür. |

### Örnek

```python
from groupdocs.watermark.watermarks import Color

# Yarı saydam kırmızı bir renk oluştur (alfa 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Belirtilen 8 bitlik kırmızı, yeşil ve mavi değerlerinden bir [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) oluşturur; alfa kanalı varsayılan olarak 255 (tamamen opak) olarak ayarlanır.

Bu yöntem her renk bileşeni için 32‑bit bir değerin geçirilmesine izin verse de, her bileşen 8 bit ile sınırlıdır.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| red | `int` | Yeni `Color` için kırmızı bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| green | `int` | Yeni `Color` için yeşil bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| blue | `int` | Yeni `Color` için mavi bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:** Color: The color that this method creates.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Kırmızı, yeşil veya mavi 0'dan küçük veya 255'ten büyüktür. |

## from_argb {#alpha-red-green-blue}

Dört ARGB bileşen değerinden (alfa, kırmızı, yeşil ve mavi) bir [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) oluşturur.

Bu yöntem her bileşen için 32‑bit bir değerin geçirilmesine izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alpha | `int` | Yeni `Color` için alfa bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| red | `int` | Yeni `Color` için kırmızı bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| green | `int` | Yeni `Color` için yeşil bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| blue | `int` | Yeni `Color` için mavi bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:** Color: The `Color` that this method creates.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Kırmızı, yeşil veya mavi 0'dan küçük veya 255'ten büyüktür. |

### Örnek

```python
from groupdocs.watermark.watermarks import Color

# Tamamen opak kırmızı bir renk oluştur
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Ayrıca Bakınız
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
