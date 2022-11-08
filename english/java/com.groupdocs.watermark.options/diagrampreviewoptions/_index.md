---
title: DiagramPreviewOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Provides options to sets requirements and stream delegates for preview generation of Diagram document.
type: docs
weight: 12
url: /java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Provides options to sets requirements and stream delegates for preview generation of Diagram document.
## Constructors

| Constructor | Description |
| --- | --- |
| [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initializes a new instance of the `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` class causing the output stream to be closed. |
| [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initializes a new instance of `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` class causing the output stream to be returned to the client for further use. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultResolution](#DefaultResolution) | Default resolution in dots per inch. |
## Methods

| Method | Description |
| --- | --- |
| [getResolution()](#getResolution--) | Gets or sets the resolution for the generated images, in dots per inch. |
| [setResolution(float value)](#setResolution-float-) | Gets or sets the resolution for the generated images, in dots per inch. |
| [getHighQualityRendering()](#getHighQualityRendering--) | Gets or sets the flag for high quality rendering. |
| [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Gets or sets the flag for high quality rendering. |
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Initializes a new instance of the `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` class causing the output stream to be closed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initializes a new instance of `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` class causing the output stream to be returned to the client for further use.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |
| releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifies that the page preview generation is done and gets the output stream. |

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Default resolution in dots per inch.

### getResolution() {#getResolution--}
```
public final float getResolution()
```


Gets or sets the resolution for the generated images, in dots per inch.

--------------------

The default value is 300.

**Returns:**
float
### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Gets or sets the resolution for the generated images, in dots per inch.

--------------------

The default value is 300.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Gets or sets the flag for high quality rendering.

--------------------

The high quality rendering uses more resources. The default value is  false .

**Returns:**
boolean
### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Gets or sets the flag for high quality rendering.

--------------------

The high quality rendering uses more resources. The default value is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

