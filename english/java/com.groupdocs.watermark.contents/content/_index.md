---
title: Content
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a content where a watermark can be placed.
type: docs
weight: 12
url: /java/com.groupdocs.watermark.contents/content/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Content extends ContentPart implements Closeable
```

Represents a content where a watermark can be placed.

## Constructors

| Constructor | Description |
| --- | --- |
| [Content(StreamContainer stream, IStrategyManager strategyManager, LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#Content-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br />

 |
## Methods

| Method | Description |
| --- | --- |
| [getWatermarkerSettings()](#getWatermarkerSettings--) | <br />

 |
| [getDocumentInfo()](#getDocumentInfo--) | <br />

 |
| [getFileType()](#getFileType--) | <br />

 |
| [getSearchableObjects()](#getSearchableObjects--) | <br />

 |
| [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | <br />

 |
| [getStream()](#getStream--) | <br />

 |
| [save(String filePath)](#save-java.lang.String-) | <br />

 |
| [save(String filePath, SaveOptions saveOptions)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br />

 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | <br />

 |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | <br />

 |
| [dispose()](#dispose--) | <br />

 |
| [performSave(String filePath)](#performSave-java.lang.String-) | <br />

 |
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | <br />

 |
| [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br />

 |
| [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | <br />

 |
| [registerDisposableResource(System.IDisposable resource)](#registerDisposableResource-com.aspose.ms.System.IDisposable-) | <br />

 |
| [getInfo(String filePath)](#getInfo-java.lang.String-) | <br />

 |
| [getInfo(System.IO.Stream stream)](#getInfo-com.aspose.ms.System.IO.Stream-) | <br />

 |
| [close()](#close--) | Disposes the current instance.
 |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br />

 |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br />

 |
### Content(StreamContainer stream, IStrategyManager strategyManager, LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#Content-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.IStrategyManager-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Content(StreamContainer stream, IStrategyManager strategyManager, LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | [IStrategyManager](../../com.groupdocs.watermark.internal/istrategymanager) |  |
| loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getWatermarkerSettings() {#getWatermarkerSettings--}
```
public final WatermarkerSettings getWatermarkerSettings()
```


<br />



**Returns:**
[WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings)
### getDocumentInfo() {#getDocumentInfo--}
```
public abstract IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


<br />



**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


<br />



**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects)
### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) |  |

### getStream() {#getStream--}
```
public final StreamContainer getStream()
```


<br />



**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

### save(String filePath, SaveOptions saveOptions) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### dispose() {#dispose--}
```
public final void dispose()
```


<br />



### performSave(String filePath) {#performSave-java.lang.String-}
```
public abstract void performSave(String filePath)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public abstract void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public abstract void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public abstract void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### registerDisposableResource(System.IDisposable resource) {#registerDisposableResource-com.aspose.ms.System.IDisposable-}
```
public final void registerDisposableResource(System.IDisposable resource)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | com.aspose.ms.System.IDisposable |  |

### getInfo(String filePath) {#getInfo-java.lang.String-}
```
public static InfoInternal getInfo(String filePath)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

**Returns:**
[InfoInternal](../../com.groupdocs.watermark.internal/infointernal)
### getInfo(System.IO.Stream stream) {#getInfo-com.aspose.ms.System.IO.Stream-}
```
public static InfoInternal getInfo(System.IO.Stream stream)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[InfoInternal](../../com.groupdocs.watermark.internal/infointernal)
### close() {#close--}
```
public final void close()
```


Disposes the current instance.


### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public abstract void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public abstract void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

