---
title: "from_argb metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Skapar en Color-struktur från ett 32-bitars ARGB‑värde."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Skapar en Color-struktur från ett 32-bitars ARGB‑värde.

```python
def from_argb(cls, argb):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb | `int` | Ett värde som specificerar det 32‑bitars ARGB‑värdet. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Skapar en Color-struktur från den angivna bas‑Color men med ett nytt alfa‑värde.

Även om denna metod tillåter att ett 32‑bitars värde skickas för alfavärdet, är värdet begränsat till 8 bitar.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| alpha | `int` | Alfavärdet för den nya Color. Giltiga värden är 0 till 255. |
| base_color | `Color` | Colorn från vilken den nya Color ska skapas. |

**Returns:** Color: The Color that this method creates.

| Kastar | Beskrivning |
| :- | :- |
| `ValueError` | Alfa är mindre än 0 eller större än 255. |

### Exempel

```python
from groupdocs.watermark.watermarks import Color

# Skapa en semi‑transparent röd färg (alpha 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Skapar en [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) från de angivna 8‑bitars röd-, grön- och blåvärdena, med alfakanalen implicit inställd på 255 (fullt ogenomskinlig).

Även om den här metoden tillåter ett 32‑bitars värde att skickas för varje färgkomponent, är varje komponent begränsad till 8 bitar.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| red | `int` | Det röda komponentvärdet för den nya `Color`. Giltiga värden är 0 till 255. |
| green | `int` | Det gröna komponentvärdet för den nya `Color`. Giltiga värden är 0 till 255. |
| blue | `int` | Det blåa komponentvärdet för den nya `Color`. Giltiga värden är 0 till 255. |

**Returns:** Color: The color that this method creates.

| Kastar | Beskrivning |
| :- | :- |
| `ValueError` | Röd, grön eller blå är mindre än 0 eller större än 255. |

## from_argb {#alpha-red-green-blue}

Skapar en [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) från de fyra ARGB‑komponentvärdena (alfa, röd, grön och blå).

Även om den här metoden tillåter ett 32‑bitars värde att skickas för varje komponent, är värdet för varje komponent begränsat till 8 bitar.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| alpha | `int` | Det alfa‑komponentvärdet för den nya `Color`. Giltiga värden är 0 till 255. |
| red | `int` | Det röda komponentvärdet för den nya `Color`. Giltiga värden är 0 till 255. |
| green | `int` | Det gröna komponentvärdet för den nya `Color`. Giltiga värden är 0 till 255. |
| blue | `int` | Det blåa komponentvärdet för den nya `Color`. Giltiga värden är 0 till 255. |

**Returns:** Color: The `Color` that this method creates.

| Kastar | Beskrivning |
| :- | :- |
| `ValueError` | Röd, grön eller blå är mindre än 0 eller större än 255. |

### Exempel

```python
from groupdocs.watermark.watermarks import Color

# Skapa en helt ogenomskinlig röd färg
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Se även
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
