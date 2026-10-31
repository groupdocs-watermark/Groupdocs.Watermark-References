---
title: "from_argb méthode"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Crée une structure Color à partir d'une valeur ARGB de 32 bits."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Crée une structure Color à partir d'une valeur ARGB de 32 bits.

```python
def from_argb(cls, argb):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| argb | `int` | Une valeur spécifiant la valeur ARGB 32 bits. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Crée une structure Color à partir de la couleur de base spécifiée mais avec une nouvelle valeur alpha.

Bien que cette méthode permette de passer une valeur 32 bits pour la valeur alpha, la valeur est limitée à 8 bits.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| alpha | `int` | La valeur alpha pour la nouvelle Color. Les valeurs valides sont de 0 à 255. |
| base_color | `Color` | La Color à partir de laquelle créer la nouvelle Color. |

**Returns:** Color: The Color that this method creates.

| Lève | Description |
| :- | :- |
| `ValueError` | Alpha est inférieur à 0 ou supérieur à 255. |

### Exemple

```python
from groupdocs.watermark.watermarks import Color

# Créer une couleur rouge semi‑transparente (alpha 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Crée un [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) à partir des valeurs rouge, vert et bleu de 8 bits spécifiées, le canal alpha étant implicitement réglé à 255 (pleinement opaque).

Bien que cette méthode permette de passer une valeur 32 bits pour chaque composant de couleur, chaque composant est limité à 8 bits.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| red | `int` | La valeur du composant rouge pour la nouvelle `Color`. Les valeurs valides sont de 0 à 255. |
| green | `int` | La valeur du composant vert pour la nouvelle `Color`. Les valeurs valides sont de 0 à 255. |
| blue | `int` | La valeur du composant bleu pour la nouvelle `Color`. Les valeurs valides sont de 0 à 255. |

**Returns:** Color: The color that this method creates.

| Lève | Description |
| :- | :- |
| `ValueError` | Le rouge, le vert ou le bleu est inférieur à 0 ou supérieur à 255. |

## from_argb {#alpha-red-green-blue}

Crée un [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) à partir des quatre valeurs de composant ARGB (alpha, rouge, vert et bleu).

Bien que cette méthode permette de passer une valeur 32 bits pour chaque composant, la valeur de chaque composant est limitée à 8 bits.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| alpha | `int` | La valeur du composant alpha pour la nouvelle `Color`. Les valeurs valides sont de 0 à 255. |
| red | `int` | La valeur du composant rouge pour la nouvelle `Color`. Les valeurs valides sont de 0 à 255. |
| green | `int` | La valeur du composant vert pour la nouvelle `Color`. Les valeurs valides sont de 0 à 255. |
| blue | `int` | La valeur du composant bleu pour la nouvelle `Color`. Les valeurs valides sont de 0 à 255. |

**Returns:** Color: The `Color` that this method creates.

| Lève | Description |
| :- | :- |
| `ValueError` | Le rouge, le vert ou le bleu est inférieur à 0 ou supérieur à 255. |

### Exemple

```python
from groupdocs.watermark.watermarks import Color

# Créer une couleur rouge totalement opaque
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Voir aussi
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
