---
title: EmailPreviewOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Provides options to sets requirements and stream delegates for preview generation of Email document.
type: docs
weight: 17
url: /java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

Provides options to sets requirements and stream delegates for preview generation of Email document.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initializes a new instance of the `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` class causing the output stream to be closed. |
| [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initializes a new instance of `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` class causing the output stream to be returned to the client for further use. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultResolution](#DefaultResolution) | Default resolution in dots per inch. |
## Methods

| Method | Description |
| --- | --- |
| [getResolution()](#getResolution--) | Gets the resolution for the generated images, in dots per inch. |
| [setResolution(float value)](#setResolution-float-) | Sets the resolution for the generated images, in dots per inch. |
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


Initializes a new instance of the `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` class causing the output stream to be closed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initializes a new instance of `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` class causing the output stream to be returned to the client for further use.

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


Gets the resolution for the generated images, in dots per inch.

**Returns:**
float - The resolution for the generated images, in dots per inch.

--------------------

The default value is 96.
### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Sets the resolution for the generated images, in dots per inch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The resolution for the generated images, in dots per inch.

--------------------

The default value is 96. |

