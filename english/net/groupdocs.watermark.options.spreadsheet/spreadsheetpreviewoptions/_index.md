---
title: SpreadsheetPreviewOptions
second_title: GroupDocs.Watermark for .NET API Reference
description: Provides options to sets requirements and stream delegates for preview generation of Spreadsheet document.
type: docs
weight: 2150
url: /net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions class

Provides options to sets requirements and stream delegates for preview generation of Spreadsheet document.

```csharp
public class SpreadsheetPreviewOptions : PreviewOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor)(CreatePageStream) | Initializes a new instance of the [`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions) class causing the output stream to be closed. |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initializes a new instance of [`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions) class causing the output stream to be returned to the client for further use. |

## Properties

| Name | Description |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Gets or sets an instance of the page stream creation delegate. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Gets or sets the page preview height. |
| [OnlyDataArea](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/onlydataarea) { get; set; } | Gets or sets the flag for rendering the data area only without headers, footers, margins. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Gets or sets an array of page numbers to generate previews. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Gets or sets the preview image format. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Gets or sets an instance of the page preview completion delegate. |
| [Resolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/resolution) { get; set; } | Gets or sets the resolution for the generated images, in dots per inch. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Gets or sets the page preview width. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/defaultresolution) | Default resolution in dots per inch. |

### See Also

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->