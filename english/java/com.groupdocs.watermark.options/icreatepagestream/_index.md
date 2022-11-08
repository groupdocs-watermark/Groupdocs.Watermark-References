---
title: ICreatePageStream
second_title: GroupDocs.Watermark for Java API Reference
description: Provides method that returns a stream to write page preview data.
type: docs
weight: 78
url: /java/com.groupdocs.watermark.options/icreatepagestream/
---```
public interface ICreatePageStream
```

Provides method that returns a stream to write page preview data.
## Methods

| Method | Description |
| --- | --- |
| [createPageStream(int pageNumber)](#createPageStream-int-) | Returns a stream to write page preview data. |
### createPageStream(int pageNumber) {#createPageStream-int-}
```
public abstract OutputStream createPageStream(int pageNumber)
```


Returns a stream to write page preview data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number of a page to generate a thumbnail. |

**Returns:**
java.io.OutputStream - The stream to write the page preview.
