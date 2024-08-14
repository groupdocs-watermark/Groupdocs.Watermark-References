---
title: PdfPreviewOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Provides options to sets requirements and stream delegates for preview generation of PDF document.
type: docs
weight: 31
url: /java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Provides options to sets requirements and stream delegates for preview generation of PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initializes a new instance of the `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` class causing the output stream to be closed. |
| [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initializes a new instance of `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` class causing the output stream to be returned to the client for further use. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultResolution](#DefaultResolution) | Default resolution in dots per inch. |
## Methods

| Method | Description |
| --- | --- |
| [getResolution()](#getResolution--) | Gets the resolution for the generated images, in dots per inch. |
| [setResolution(int value)](#setResolution-int-) | Sets the resolution for the generated images, in dots per inch. |
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Initializes a new instance of the `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` class causing the output stream to be closed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initializes a new instance of `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` class causing the output stream to be returned to the client for further use.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |
| releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifies that the page preview generation is done and gets the output stream. |

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Default resolution in dots per inch.

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Gets the resolution for the generated images, in dots per inch.

**Returns:**
int - The resolution for the generated images, in dots per inch.

--------------------

The default value is 150.
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Sets the resolution for the generated images, in dots per inch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The resolution for the generated images, in dots per inch.

--------------------

The default value is 150. |

