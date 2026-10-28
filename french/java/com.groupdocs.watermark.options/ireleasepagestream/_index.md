---
title: "IReleasePageStream"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une méthode qui libère le flux créé par l'objet."
type: docs
weight: 81
url: /fr/java/com.groupdocs.watermark.options/ireleasepagestream/
---```
public interface IReleasePageStream
```

Represents a method which releases the stream created by `[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream)` object.

## Methods

| Method | Description |
| --- | --- |
| [releasePageStream(int pageNumber, OutputStream pageStream)](#releasePageStream-int-java.io.OutputStream-) | Releases the stream created by `[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream)` object.
 |
### releasePageStream(int pageNumber, OutputStream pageStream) {#releasePageStream-int-java.io.OutputStream-}
```
public abstract void releasePageStream(int pageNumber, OutputStream pageStream)
```


Releases the stream created by `[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream)` object.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number of a generated page preview.
 |
| pageStream | java.io.OutputStream | The stream containing the generated page preview.
 |

