---
title: from_argb method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Creates a Color structure from a 32-bit ARGB value."
type: docs
url: /python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

Creates a Color structure from a 32-bit ARGB value.

```python
def from_argb(cls, argb):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| argb | `int` | A value specifying the 32-bit ARGB value. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

Creates a Color structure from the specified base Color but with a new alpha value.

Although this method allows a 32-bit value to be passed for the alpha value, the value is limited to 8 bits.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| alpha | `int` | The alpha value for the new `Color`. Valid values are 0 through 255. |
| base_color | `Color` | The `Color` from which to create the new `Color`. |

**Returns:** `Color`: The `Color` that this method creates.

| Raises | Description |
| :- | :- |
| `ValueError` | Alpha is less than 0 or greater than 255. |

## from_argb {#red-green-blue}

Creates a Color structure from the specified 8‑bit red, green, and blue values; the alpha component is implicitly set to 255 (fully opaque).

Although this method allows a 32‑bit value to be passed for each color component, each component is limited to 8 bits.

```python
def from_argb(cls, red, green, blue):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| red | `int` | The red component value for the new Color. Valid values are 0 through 255. |
| green | `int` | The green component value for the new Color. Valid values are 0 through 255. |
| blue | `int` | The blue component value for the new Color. Valid values are 0 through 255. |

**Returns:** Color: The Color that this method creates.

| Raises | Description |
| :- | :- |
| `ValueError` | red, green, or blue is less than 0 or greater than 255. |

## from_argb {#alpha-red-green-blue}

Creates a [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) structure from the four ARGB component (alpha, red, green, and blue) values.

Although this method allows a 32-bit value to be passed for each component, the value of each component is limited to 8 bits.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| alpha | `int` | The alpha component value for the new `Color`. Valid values are 0 through 255. |
| red | `int` | The red component value for the new `Color`. Valid values are 0 through 255. |
| green | `int` | The green component value for the new `Color`. Valid values are 0 through 255. |
| blue | `int` | The blue component value for the new `Color`. Valid values are 0 through 255. |

**Returns:** Color: The `Color` that this method creates.

| Raises | Description |
| :- | :- |
| `ValueError` | Red, green, or blue is less than 0 or greater than 255. |

### See Also
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
