---
title: "ICreatePageStream"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Methode bereit, die einen Stream zurückgibt, um Seitenvorschau-Daten zu schreiben."
type: docs
weight: 78
url: /de/java/com.groupdocs.watermark.options/icreatepagestream/
---```
public interface ICreatePageStream
```

Provides method that returns a stream to write page preview data.

## Methods

| Method | Description |
| --- | --- |
| [createPageStream(int pageNumber)](#createPageStream-int-) | Returns a stream to write page preview data.
 |
### createPageStream(int pageNumber) {#createPageStream-int-}
```
public abstract OutputStream createPageStream(int pageNumber)
```


Returns a stream to write page preview data.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number of a page to generate a thumbnail.
 |

**Returns:**
java.io.OutputStream - The stream to write the page preview.

