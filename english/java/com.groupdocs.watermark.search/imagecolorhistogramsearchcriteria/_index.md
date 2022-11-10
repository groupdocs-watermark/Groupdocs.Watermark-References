---
title: ImageColorHistogramSearchCriteria
second_title: GroupDocs.Watermark for Java API Reference
description: Represents search criteria for finding images in a content.
type: docs
weight: 30
url: /java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Represents search criteria for finding images in a content.

--------------------

This search criteria uses image color histograms for calculating image similarity.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Initializes a new instance of the `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` class with a specified file path. |
| [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Initializes a new instance of the `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` class with a specified stream. |
## Methods

| Method | Description |
| --- | --- |
| [getBinsCount()](#getBinsCount--) | Gets a count of bins that will be used for building color histograms. |
| [setBinsCount(byte value)](#setBinsCount-byte-) | Sets a count of bins that will be used for building color histograms. |
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Initializes a new instance of the `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` class with a specified file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load image from. |

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Initializes a new instance of the `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` class with a specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from. |

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Gets a count of bins that will be used for building color histograms.

**Returns:**
byte - The default value is 10.
### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Sets a count of bins that will be used for building color histograms.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The default value is 10. |

