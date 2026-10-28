---
title: "WordProcessingHeaderFooterCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서의 머리글 및 바닥글 컬렉션을 나타냅니다."
type: docs
weight: 132
url: /ko/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Word 문서의 머리글 및 바닥글 컬렉션을 나타냅니다.

이 컬렉션은 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` 유형의 항목을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | 지정된 유형의 머리글 또는 바닥글을 가져옵니다. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | 모든 머리글 및 바닥글을 해당 |
이전 섹션의 머리글 및 바닥글에 연결하거나 연결을 해제합니다.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


지정된 유형의 머리글 또는 바닥글을 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | headerFooterType | int | `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` 값으로, 가져올 머리글/바닥글의 유형을 지정합니다. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


모든 머리글 및 바닥글을 해당
이전 섹션의 머리글 및 바닥글에 연결하거나 연결을 해제합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | 머리글 및 바닥글을 이전 섹션에 연결하려면 true, 연결을 해제하려면 false. |
|

