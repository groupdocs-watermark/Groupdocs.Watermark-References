---
title: "from_argb método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Crea una estructura Color a partir de un valor ARGB de 32 bits."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Crea una estructura Color a partir de un valor ARGB de 32 bits.

```python
def from_argb(cls, argb):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb | `int` | Un valor que especifica el valor ARGB de 32 bits. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Crea una estructura Color a partir del Color base especificado pero con un nuevo valor alfa.

Aunque este método permite pasar un valor de 32 bits para el valor alfa, el valor está limitado a 8 bits.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alpha | `int` | El valor alfa para el nuevo Color. Los valores válidos son de 0 a 255. |
| base_color | `Color` | El Color del cual crear el nuevo Color. |

**Returns:** Color: The Color that this method creates.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Alfa es menor que 0 o mayor que 255. |

### Ejemplo

```python
from groupdocs.watermark.watermarks import Color

# Crear un color rojo semi‑transparente (alfa 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

Crea un [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) a partir de los valores rojo, verde y azul de 8‑bit especificados, con el canal alfa establecido implícitamente a 255 (totalmente opaco).

Aunque este método permite pasar un valor de 32 bits para cada componente de color, cada componente está limitado a 8 bits.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| red | `int` | El valor del componente rojo para el nuevo `Color`. Los valores válidos son de 0 a 255. |
| green | `int` | El valor del componente verde para el nuevo `Color`. Los valores válidos son de 0 a 255. |
| blue | `int` | El valor del componente azul para el nuevo `Color`. Los valores válidos son de 0 a 255. |

**Returns:** Color: The color that this method creates.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Rojo, verde o azul es menor que 0 o mayor que 255. |

## from_argb {#alpha-red-green-blue}

Crea un [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) a partir de los cuatro valores de los componentes ARGB (alfa, rojo, verde y azul).

Aunque este método permite pasar un valor de 32 bits para cada componente, el valor de cada componente está limitado a 8 bits.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alpha | `int` | El valor del componente alfa para el nuevo `Color`. Los valores válidos son de 0 a 255. |
| red | `int` | El valor del componente rojo para el nuevo `Color`. Los valores válidos son de 0 a 255. |
| green | `int` | El valor del componente verde para el nuevo `Color`. Los valores válidos son de 0 a 255. |
| blue | `int` | El valor del componente azul para el nuevo `Color`. Los valores válidos son de 0 a 255. |

**Returns:** Color: The `Color` that this method creates.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Rojo, verde o azul es menor que 0 o mayor que 255. |

### Ejemplo

```python
from groupdocs.watermark.watermarks import Color

# Crear un color rojo totalmente opaco
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### Ver también
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
