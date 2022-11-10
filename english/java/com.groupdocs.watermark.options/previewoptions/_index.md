---
title: PreviewOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Provides options to sets requirements and stream delegates for preview generation.
type: docs
weight: 47
url: /java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Provides options to sets requirements and stream delegates for preview generation.
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initializes a new instance of the `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` class causing the output stream to be closed. |
| [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initializes a new instance of `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` class causing the output stream to be returned to the client for further use. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets the page preview width. |
| [setWidth(int value)](#setWidth-int-) | Sets the page preview width. |
| [getHeight()](#getHeight--) | Gets the page preview height. |
| [setHeight(int value)](#setHeight-int-) | Sets the page preview height. |
| [getPageNumbers()](#getPageNumbers--) | Gets an array of page numbers to generate previews. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Sets an array of page numbers to generate previews. |
| [getPreviewFormat()](#getPreviewFormat--) | Gets the preview image format. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Sets the preview image format. |
| [getCreatePageStream()](#getCreatePageStream--) | Gets an instance of the page stream creation class. |
| [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Sets an instance of the page stream creation class. |
| [getReleasePageStream()](#getReleasePageStream--) | Gets an instance of the page preview completion class. |
| [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Sets an instance of the page preview completion class. |
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Initializes a new instance of the `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` class causing the output stream to be closed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initializes a new instance of `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` class causing the output stream to be returned to the client for further use.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Creates a stream for a specific page preview. |
| releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifies that the page preview generation is done and gets the output stream. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the page preview width.

**Returns:**
int - The page preview width.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the page preview width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The page preview width. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the page preview height.

**Returns:**
int - The page preview height.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the page preview height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The page preview height. |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Gets an array of page numbers to generate previews.

**Returns:**
int[] - The array of page numbers to generate previews.
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Sets an array of page numbers to generate previews.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The array of page numbers to generate previews. |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Gets the preview image format.

**Returns:**
int - The preview image format.
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Sets the preview image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The preview image format. |

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Gets an instance of the page stream creation class.

**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.
### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Sets an instance of the page stream creation class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | The instance of the page stream creation class. |

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Gets an instance of the page preview completion class.

**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.
### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Sets an instance of the page preview completion class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | The instance of the page preview completion delegate. |

