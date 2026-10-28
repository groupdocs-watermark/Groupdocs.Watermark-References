---
title: "MultiframeImageContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 멀티프레임 이미지를 나타냅니다."
type: docs
weight: 42
url: /ko/java/com.groupdocs.watermark.contents/multiframeimagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content), [com.groupdocs.watermark.contents.ImageContent](../../com.groupdocs.watermark.contents/imagecontent)
```
public abstract class MultiframeImageContent extends ImageContent
```

워터마크를 배치할 수 있는 멀티프레임 이미지를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFrames()](#getFrames--) | 이미지의 모든 프레임 컬렉션을 가져옵니다. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
### getFrames() {#getFrames--}
```
public final ImageFrameCollection getFrames()
```


이미지의 모든 프레임 컬렉션을 가져옵니다.


**Returns:**
[ImageFrameCollection](../../com.groupdocs.watermark.contents/imageframecollection) - The collection of image frames.

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
