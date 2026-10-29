---
title: "PdfShapeFormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine Sammlung formatierter Textfragmente in einem PDF-Dokument XObject Artifact oder Anmerkung dar."
type: docs
weight: 780
url: /de/net/groupdocs.watermark.contents.pdf/pdfshapeformattedtextfragmentcollection/
---
## PdfShapeFormattedTextFragmentCollection class

Stellt eine Sammlung von formatierten Textfragmenten in einem pdf-Dokument‑XObject, Artefakt oder Anmerkung dar.

```csharp
public class PdfShapeFormattedTextFragmentCollection : PdfFormattedTextFragmentCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CollectionType](../../groupdocs.watermark.search/formattedtextfragmentcollection/collectiontype) { get; } | Ermittelt den Typ der Sammlung formatierter Fragmente. |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Liefert die Anzahl der in der Sammlung enthaltenen Elemente. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Liefert das Element am angegebenen Index in der Sammlung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color, Color) | Fügt der Sammlung ein formatiertes Textfragment hinzu. |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(FormattedTextFragment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(FormattedTextFragment) |  |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color, Color) | Fügt an einem angegebenen Index ein formatiertes Textfragment in die Sammlung ein. |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(FormattedTextFragment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Hinweise

Diese Sammlung enthält Elemente des Typs [`PdfFormattedTextFragment`](../pdfformattedtextfragment).

### Siehe auch

* class [PdfFormattedTextFragmentCollection](../pdfformattedtextfragmentcollection)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
