---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine Sammlung von Kopf- und Fußzeilen in einem Word-Dokument dar."
type: docs
weight: 1370
url: /de/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/
---
## WordProcessingHeaderFooterCollection class

Stellt eine Sammlung von Kopf- und Fußzeilen in einem Word-Dokument dar.

```csharp
public class WordProcessingHeaderFooterCollection : ReadOnlyListBase<WordProcessingHeaderFooter>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Liefert die Anzahl der in der Sammlung enthaltenen Elemente. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Liefert das Element am angegebenen Index in der Sammlung. |
| [Item](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/item) { get; } | Ruft die Kopf- oder Fußzeile des angegebenen Typs ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(WordProcessingHeaderFooter) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(WordProcessingHeaderFooter) |  |
| [LinkToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/linktoprevious)(bool) | Verknüpft oder löst die Verknüpfung aller Kopf- und Fußzeilen mit den entsprechenden Kopf- und Fußzeilen im vorherigen Abschnitt. |

### Hinweise

Diese Sammlung enthält Elemente des Typs [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter).

### Siehe auch

* class [ReadOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/readonlylistbase-1)
* class [WordProcessingHeaderFooter](../wordprocessingheaderfooter)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
