---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Specifica i flag che rappresentano gli oggetti di contenuto PDF da includere in una ricerca di filigrana."
type: docs
weight: 2530
url: /it/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

Specifica i flag che rappresentano gli oggetti di contenuto PDF da includere in una ricerca di filigrana.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Specifica nessun oggetto di ricerca. |
| XObjects | `1` | Cerca in XObjects. |
| Artifacts | `2` | Cerca negli artefatti. |
| Annotations | `4` | Cerca nelle annotazioni. |
| Text | `8` | Cerca nel testo del contenuto. |
| Hyperlinks | `10` | Cerca nei collegamenti ipertestuali. |
| AttachedImages | `20` | Cerca nelle immagini allegate. |
| Vector | `40` | Cerca negli operatori. |
| All | `7F` | Cerca in tutti gli oggetti di contenuto. |

### Vedi anche

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
