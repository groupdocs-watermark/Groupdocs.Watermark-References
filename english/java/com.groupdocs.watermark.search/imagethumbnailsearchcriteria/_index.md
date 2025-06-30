---
title: ImageThumbnailSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents search criteria for finding images in a content.
type: docs
weight: 33
url: /java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Represents search criteria for finding images in a content.

--------------------

This search criteria uses image binarized thumbnail for calculating image similarity.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Initializes a new instance of the `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` class with a specified file path. |
| [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Initializes a new instance of the `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` class with a specified stream. |
## Methods

| Method | Description |
| --- | --- |
| [getThumbnailSize()](#getThumbnailSize--) | Gets thumbnail size. |
| [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Sets thumbnail size. |
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Initializes a new instance of the `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` class with a specified file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load image from. |

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Initializes a new instance of the `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` class with a specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from. |

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Gets thumbnail size.

**Returns:**
byte - By default 32X32 thumbnail will be used.
### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Sets thumbnail size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | By default 32X32 thumbnail will be used. |

