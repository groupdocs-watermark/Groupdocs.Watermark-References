---
title: "ICreatePageStream"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "페이지 미리보기 데이터를 쓰기 위한 스트림을 반환하는 메서드를 제공합니다."
type: docs
weight: 78
url: /ko/java/com.groupdocs.watermark.options/icreatepagestream/
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

