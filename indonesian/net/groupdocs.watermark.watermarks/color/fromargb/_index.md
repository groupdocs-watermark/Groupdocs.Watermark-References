---
title: "FromArgb"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Membuat struktur Colorgroupdocs.watermark.watermarks/color dari nilai ARGB 32bit."
type: docs
weight: 1430
url: /id/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Membuat struktur [`Color`](../../color) dari nilai ARGB 32-bit.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| argb | Int32 | Nilai yang menentukan nilai ARGB 32-bit. |

### Nilai Kembalian

Struktur [`Color`](../../color) yang dibuat oleh metode ini.

### Lihat Juga

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Membuat struktur [`Color`](../../color) dari struktur [`Color`](../../color) yang ditentukan, tetapi dengan nilai alfa baru yang ditentukan.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| alpha | Int32 | Nilai alfa untuk [`Color`](../../color) baru. Nilai yang valid antara 0 hingga 255. |
| baseColor | Color | [`Color`](../../color) yang akan digunakan untuk membuat [`Color`](../../color) baru. |

### Nilai Kembalian

[`Color`](../../color) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Alfa kurang dari 0 atau lebih besar dari 255. |

### Catatan

Meskipun metode ini memungkinkan nilai 32-bit diberikan untuk nilai alfa, nilai tersebut dibatasi hingga 8 bit.

### Lihat Juga

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Membuat struktur [`Color`](../../color) dari nilai warna 8-bit yang ditentukan (merah, hijau, dan biru) dan nilai alfa secara implisit adalah 255 (sepenuhnya tidak tembus).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| red | Int32 | Nilai komponen merah untuk [`Color`](../../color) baru. Nilai yang valid antara 0 hingga 255. |
| green | Int32 | Nilai komponen hijau untuk [`Color`](../../color) baru. Nilai yang valid antara 0 hingga 255. |
| blue | Int32 | Nilai komponen biru untuk [`Color`](../../color) yang baru. Nilai yang valid adalah 0 hingga 255. |

### Nilai Kembalian

[`Color`](../../color) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Merah, hijau, atau biru kurang dari 0 atau lebih besar dari 255. |

### Catatan

Meskipun metode ini memungkinkan nilai 32-bit diberikan untuk setiap komponen warna, nilai setiap komponen dibatasi hingga 8 bit.

### Lihat Juga

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Membuat struktur [`Color`](../../color) dari empat nilai komponen ARGB (alpha, merah, hijau, dan biru).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| alpha | Int32 | Nilai komponen alfa untuk [`Color`](../../color) yang baru. Nilai yang valid adalah 0 hingga 255. |
| red | Int32 | Nilai komponen merah untuk [`Color`](../../color) baru. Nilai yang valid antara 0 hingga 255. |
| green | Int32 | Nilai komponen hijau untuk [`Color`](../../color) baru. Nilai yang valid antara 0 hingga 255. |
| blue | Int32 | Nilai komponen biru untuk [`Color`](../../color) yang baru. Nilai yang valid adalah 0 hingga 255. |

### Nilai Kembalian

[`Color`](../../color) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Merah, hijau, atau biru kurang dari 0 atau lebih besar dari 255. |

### Catatan

Meskipun metode ini memungkinkan nilai 32-bit diberikan untuk setiap komponen, nilai setiap komponen dibatasi hingga 8 bit.

### Lihat Juga

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
