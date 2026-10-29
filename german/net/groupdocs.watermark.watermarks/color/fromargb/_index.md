---
title: "FromArgb"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Erstellt eine Colorgroupdocs.watermark.watermarks/color-Struktur aus einem 32‑Bit‑ARGB‑Wert."
type: docs
weight: 1430
url: /de/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Erstellt eine [`Color`](../../color)-Struktur aus einem 32‑Bit‑ARGB‑Wert.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| argb | Int32 | Ein Wert, der den 32‑Bit‑ARGB‑Wert angibt. |

### Rückgabewert

Die [`Color`](../../color)-Struktur, die diese Methode erstellt.

### Siehe auch

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Erstellt eine [`Color`](../../color)-Struktur aus der angegebenen [`Color`](../../color)-Struktur, jedoch mit dem neu angegebenen Alpha‑Wert.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| alpha | Int32 | Der Alpha‑Wert für die neue [`Color`](../../color). Gültige Werte liegen zwischen 0 und 255. |
| baseColor | Color | Die [`Color`](../../color), aus der die neue [`Color`](../../color) erstellt wird. |

### Rückgabewert

Die [`Color`](../../color), die diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Alpha ist kleiner als 0 oder größer als 255. |

### Hinweise

Obwohl diese Methode das Übergeben eines 32‑Bit‑Werts für den Alpha‑Wert erlaubt, ist der Wert auf 8 Bit begrenzt.

### Siehe auch

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Erstellt eine [`Color`](../../color)-Struktur aus den angegebenen 8‑Bit‑Farbwerten (Rot, Grün und Blau), wobei der Alpha‑Wert implizit 255 (vollständig undurchsichtig) ist.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| red | Int32 | Der Rot‑Komponentenwert für die neue [`Color`](../../color). Gültige Werte liegen zwischen 0 und 255. |
| green | Int32 | Der Grün‑Komponentenwert für die neue [`Color`](../../color). Gültige Werte liegen zwischen 0 und 255. |
| blue | Int32 | Der Blaukomponentenwert für das neue [`Color`](../../color). Gültige Werte sind 0 bis 255. |

### Rückgabewert

Die [`Color`](../../color), die diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Rot, Grün oder Blau ist kleiner als 0 oder größer als 255. |

### Hinweise

Obwohl diese Methode einen 32‑Bit‑Wert für jede Farbkomponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

### Siehe auch

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Erstellt eine [`Color`](../../color)-Struktur aus den vier ARGB‑Komponenten (Alpha, Rot, Grün und Blau) Werten.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| alpha | Int32 | Der Alphakomponentenwert für das neue [`Color`](../../color). Gültige Werte sind 0 bis 255. |
| red | Int32 | Der Rot‑Komponentenwert für die neue [`Color`](../../color). Gültige Werte liegen zwischen 0 und 255. |
| green | Int32 | Der Grün‑Komponentenwert für die neue [`Color`](../../color). Gültige Werte liegen zwischen 0 und 255. |
| blue | Int32 | Der Blaukomponentenwert für das neue [`Color`](../../color). Gültige Werte sind 0 bis 255. |

### Rückgabewert

Die [`Color`](../../color), die diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Rot, Grün oder Blau ist kleiner als 0 oder größer als 255. |

### Hinweise

Obwohl diese Methode einen 32‑Bit‑Wert für jede Komponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

### Siehe auch

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
