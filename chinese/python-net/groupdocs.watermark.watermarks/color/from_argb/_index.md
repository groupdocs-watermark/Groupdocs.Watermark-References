---
title: "from_argb 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "从 32 位 ARGB 值创建 Color 结构。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

从 32 位 ARGB 值创建 Color 结构。

```python
def from_argb(cls, argb):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| argb | `int` | 指定 32 位 ARGB 值的参数。 |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

从指定的基 Color 创建 Color 结构，但使用新的 alpha 值。

虽然此方法允许为 alpha 值传入 32 位值，但该值限制为 8 位。

```python
def from_argb(cls, alpha, base_color):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alpha | `int` | 新 Color 的 alpha 值。有效范围为 0 到 255。 |
| base_color | `Color` | 用于创建新 Color 的原始 Color。 |

**Returns:** Color: The Color that this method creates.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | Alpha 小于 0 或大于 255。 |

### 示例

```python
from groupdocs.watermark.watermarks import Color

# 创建半透明的红色 (alpha 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

根据指定的 8 位红、绿、蓝值创建 [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)，并将 alpha 通道隐式设为 255（完全不透明）。

虽然此方法允许为每个颜色分量传入 32 位值，但每个分量限制为 8 位。

```python
def from_argb(cls, red, green, blue):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| red | `int` | 新 `Color` 的红色分量值。有效范围为 0 到 255。 |
| green | `int` | 新 `Color` 的绿色分量值。有效范围为 0 到 255。 |
| blue | `int` | 新 `Color` 的蓝色分量值。有效范围为 0 到 255。 |

**Returns:** Color: The color that this method creates.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 红、绿或蓝的值小于 0 或大于 255。 |

## from_argb {#alpha-red-green-blue}

根据四个 ARGB 分量值（alpha、红、绿、蓝）创建 [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)。

虽然此方法允许为每个分量传入 32 位值，但每个分量的值限制为 8 位。

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alpha | `int` | 新 `Color` 的 alpha 分量值。有效范围为 0 到 255。 |
| red | `int` | 新 `Color` 的红色分量值。有效范围为 0 到 255。 |
| green | `int` | 新 `Color` 的绿色分量值。有效范围为 0 到 255。 |
| blue | `int` | 新 `Color` 的蓝色分量值。有效范围为 0 到 255。 |

**Returns:** Color: The `Color` that this method creates.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 红、绿或蓝的值小于 0 或大于 255。 |

### 示例

```python
from groupdocs.watermark.watermarks import Color

# 创建完全不透明的红色
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### 另请参见
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
