---
title: PdfShapeFormattedTextFragmentCollection
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Representa una colección de fragmentos de texto con formato en un documento pdf XObject Artifact o Annotation.
type: docs
weight: 710
url: /es/net/groupdocs.watermark.contents.pdf/pdfshapeformattedtextfragmentcollection/
---
## PdfShapeFormattedTextFragmentCollection class

Representa una colección de fragmentos de texto con formato en un documento pdf XObject, Artifact o Annotation.

```csharp
public class PdfShapeFormattedTextFragmentCollection : PdfFormattedTextFragmentCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CollectionType](../../groupdocs.watermark.search/formattedtextfragmentcollection/collectiontype) { get; } | Obtiene el tipo de colección de fragmentos formateados. |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Obtiene el número de elementos que contiene la colección. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Obtiene un valor que indica si la colección es de solo lectura. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Obtiene el elemento en el índice especificado en la colección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string) | Agrega un fragmento de texto formateado a la colección. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font) | Agrega un fragmento de texto formateado a la colección. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color) | Agrega un fragmento de texto formateado a la colección. |
| [Add](../../groupdocs.watermark.search/formattedtextfragmentcollection/add)(string, Font, Color, Color) | Agrega un fragmento de texto formateado a la colección. |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(FormattedTextFragment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(FormattedTextFragment) |  |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
| [Insert](../../groupdocs.watermark.search/formattedtextfragmentcollection/insert)(int, string, Font, Color, Color) | Inserta un fragmento de texto formateado en la colección en un índice dado. |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(FormattedTextFragment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Observaciones

Esta colección contiene los elementos de[`PdfFormattedTextFragment`](../pdfformattedtextfragment) tipo.

### Ver también

* class [PdfFormattedTextFragmentCollection](../pdfformattedtextfragmentcollection)
* espacio de nombres [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* asamblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
