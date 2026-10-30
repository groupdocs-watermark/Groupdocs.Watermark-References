---
title: "FromArgb"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Crea una struttura Colorgroupdocs.watermark.watermarks/color da un valore ARGB a 32 bit."
type: docs
weight: 1430
url: /it/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Crea una struttura [`Color`](../../color) da un valore ARGB a 32 bit.

```csharp
public static Color FromArgb(int argb)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| argb | Int32 | Un valore che specifica il valore ARGB a 32 bit. |

### Valore di ritorno

La struttura [`Color`](../../color) che questo metodo crea.

### Vedi anche

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Crea una struttura [`Color`](../../color) dalla struttura [`Color`](../../color) specificata, ma con il nuovo valore alpha specificato.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| alpha | Int32 | Il valore alpha per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |
| baseColor | Color | Il [`Color`](../../color) da cui creare il nuovo [`Color`](../../color). |

### Valore di ritorno

Il [`Color`](../../color) che questo metodo crea.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | Alpha è inferiore a 0 o superiore a 255. |

### Osservazioni

Sebbene questo metodo consenta di passare un valore a 32 bit per il valore alpha, il valore è limitato a 8 bit.

### Vedi anche

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Crea una struttura [`Color`](../../color) dai valori di colore a 8 bit specificati (rosso, verde e blu) e il valore alpha è implicitamente 255 (completamente opaco).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| red | Int32 | Il valore del componente rosso per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |
| green | Int32 | Il valore del componente verde per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |
| blue | Int32 | Il valore del componente blu per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |

### Valore di ritorno

Il [`Color`](../../color) che questo metodo crea.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | Il rosso, il verde o il blu è minore di 0 o maggiore di 255. |

### Osservazioni

Sebbene questo metodo consenta di passare un valore a 32 bit per ogni componente di colore, il valore di ciascun componente è limitato a 8 bit.

### Vedi anche

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Crea una struttura [`Color`](../../color) dai quattro valori dei componenti ARGB (alpha, rosso, verde e blu).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| alpha | Int32 | Il valore del componente alfa per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |
| red | Int32 | Il valore del componente rosso per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |
| green | Int32 | Il valore del componente verde per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |
| blue | Int32 | Il valore del componente blu per il nuovo [`Color`](../../color). I valori validi sono da 0 a 255. |

### Valore di ritorno

Il [`Color`](../../color) che questo metodo crea.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | Il rosso, il verde o il blu è minore di 0 o maggiore di 255. |

### Osservazioni

Sebbene questo metodo consenta di passare un valore a 32 bit per ogni componente, il valore di ciascun componente è limitato a 8 bit.

### Vedi anche

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
