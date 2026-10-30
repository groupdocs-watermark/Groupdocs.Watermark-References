---
title: "FromArgb"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Skapar en Colorgroupdocs.watermark.watermarks/color-struktur från ett 32‑bit ARGB‑värde."
type: docs
weight: 1430
url: /sv/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Skapar en [`Color`](../../color)-struktur från ett 32‑bit ARGB‑värde.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | Int32 | Ett värde som specificerar 32‑bit ARGB‑värdet. |

### Returvärde

Den [`Color`](../../color)-strukturen som den här metoden skapar.

### Se även

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Skapar en [`Color`](../../color)-struktur från den angivna [`Color`](../../color)-strukturen, men med det nya angivna alfavärdet.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | Int32 | Alfavärdet för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |
| baseColor | Color | Den [`Color`](../../color) som den nya [`Color`](../../color) ska skapas från. |

### Returvärde

Den [`Color`](../../color) som den här metoden skapar.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Alfa är mindre än 0 eller större än 255. |

### Anmärkningar

Även om den här metoden tillåter att ett 32-bitars värde skickas för alfavärdet, är värdet begränsat till 8 bitar.

### Se även

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Skapar en [`Color`](../../color)-struktur från de angivna 8-bitars färgvärdena (röd, grön och blå) och alfavärdet är implicit 255 (fullt ogenomskinligt).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| red | Int32 | Det röda komponentvärdet för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |
| green | Int32 | Det gröna komponentvärdet för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |
| blue | Int32 | Det blåa komponentvärdet för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |

### Returvärde

Den [`Color`](../../color) som den här metoden skapar.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Röd, grön eller blå är mindre än 0 eller större än 255. |

### Anmärkningar

Även om den här metoden tillåter att ett 32-bitars värde skickas för varje färgkomponent, är varje komponents värde begränsat till 8 bitar.

### Se även

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Skapar en [`Color`](../../color)-struktur från de fyra ARGB-komponentvärdena (alfa, röd, grön och blå).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | Int32 | Alfakomponentens värde för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |
| red | Int32 | Det röda komponentvärdet för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |
| green | Int32 | Det gröna komponentvärdet för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |
| blue | Int32 | Det blåa komponentvärdet för den nya [`Color`](../../color). Giltiga värden är 0 till 255. |

### Returvärde

Den [`Color`](../../color) som den här metoden skapar.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Röd, grön eller blå är mindre än 0 eller större än 255. |

### Anmärkningar

Även om den här metoden tillåter att ett 32-bitars värde skickas för varje komponent, är varje komponents värde begränsat till 8 bitar.

### Se även

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
