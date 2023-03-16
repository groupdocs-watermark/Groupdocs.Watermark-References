---
title: FromExtension
second_title: GroupDocs.Watermark for .NET API-referens
description: Mappar filtillägget till filtypen.
type: docs
weight: 590
url: /sv/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Mappar filtillägget till filtypen.

```csharp
public static FileType FromExtension(string extension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extension | String | Filtillägget (inklusive perioden "."). |

### Returvärde

När filtypen stöds returneras den, annars returneras standard[`Unknown`](../unknown) filtyp.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*extension* är null eller tom sträng. |

### Se även

* class [FileType](../../filetype)
* namnutrymme [GroupDocs.Watermark.Common](../../filetype)
* hopsättning [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->