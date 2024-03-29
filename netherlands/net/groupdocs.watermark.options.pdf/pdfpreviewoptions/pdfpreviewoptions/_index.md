---
title: PdfPreviewOptions
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Initialiseert een nieuw exemplaar van hetPdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions klasse waardoor de uitvoerstroom wordt gesloten.
type: docs
weight: 10
url: /nl/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Initialiseert een nieuw exemplaar van het[`PdfPreviewOptions`](../../pdfpreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Creëert een stream voor een specifiek paginavoorbeeld. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* naamruimte [GroupDocs.Watermark.Options.Pdf](../../pdfpreviewoptions)
* montage [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialiseert een nieuw exemplaar van[`PdfPreviewOptions`](../../pdfpreviewoptions) class waardoor de uitvoerstroom wordt teruggestuurd naar de client voor verder gebruik.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Creëert een stream voor een specifiek paginavoorbeeld. |
| releasePageStream | ReleasePageStream | Geeft aan dat het genereren van het paginavoorbeeld is voltooid en ontvangt de uitvoerstroom. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* naamruimte [GroupDocs.Watermark.Options.Pdf](../../pdfpreviewoptions)
* montage [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
