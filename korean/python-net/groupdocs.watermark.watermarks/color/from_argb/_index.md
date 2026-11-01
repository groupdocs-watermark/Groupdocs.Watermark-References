---
title: "from_argb 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "32비트 ARGB 값으로부터 Color 구조를 생성합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

32비트 ARGB 값으로부터 Color 구조를 생성합니다.

```python
def from_argb(cls, argb):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| argb | `int` | 32비트 ARGB 값을 지정하는 값입니다. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

지정된 기본 Color에서 새로운 알파 값으로 Color 구조를 생성합니다.

이 메서드는 알파 값에 대해 32비트 값을 전달할 수 있지만, 해당 값은 8비트로 제한됩니다.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| alpha | `int` | 새 Color의 알파 값입니다. 유효한 값은 0부터 255까지입니다. |
| base_color | `Color` | 새 Color를 생성할 기준이 되는 Color입니다. |

**Returns:** Color: The Color that this method creates.

| 예외 | 설명 |
| :- | :- |
| `ValueError` | 알파 값이 0보다 작거나 255보다 큽니다. |

### 예시

```python
from groupdocs.watermark.watermarks import Color

# 반투명 빨간색을 생성합니다 (알파 128).
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

지정된 8‑bit 빨강, 초록 및 파랑 값으로부터 [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)을 생성하고, 알파 채널은 암묵적으로 255(완전 불투명)로 설정됩니다.

이 메서드는 각 색 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소는 8비트로 제한됩니다.

```python
def from_argb(cls, red, green, blue):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| red | `int` | 새 `Color`의 빨간색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| green | `int` | 새 `Color`의 녹색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| blue | `int` | 새 `Color`의 파란색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:** Color: The color that this method creates.

| 예외 | 설명 |
| :- | :- |
| `ValueError` | 빨강, 녹색 또는 파랑 값이 0보다 작거나 255보다 큽니다. |

## from_argb {#alpha-red-green-blue}

네 개의 ARGB 구성 요소 값(알파, 빨강, 초록, 파랑)으로부터 [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)을 생성합니다.

이 메서드는 각 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| alpha | `int` | 새 `Color`의 알파 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| red | `int` | 새 `Color`의 빨간색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| green | `int` | 새 `Color`의 녹색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| blue | `int` | 새 `Color`의 파란색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:** Color: The `Color` that this method creates.

| 예외 | 설명 |
| :- | :- |
| `ValueError` | 빨강, 녹색 또는 파랑 값이 0보다 작거나 255보다 큽니다. |

### 예시

```python
from groupdocs.watermark.watermarks import Color

# 완전 불투명한 빨간색을 생성합니다.
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### 또 보기
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
