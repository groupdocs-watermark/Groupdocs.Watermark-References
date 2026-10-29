---
title: "SizingType"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Gibt an, wie die Größe des Wasserzeichens berechnet werden soll."
type: docs
weight: 3300
url: /de/net/groupdocs.watermark.watermarks/sizingtype/
---
## SizingType enumeration

Gibt an, wie die Größe des Wasserzeichens berechnet werden soll.

```csharp
public enum SizingType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Das Wasserzeichen sollte automatisch entsprechend seinem Inhalt dimensioniert werden. |
| Absolute | `1` | Das Wasserzeichen sollte auf eine exakte [`Width`](../../groupdocs.watermark/watermark/width) und [`Height`](../../groupdocs.watermark/watermark/height) dimensioniert werden. |
| ScaleToParentDimensions | `2` | Das Wasserzeichen sollte relativ zu den übergeordneten Abmessungen mit dem angegebenen [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) skaliert werden. |
| ScaleToParentArea | `3` | Das Wasserzeichen sollte relativ zur übergeordneten Fläche mit dem angegebenen [`ScaleFactor`](../../groupdocs.watermark/watermark/scalefactor) skaliert werden. |

### Siehe auch

* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
