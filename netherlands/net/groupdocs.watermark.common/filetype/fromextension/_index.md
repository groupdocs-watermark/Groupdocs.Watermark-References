---
title: "FromExtension"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Mapt de bestandsextensie naar het bestandstype."
type: docs
weight: 590
url: /nl/net/groupdocs.watermark.common/filetype/fromextension/
---
## FileType.FromExtension method

Mapt de bestandsextensie naar het bestandstype.

```csharp
public static FileType FromExtension(string extension)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extensie | String | De bestandsextensie (inclusief de punt \".\"). |

### Retourwaarde

Wanneer het bestandstype wordt ondersteund, wordt het geretourneerd, anders wordt het standaard [`Unknown`](../unknown)-bestandstype geretourneerd.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer *extension* null of een lege string is. |

### Zie ook

* class [FileType](../../filetype)
* namespace [GroupDocs.Watermark.Common](../../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
