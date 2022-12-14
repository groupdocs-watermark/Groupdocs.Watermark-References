---
title: FromArgb
second_title: GroupDocs.Watermark لـ .NET API Reference
description: ينشئ ملفColorgroupdocs.watermark.watermarks/color بنية من قيمة ARGB 32 بت.
type: docs
weight: 1430
url: /ar/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

ينشئ ملف[`Color`](../../color) بنية من قيمة ARGB 32 بت.

```csharp
public static Color FromArgb(int argb)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| argb | Int32 | قيمة تحدد قيمة ARGB 32 بت. |

### قيمة الإرجاع

ال[`Color`](../../color) الهيكل الذي تخلقه هذه الطريقة.

### أنظر أيضا

* struct [Color](../../color)
* مساحة الاسم [GroupDocs.Watermark.Watermarks](../../color)
* المجسم [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

ينشئ ملف[`Color`](../../color) هيكل من المحدد[`Color`](../../color) بنية ، ولكن بقيمة ألفا الجديدة المحددة.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| alpha | Int32 | قيمة ألفا الجديدة[`Color`](../../color). القيم الصالحة من 0 إلى 255. |
| baseColor | Color | ال[`Color`](../../color) التي يتم إنشاء الجديد منها[`Color`](../../color). |

### قيمة الإرجاع

ال[`Color`](../../color) التي تخلقها هذه الطريقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | ألفا أقل من 0 أو أكبر من 255. |

### ملاحظات

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32 بت لقيمة ألفا ، فإن القيمة تقتصر على 8 بت.

### أنظر أيضا

* struct [Color](../../color)
* مساحة الاسم [GroupDocs.Watermark.Watermarks](../../color)
* المجسم [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

ينشئ ملف[`Color`](../../color)بنية من قيم الألوان المحددة 8 بت (الأحمر والأخضر والأزرق) و قيمة ألفا ضمنيًا 255 (معتم بالكامل).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| red | Int32 | قيمة المكون الأحمر للجديد[`Color`](../../color). القيم الصالحة من 0 إلى 255. |
| green | Int32 | قيمة المكون الأخضر للجديد[`Color`](../../color). القيم الصالحة من 0 إلى 255. |
| blue | Int32 | قيمة المكون الأزرق للجديد[`Color`](../../color). القيم الصالحة من 0 إلى 255. |

### قيمة الإرجاع

ال[`Color`](../../color) التي تخلقها هذه الطريقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | الأحمر أو الأخضر أو الأزرق أقل من 0 أو أكبر من 255. |

### ملاحظات

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32 بت لكل مكون لون ، فإن قيمة كل مكون تقتصر على 8 بت.

### أنظر أيضا

* struct [Color](../../color)
* مساحة الاسم [GroupDocs.Watermark.Watermarks](../../color)
* المجسم [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

ينشئ ملف[`Color`](../../color) هيكل من قيم مكون ARGB الأربعة (ألفا ، أحمر ، أخضر ، وأزرق).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| alpha | Int32 | قيمة مكون ألفا لملف[`Color`](../../color). القيم الصالحة من 0 إلى 255. |
| red | Int32 | قيمة المكون الأحمر للجديد[`Color`](../../color). القيم الصالحة من 0 إلى 255. |
| green | Int32 | قيمة المكون الأخضر للجديد[`Color`](../../color). القيم الصالحة من 0 إلى 255. |
| blue | Int32 | قيمة المكون الأزرق للجديد[`Color`](../../color). القيم الصالحة من 0 إلى 255. |

### قيمة الإرجاع

ال[`Color`](../../color) التي تخلقها هذه الطريقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | الأحمر أو الأخضر أو الأزرق أقل من 0 أو أكبر من 255. |

### ملاحظات

على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32 بت لكل مكون ، قيمة كل مكون تقتصر على 8 بت.

### أنظر أيضا

* struct [Color](../../color)
* مساحة الاسم [GroupDocs.Watermark.Watermarks](../../color)
* المجسم [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
