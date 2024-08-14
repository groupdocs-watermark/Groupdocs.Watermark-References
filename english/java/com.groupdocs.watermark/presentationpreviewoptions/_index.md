---
title: PresentationPreviewOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Provides options to sets requirements and stream delegates for preview generation of Presentation document.
type: docs
weight: 12
url: /java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Provides options to sets requirements and stream delegates for preview generation of Presentation document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initializes a new instance of the `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` class causing the output stream to be closed. |
| [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initializes a new instance of `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` class causing the output stream to be returned to the client for further use. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultResolution](#DefaultResolution) | Default resolution in dots per inch. |
## Methods

| Method | Description |
| --- | --- |
| [getResolution()](#getResolution--) | Gets the resolution for the generated images, in dots per inch. |
| [setResolution(long value)](#setResolution-long-) | Sets the resolution for the generated images, in dots per inch. |
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Initializes a new instance of the `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` class causing the output stream to be closed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initializes a new instance of `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` class causing the output stream to be returned to the client for further use.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |
| releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifies that the page preview generation is done and gets the output stream. |

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Default resolution in dots per inch.

### getResolution() {#getResolution--}
```
public final long getResolution()
```


Gets the resolution for the generated images, in dots per inch.

**Returns:**
long - The resolution for the generated images, in dots per inch.
### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Sets the resolution for the generated images, in dots per inch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The resolution for the generated images, in dots per inch. |

