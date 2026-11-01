---
title: "from_argb メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "32 ビット ARGB 値から Color 構造体を作成します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

32 ビット ARGB 値から Color 構造体を作成します。

```python
def from_argb(cls, argb):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| argb | `int` | 32ビット ARGB 値を指定する値です。 |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

指定されたベース Color から、アルファ値を新しくした Color 構造体を作成します。

このメソッドはアルファ値に 32 ビットの値を渡すことを許可しますが、その値は 8 ビットに制限されます。

```python
def from_argb(cls, alpha, base_color):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alpha | `int` | 新しい Color のアルファ値です。有効な値は 0 から 255 です。 |
| base_color | `Color` | 新しい Color を作成する元となる Color です。 |

**Returns:** Color: The Color that this method creates.

| 例外が発生 | 説明 |
| :- | :- |
| `ValueError` | アルファが 0 未満または 255 より大きいです。 |

### 例

```python
from groupdocs.watermark.watermarks import Color

# 半透明の赤色を作成します（アルファ 128）
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

指定された 8 ビットの赤、緑、青の値から[`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)を作成し、アルファチャンネルは暗黙的に 255（完全に不透明）に設定されます。

このメソッドは各色成分に 32 ビットの値を渡すことを許可しますが、各成分は 8 ビットに制限されます。

```python
def from_argb(cls, red, green, blue):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| red | `int` | 新しい `Color` の赤成分の値です。有効な値は 0 から 255 です。 |
| green | `int` | 新しい `Color` の緑成分の値です。有効な値は 0 から 255 です。 |
| blue | `int` | 新しい `Color` の青成分の値です。有効な値は 0 から 255 です。 |

**Returns:** Color: The color that this method creates.

| 例外が発生 | 説明 |
| :- | :- |
| `ValueError` | 赤、緑、青のいずれかが 0 未満または 255 より大きいです。 |

## from_argb {#alpha-red-green-blue}

4 つの ARGB コンポーネント値（アルファ、赤、緑、青）から[`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)を作成します。

このメソッドは各成分に 32 ビットの値を渡すことを許可しますが、各成分の値は 8 ビットに制限されます。

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alpha | `int` | 新しい `Color` のアルファ成分の値です。有効な値は 0 から 255 です。 |
| red | `int` | 新しい `Color` の赤成分の値です。有効な値は 0 から 255 です。 |
| green | `int` | 新しい `Color` の緑成分の値です。有効な値は 0 から 255 です。 |
| blue | `int` | 新しい `Color` の青成分の値です。有効な値は 0 から 255 です。 |

**Returns:** Color: The `Color` that this method creates.

| 例外が発生 | 説明 |
| :- | :- |
| `ValueError` | 赤、緑、青のいずれかが 0 未満または 255 より大きいです。 |

### 例

```python
from groupdocs.watermark.watermarks import Color

# 完全に不透明な赤色を作成します
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### 関連項目
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
