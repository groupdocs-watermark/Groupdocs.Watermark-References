---
title: "FromArgb"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "ينشئ بنية Colorgroupdocs.watermark.watermarks/color من قيمة ARGB 32 بت."
type: docs
weight: 1430
url: /ar/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

ينشئ بنية [`Color`](../../color) من قيمة ARGB 32‑بت.

```csharp
public static Color FromArgb(int argb)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| argb | Int32 | قيمة تحدد قيمة ARGB 32‑بت. |

### قيمة الإرجاع

بنية [`Color`](../../color) التي ينشئها هذا الأسلوب.

### انظر أيضاً

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

ينشئ بنية [`Color`](../../color) من بنية [`Color`](../../color) المحددة، ولكن مع قيمة ألفا الجديدة المحددة.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| alpha | Int32 | قيمة الألفا للبنية [`Color`](../../color) الجديدة. القيم الصالحة هي من 0 إلى 255. |
| baseColor | Color | بنية [`Color`](../../color) التي يُنشأ منها البنية [`Color`](../../color) الجديدة. |

### قيمة الإرجاع

بنية [`Color`](../../color) التي ينشئها هذا الأسلوب.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | قيمة الألفا أقل من 0 أو أكبر من 255. |

### ملاحظات

على الرغم من أن هذا الأسلوب يسمح بتمرير قيمة 32‑بت لقيمة الألفا، فإن القيمة مقيدة بـ 8‑بت.

### انظر أيضاً

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

ينشئ بنية [`Color`](../../color) من قيم الألوان 8‑بت المحددة (الأحمر، الأخضر، والأزرق) وتكون قيمة الألفا ضمنيًا 255 (معتمة تمامًا).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| red | Int32 | قيمة المكوّن الأحمر للبنية [`Color`](../../color) الجديدة. القيم الصالحة هي من 0 إلى 255. |
| green | Int32 | قيمة المكوّن الأخضر للبنية [`Color`](../../color) الجديدة. القيم الصالحة هي من 0 إلى 255. |
| blue | Int32 | قيمة مكوّن اللون الأزرق للـ [`Color`](../../color) الجديد. القيم الصالحة هي من 0 إلى 255. |

### قيمة الإرجاع

بنية [`Color`](../../color) التي ينشئها هذا الأسلوب.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | القيمة الحمراء أو الخضراء أو الزرقاء أقل من 0 أو أكبر من 255. |

### ملاحظات

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32-بت لكل مكوّن لوني، فإن قيمة كل مكوّن محدودة بـ 8 بت.

### انظر أيضاً

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

ينشئ بنية [`Color`](../../color) من القيم الأربعة لمكوّنات ARGB (ألفا، أحمر، أخضر، وأزرق).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| alpha | Int32 | قيمة مكوّن الألفا للـ [`Color`](../../color) الجديد. القيم الصالحة هي من 0 إلى 255. |
| red | Int32 | قيمة المكوّن الأحمر للبنية [`Color`](../../color) الجديدة. القيم الصالحة هي من 0 إلى 255. |
| green | Int32 | قيمة المكوّن الأخضر للبنية [`Color`](../../color) الجديدة. القيم الصالحة هي من 0 إلى 255. |
| blue | Int32 | قيمة مكوّن اللون الأزرق للـ [`Color`](../../color) الجديد. القيم الصالحة هي من 0 إلى 255. |

### قيمة الإرجاع

بنية [`Color`](../../color) التي ينشئها هذا الأسلوب.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | القيمة الحمراء أو الخضراء أو الزرقاء أقل من 0 أو أكبر من 255. |

### ملاحظات

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32-بت لكل مكوّن، فإن قيمة كل مكوّن محدودة بـ 8 بت.

### انظر أيضاً

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
