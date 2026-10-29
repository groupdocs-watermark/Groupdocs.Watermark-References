---
title: "FromArgb"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "从 32 位 ARGB 值创建一个 Colorgroupdocs.watermark.watermarks/color 结构。"
type: docs
weight: 1430
url: /zh/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

从 32 位 ARGB 值创建一个 [`Color`](../../color) 结构。

```csharp
public static Color FromArgb(int argb)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| argb | Int32 | 指定 32 位 ARGB 值的数值。 |

### 返回值

此方法创建的 [`Color`](../../color) 结构。

### 另请参阅

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

从指定的 [`Color`](../../color) 结构创建一个 [`Color`](../../color) 结构，但使用新的指定 alpha 值。

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| alpha | Int32 | 新 [`Color`](../../color) 的 alpha 值。有效值范围为 0 到 255。 |
| baseColor | Color | 用于创建新 [`Color`](../../color) 的 [`Color`](../../color)。 |

### 返回值

此方法创建的 [`Color`](../../color)。

### Exceptions

| exception | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | Alpha 小于 0 或大于 255。 |

### 备注

虽然此方法允许为 alpha 值传入 32 位整数，但该值仅限于 8 位。

### 另请参阅

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

从指定的 8 位颜色值（红、绿、蓝）创建一个 [`Color`](../../color) 结构，且 alpha 值隐式为 255（完全不透明）。

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| red | Int32 | 新 [`Color`](../../color) 的红色分量值。有效值范围为 0 到 255。 |
| green | Int32 | 新 [`Color`](../../color) 的绿色分量值。有效值范围为 0 到 255。 |
| blue | Int32 | 新 [`Color`](../../color) 的蓝色分量值。有效值范围为 0 到 255。 |

### 返回值

此方法创建的 [`Color`](../../color)。

### Exceptions

| exception | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 红、绿或蓝的值小于 0 或大于 255。 |

### 备注

虽然此方法允许为每个颜色分量传入 32 位整数，但每个分量的值仅限于 8 位。

### 另请参阅

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

从四个 ARGB 分量（alpha、红、绿、蓝）值创建一个 [`Color`](../../color) 结构。

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| alpha | Int32 | 新 [`Color`](../../color) 的 alpha 分量值。有效值范围为 0 到 255。 |
| red | Int32 | 新 [`Color`](../../color) 的红色分量值。有效值范围为 0 到 255。 |
| green | Int32 | 新 [`Color`](../../color) 的绿色分量值。有效值范围为 0 到 255。 |
| blue | Int32 | 新 [`Color`](../../color) 的蓝色分量值。有效值范围为 0 到 255。 |

### 返回值

此方法创建的 [`Color`](../../color)。

### Exceptions

| exception | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 红、绿或蓝的值小于 0 或大于 255。 |

### 备注

虽然此方法允许为每个分量传入 32 位整数，但每个分量的值仅限于 8 位。

### 另请参阅

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
