---
title: "from_argb طريقة"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينشئ هيكل Color من قيمة ARGB 32‑بت."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/color/from_argb/
is_root: false
weight: 1040
---


## from_argb {#argb}

ينشئ هيكل Color من قيمة ARGB 32‑بت.

```python
def from_argb(cls, argb):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| argb | `int` | قيمة تحدد قيمة ARGB ذات 32 بت. |

**Returns:** Color: The Color structure that this method creates.

## from_argb {#alpha-base_color}

ينشئ هيكل Color من اللون الأساسي المحدد ولكن بقيمة ألفا جديدة.

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لقيمة ألفا، فإن القيمة محدودة بـ 8 بت.

```python
def from_argb(cls, alpha, base_color):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| alpha | `int` | قيمة ألفا للون الجديد. القيم الصالحة هي من 0 إلى 255. |
| base_color | `Color` | اللون الذي يُنشأ منه اللون الجديد. |

**Returns:** Color: The Color that this method creates.

| يطرح | الوصف |
| :- | :- |
| `ValueError` | قيمة ألفا أقل من 0 أو أكبر من 255. |

### مثال

```python
from groupdocs.watermark.watermarks import Color

# إنشاء لون أحمر شبه شفاف (ألفا 128)
transparent_red = Color.from_argb(128, Color.red)
```

## from_argb {#red-green-blue}

ينشئ [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) من قيم الأحمر، الأخضر، والأزرق 8‑بت المحددة، مع ضبط قناة ألفا ضمنيًا إلى 255 (معتمة تمامًا).

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن لون، فإن كل مكوّن محدود بـ 8 بت.

```python
def from_argb(cls, red, green, blue):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| red | `int` | قيمة المكوّن الأحمر للون الجديد `Color`. القيم الصالحة هي من 0 إلى 255. |
| green | `int` | قيمة المكوّن الأخضر للون الجديد `Color`. القيم الصالحة هي من 0 إلى 255. |
| blue | `int` | قيمة المكوّن الأزرق للون الجديد `Color`. القيم الصالحة هي من 0 إلى 255. |

**Returns:** Color: The color that this method creates.

| يطرح | الوصف |
| :- | :- |
| `ValueError` | القيمة الحمراء أو الخضراء أو الزرقاء أقل من 0 أو أكبر من 255. |

## from_argb {#alpha-red-green-blue}

ينشئ [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) من القيم الأربعة لمكونات ARGB (ألفا، أحمر، أخضر، وأزرق).

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن، فإن قيمة كل مكوّن محدودة بـ 8 بت.

```python
def from_argb(cls, alpha, red, green, blue):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| alpha | `int` | قيمة مكوّن ألفا للون الجديد `Color`. القيم الصالحة هي من 0 إلى 255. |
| red | `int` | قيمة المكوّن الأحمر للون الجديد `Color`. القيم الصالحة هي من 0 إلى 255. |
| green | `int` | قيمة المكوّن الأخضر للون الجديد `Color`. القيم الصالحة هي من 0 إلى 255. |
| blue | `int` | قيمة المكوّن الأزرق للون الجديد `Color`. القيم الصالحة هي من 0 إلى 255. |

**Returns:** Color: The `Color` that this method creates.

| يطرح | الوصف |
| :- | :- |
| `ValueError` | القيمة الحمراء أو الخضراء أو الزرقاء أقل من 0 أو أكبر من 255. |

### مثال

```python
from groupdocs.watermark.watermarks import Color

# إنشاء لون أحمر غير شفاف تمامًا
red_color = Color.from_argb(255, 255, 0, 0)
print(red_color)  # Output: Color(A=255, R=255, G=0, B=0)
```

### انظر أيضًا
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
