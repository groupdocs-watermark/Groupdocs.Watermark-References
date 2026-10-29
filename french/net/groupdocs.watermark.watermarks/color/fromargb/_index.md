---
title: "FromArgb"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Crée une structure Colorgroupdocs.watermark.watermarks/color à partir d'une valeur ARGB 32 bits."
type: docs
weight: 1430
url: /fr/net/groupdocs.watermark.watermarks/color/fromargb/
---
## FromArgb(int) {#fromargb}

Crée une structure [`Color`](../../color) à partir d'une valeur ARGB 32 bits.

```csharp
public static Color FromArgb(int argb)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| argb | Int32 | Une valeur spécifiant la valeur ARGB 32 bits. |

### Valeur de retour

La structure [`Color`](../../color) que cette méthode crée.

### Voir aussi

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Crée une structure [`Color`](../../color) à partir de la structure [`Color`](../../color) spécifiée, mais avec la nouvelle valeur alpha spécifiée.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | Int32 | La valeur alpha pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |
| baseColor | Color | Le [`Color`](../../color) à partir duquel créer le nouveau [`Color`](../../color). |

### Valeur de retour

Le [`Color`](../../color) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Alpha est inférieur à 0 ou supérieur à 255. |

### Remarques

Bien que cette méthode permette de passer une valeur 32 bits pour la valeur alpha, la valeur est limitée à 8 bits.

### Voir aussi

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Crée une structure [`Color`](../../color) à partir des valeurs de couleur 8 bits spécifiées (rouge, vert et bleu) et la valeur alpha est implicitement 255 (pleinement opaque).

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| red | Int32 | La valeur du composant rouge pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |
| green | Int32 | La valeur du composant vert pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |
| blue | Int32 | La valeur du composant bleu pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |

### Valeur de retour

Le [`Color`](../../color) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Le rouge, le vert ou le bleu est inférieur à 0 ou supérieur à 255. |

### Remarques

Bien que cette méthode permette de passer une valeur 32 bits pour chaque composant de couleur, la valeur de chaque composant est limitée à 8 bits.

### Voir aussi

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Crée une structure [`Color`](../../color) à partir des quatre valeurs de composant ARGB (alpha, rouge, vert et bleu).

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | Int32 | La valeur du composant alpha pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |
| red | Int32 | La valeur du composant rouge pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |
| green | Int32 | La valeur du composant vert pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |
| blue | Int32 | La valeur du composant bleu pour le nouveau [`Color`](../../color). Les valeurs valides sont de 0 à 255. |

### Valeur de retour

Le [`Color`](../../color) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Le rouge, le vert ou le bleu est inférieur à 0 ou supérieur à 255. |

### Remarques

Bien que cette méthode permette de passer une valeur 32 bits pour chaque composant, la valeur de chaque composant est limitée à 8 bits.

### Voir aussi

* struct [Color](../../color)
* namespace [GroupDocs.Watermark.Watermarks](../../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
