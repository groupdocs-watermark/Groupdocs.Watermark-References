---
title: "from_argb metodo"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Crea una struttura Color da un valore ARGB a 32 bit."
type: docs
url: /it/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Crea una struttura Color da un valore ARGB a 32 bit.

```python
def from_argb(cls, argb):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | `int` | Un valore che specifica il valore ARGB a 32 bit. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Crea una struttura Color dal Color base specificato ma con un nuovo valore alpha.

Sebbene questo metodo consenta di passare un valore a 32 bit per il valore alfa, il valore è limitato a 8 bit.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alpha | `int` | Il valore alfa per il nuovo Color. I valori validi sono da 0 a 255. |
| base_color | `Color` | Il Color da cui creare il nuovo Color. |

**Returns:** Color: The Color that this method creates.

| Genera | Descrizione |
| :- | :- |
| `ValueError` | Alfa è inferiore a 0 o superiore a 255. |

### Esempio

```python
from groupdocs.watermark.watermarks import Color

# Crea un colore rosso semi‑trasparente (alfa 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Crea un [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) dai valori rosso, verde e blu a 8‑bit specificati, impostando implicitamente il canale alpha a 255 (completamente opaco).

Sebbene questo metodo consenta di passare un valore a 32 bit per ogni componente di colore, ogni componente è limitato a 8 bit.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| red | `int` | Il valore del componente rosso per il nuovo `Color`. I valori validi sono da 0 a 255. |
| green | `int` | Il valore del componente verde per il nuovo `Color`. I valori validi sono da 0 a 255. |
| blue | `int` | Il valore del componente blu per il nuovo `Color`. I valori validi sono da 0 a 255. |

**Returns:** Color: The color that this method creates.

| Genera | Descrizione |
| :- | :- |
| `ValueError` | Rosso, verde o blu è inferiore a 0 o superiore a 255. |

## from_argb {#alpha-red-green-blue}

Crea un [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) dai quattro valori dei componenti ARGB (alpha, rosso, verde e blu).

Sebbene questo metodo consenta di passare un valore a 32 bit per ogni componente, il valore di ogni componente è limitato a 8 bit.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alpha | `int` | Il valore del componente alfa per il nuovo `Color`. I valori validi sono da 0 a 255. |
| red | `int` | Il valore del componente rosso per il nuovo `Color`. I valori validi sono da 0 a 255. |
| green | `int` | Il valore del componente verde per il nuovo `Color`. I valori validi sono da 0 a 255. |
| blue | `int` | Il valore del componente blu per il nuovo `Color`. I valori validi sono da 0 a 255. |

**Returns:** Color: The `Color` that this method creates.

| Genera | Descrizione |
| :- | :- |
| `ValueError` | Rosso, verde o blu è inferiore a 0 o superiore a 255. |

### Esempio

```python
from groupdocs.watermark.watermarks import Color

# Crea un colore rosso completamente opaco
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Vedi anche
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
