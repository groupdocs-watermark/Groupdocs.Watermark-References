---
title: "from_argb methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Maakt een Color-structuur aan vanuit een 32-bits ARGB-waarde."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Maakt een Color-structuur aan vanuit een 32-bits ARGB-waarde.

```python
def from_argb(cls, argb):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb | `int` | Een waarde die de 32-bit ARGB-waarde specificeert. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Maakt een Color-structuur aan vanuit de opgegeven basis‑Color, maar met een nieuwe alfa‑waarde.

Hoewel deze methode een 32‑bits waarde toestaat voor de alpha‑waarde, is de waarde beperkt tot 8 bits.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alpha | `int` | De alpha‑waarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |
| base_color | `Color` | De Color waaruit de nieuwe Color moet worden gemaakt. |

**Returns:** Color: The Color that this method creates.

| Verhoogt | Beschrijving |
| :- | :- |
| `ValueError` | Alpha is kleiner dan 0 of groter dan 255. |

### Voorbeeld

```python
from groupdocs.watermark.watermarks import Color

# Maak een semi‑transparante rode kleur (alpha 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Maakt een [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) aan vanuit de opgegeven 8‑bit rode, groene en blauwe waarden, waarbij het alfakanaal impliciet wordt ingesteld op 255 (volledig ondoorzichtig).

Hoewel deze methode een 32‑bits waarde toestaat voor elk kleurcomponent, is elk component beperkt tot 8 bits.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| red | `int` | De rode componentwaarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |
| green | `int` | De groene componentwaarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |
| blue | `int` | De blauwe componentwaarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |

**Returns:** Color: The color that this method creates.

| Verhoogt | Beschrijving |
| :- | :- |
| `ValueError` | Rood, groen of blauw is kleiner dan 0 of groter dan 255. |

## from_argb {#alpha-red-green-blue}

Maakt een [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) aan vanuit de vier ARGB‑componentwaarden (alfa, rood, groen en blauw).

Hoewel deze methode een 32‑bits waarde toestaat voor elk component, is de waarde van elk component beperkt tot 8 bits.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alpha | `int` | De alpha‑componentwaarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |
| red | `int` | De rode componentwaarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |
| green | `int` | De groene componentwaarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |
| blue | `int` | De blauwe componentwaarde voor de nieuwe `Color`. Geldige waarden zijn 0 tot en met 255. |

**Returns:** Color: The `Color` that this method creates.

| Verhoogt | Beschrijving |
| :- | :- |
| `ValueError` | Rood, groen of blauw is kleiner dan 0 of groter dan 255. |

### Voorbeeld

```python
from groupdocs.watermark.watermarks import Color

# Maak een volledig ondoorzichtige rode kleur
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Zie ook
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
