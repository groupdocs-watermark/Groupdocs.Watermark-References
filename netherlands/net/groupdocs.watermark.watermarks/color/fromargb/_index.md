---
title: "FromArgb"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Maakt een Colorgroupdocs.watermark.watermarks/color-structuur aan vanuit een 32-bit ARGB-waarde."
type: docs
weight: 1430
url: /nl/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Maakt een [`Color`](../../color) structuur aan vanuit een 32-bit ARGB-waarde.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb | Int32 | Een waarde die de 32-bit ARGB-waarde specificeert. |

### Retourwaarde

De [`Color`](../../color) structuur die deze methode maakt.

### Zie ook

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Maakt een [`Color`](../../color) structuur aan vanuit de opgegeven [`Color`](../../color) structuur, maar met de nieuw opgegeven alpha-waarde.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | Int32 | De alpha-waarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |
| baseColor | Color | De [`Color`](../../color) waarvan de nieuwe [`Color`](../../color) wordt gemaakt. |

### Retourwaarde

De [`Color`](../../color) die deze methode maakt.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentOutOfRangeException | Alpha is kleiner dan 0 of groter dan 255. |

### Opmerkingen

Hoewel deze methode een 32-bit waarde voor de alpha-waarde toestaat, is de waarde beperkt tot 8 bits.

### Zie ook

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Maakt een [`Color`](../../color) structuur aan vanuit de opgegeven 8-bit kleurwaarden (rood, groen en blauw) en de alpha-waarde is impliciet 255 (volledig ondoorzichtig).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| red | Int32 | De rode componentwaarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |
| green | Int32 | De groene componentwaarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |
| blue | Int32 | De blauwe componentwaarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |

### Retourwaarde

De [`Color`](../../color) die deze methode maakt.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentOutOfRangeException | Rood, groen of blauw is kleiner dan 0 of groter dan 255. |

### Opmerkingen

Hoewel deze methode een 32-bits waarde toestaat voor elke kleurcomponent, is de waarde van elke component beperkt tot 8 bits.

### Zie ook

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Maakt een [`Color`](../../color) structuur aan vanuit de vier ARGB-componenten (alpha, rood, groen en blauw) waarden.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | Int32 | De alfa componentwaarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |
| red | Int32 | De rode componentwaarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |
| green | Int32 | De groene componentwaarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |
| blue | Int32 | De blauwe componentwaarde voor de nieuwe [`Color`](../../color). Geldige waarden zijn 0 tot en met 255. |

### Retourwaarde

De [`Color`](../../color) die deze methode maakt.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentOutOfRangeException | Rood, groen of blauw is kleiner dan 0 of groter dan 255. |

### Opmerkingen

Hoewel deze methode een 32-bits waarde toestaat voor elke component, is de waarde van elke component beperkt tot 8 bits.

### Zie ook

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
