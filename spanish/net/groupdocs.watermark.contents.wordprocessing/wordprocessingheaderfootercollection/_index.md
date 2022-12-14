---
title: WordProcessingHeaderFooterCollection
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Representa una colección de encabezados y pies de página en un documento de Word.
type: docs
weight: 1310
url: /es/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/
---
## WordProcessingHeaderFooterCollection class

Representa una colección de encabezados y pies de página en un documento de Word.

```csharp
public class WordProcessingHeaderFooterCollection : ReadOnlyListBase<WordProcessingHeaderFooter>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Obtiene el número de elementos que contiene la colección. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | Obtiene un valor que indica si la colección es de solo lectura. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Obtiene el elemento en el índice especificado en la colección. |
| [Item](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/item) { get; } | Obtiene el encabezado o pie de página del tipo especificado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(WordProcessingHeaderFooter) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(WordProcessingHeaderFooter) |  |
| [LinkToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/linktoprevious)(bool) | Vincula o desvincula todos los encabezados y pies de página a los correspondientes encabezados y pies de página en la sección anterior. |

### Observaciones

Esta colección contiene los elementos de[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter) tipo.

### Ver también

* class [ReadOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/readonlylistbase-1)
* class [WordProcessingHeaderFooter](../wordprocessingheaderfooter)
* espacio de nombres [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* asamblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
