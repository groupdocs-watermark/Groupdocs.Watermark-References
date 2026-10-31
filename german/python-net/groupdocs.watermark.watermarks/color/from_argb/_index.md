---
title: "from_argb Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Erstellt eine Color-Struktur aus einem 32‑Bit‑ARGB‑Wert."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Erstellt eine Color-Struktur aus einem 32‑Bit‑ARGB‑Wert.

```python
def from_argb(cls, argb):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | `int` | Ein Wert, der den 32‑bit‑ARGB‑Wert angibt. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Erstellt eine Color-Struktur aus der angegebenen Basis‑Color, jedoch mit einem neuen Alpha‑Wert.

Obwohl diese Methode das Übergeben eines 32‑bit‑Wertes für den Alpha‑Wert erlaubt, ist der Wert auf 8 bits begrenzt.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alpha | `int` | Der Alpha‑Wert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |
| base_color | `Color` | Das `Color`, aus dem das neue `Color` erstellt werden soll. |

**Returns:** Color: The Color that this method creates.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Alpha ist kleiner als 0 oder größer als 255. |

### Beispiel

```python
from groupdocs.watermark.watermarks import Color

# Erstelle eine halbtransparente rote Farbe (Alpha 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Erstellt ein [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) aus den angegebenen 8‑Bit‑Rot-, Grün‑ und Blauwerten, wobei der Alpha‑Kanal implizit auf 255 (vollständig undurchsichtig) gesetzt wird.

Obwohl diese Methode das Übergeben eines 32‑bit‑Wertes für jede Farbkomponente erlaubt, ist jede Komponente auf 8 bits begrenzt.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| red | `int` | Der Rot‑Komponentenwert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |
| green | `int` | Der Grün‑Komponentenwert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |
| blue | `int` | Der Blau‑Komponentenwert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |

**Returns:** Color: The color that this method creates.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Rot, Grün oder Blau ist kleiner als 0 oder größer als 255. |

## from_argb {#alpha-red-green-blue}

Erstellt ein [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) aus den vier ARGB‑Komponentenwerten (Alpha, Rot, Grün und Blau).

Obwohl diese Methode das Übergeben eines 32‑bit‑Wertes für jede Komponente erlaubt, ist der Wert jeder Komponente auf 8 bits begrenzt.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alpha | `int` | Der Alpha‑Komponentenwert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |
| red | `int` | Der Rot‑Komponentenwert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |
| green | `int` | Der Grün‑Komponentenwert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |
| blue | `int` | Der Blau‑Komponentenwert für das neue `Color`. Gültige Werte liegen zwischen 0 und 255. |

**Returns:** Color: The `Color` that this method creates.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Rot, Grün oder Blau ist kleiner als 0 oder größer als 255. |

### Beispiel

```python
from groupdocs.watermark.watermarks import Color

# Erstelle eine vollständig undurchsichtige rote Farbe
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Siehe auch
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
