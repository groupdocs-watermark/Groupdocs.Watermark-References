---
title: "from_argb metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Membuat struktur Color dari nilai ARGB 32-bit."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Membuat struktur Color dari nilai ARGB 32-bit.

```python
def from_argb(cls, argb):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| argb | `int` | Nilai yang menentukan nilai ARGB 32-bit. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Membuat struktur Color dari Color dasar yang ditentukan tetapi dengan nilai alpha baru.

Meskipun metode ini memungkinkan nilai 32‑bit diteruskan untuk nilai alfa, nilai tersebut dibatasi hingga 8 bit.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alpha | `int` | Nilai alfa untuk Color baru. Nilai yang valid adalah 0 hingga 255. |
| base_color | `Color` | Color yang menjadi sumber untuk membuat Color baru. |

**Returns:** Color: The Color that this method creates.

| Menaikkan | Deskripsi |
| :- | :- |
| `ValueError` | Alfa kurang dari 0 atau lebih besar dari 255. |

### Contoh

```python
from groupdocs.watermark.watermarks import Color

# Buat warna merah semi‑transparan (alfa 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Membuat [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) dari nilai merah, hijau, dan biru 8‑bit yang ditentukan, dengan saluran alpha secara implisit diatur ke 255 (sepenuhnya tidak transparan).

Meskipun metode ini memungkinkan nilai 32‑bit diteruskan untuk setiap komponen warna, setiap komponen dibatasi hingga 8 bit.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| red | `int` | Nilai komponen merah untuk `Color` baru. Nilai yang valid adalah 0 hingga 255. |
| green | `int` | Nilai komponen hijau untuk `Color` baru. Nilai yang valid adalah 0 hingga 255. |
| blue | `int` | Nilai komponen biru untuk `Color` baru. Nilai yang valid adalah 0 hingga 255. |

**Returns:** Color: The color that this method creates.

| Menaikkan | Deskripsi |
| :- | :- |
| `ValueError` | Merah, hijau, atau biru kurang dari 0 atau lebih besar dari 255. |

## from_argb {#alpha-red-green-blue}

Membuat [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) dari empat nilai komponen ARGB (alpha, merah, hijau, dan biru).

Meskipun metode ini memungkinkan nilai 32‑bit diteruskan untuk setiap komponen, nilai setiap komponen dibatasi hingga 8 bit.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alpha | `int` | Nilai komponen alfa untuk `Color` baru. Nilai yang valid adalah 0 hingga 255. |
| red | `int` | Nilai komponen merah untuk `Color` baru. Nilai yang valid adalah 0 hingga 255. |
| green | `int` | Nilai komponen hijau untuk `Color` baru. Nilai yang valid adalah 0 hingga 255. |
| blue | `int` | Nilai komponen biru untuk `Color` baru. Nilai yang valid adalah 0 hingga 255. |

**Returns:** Color: The `Color` that this method creates.

| Menaikkan | Deskripsi |
| :- | :- |
| `ValueError` | Merah, hijau, atau biru kurang dari 0 atau lebih besar dari 255. |

### Contoh

```python
from groupdocs.watermark.watermarks import Color

# Buat warna merah yang sepenuhnya tidak tembus pandang
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Lihat Juga
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
