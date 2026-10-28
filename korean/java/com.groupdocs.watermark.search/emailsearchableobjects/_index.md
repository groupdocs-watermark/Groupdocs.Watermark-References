---
title: "EmailSearchableObjects"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크 검색에 포함될 이메일 메시지 개체를 나타내는 플래그를 지정합니다."
type: docs
weight: 22
url: /ko/java/com.groupdocs.watermark.search/emailsearchableobjects/
---
**Inheritance:**
java.lang.Object
```
public final class EmailSearchableObjects
```

워터마크 검색에 포함될 이메일 메시지 개체를 나타내는 플래그를 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [None](#None) | 검색 객체가 없음을 지정합니다. |
|
|  | [Subject](#Subject) | 메시지 제목에서 검색합니다. |
|
|  | [PlainTextBody](#PlainTextBody) | 메시지 일반 텍스트 본문에서 검색합니다. |
|
|  | [HtmlBody](#HtmlBody) | 메시지 HTML 본문에서 검색합니다. |
|
|  | [AttachedImages](#AttachedImages) | 첨부된 이미지에서 검색합니다. |
|
|  | [EmbeddedImages](#EmbeddedImages) | 내장된 이미지에서 검색합니다. |
|
|  | [All](#All) | 모든 이메일 객체에서 검색합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getValues()](#getValues--) | `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)` 열거형의 모든 값 배열을 가져옵니다. |
|
### None {#None}
```
public static final int None
```


검색 객체가 없음을 지정합니다.


### Subject {#Subject}
```
public static final int Subject
```


메시지 제목에서 검색합니다.


### PlainTextBody {#PlainTextBody}
```
public static final int PlainTextBody
```


메시지 일반 텍스트 본문에서 검색합니다.


### HtmlBody {#HtmlBody}
```
public static final int HtmlBody
```


메시지 HTML 본문에서 검색합니다.


### AttachedImages {#AttachedImages}
```
public static final int AttachedImages
```


첨부된 이미지에서 검색합니다.


### EmbeddedImages {#EmbeddedImages}
```
public static final int EmbeddedImages
```


내장된 이미지에서 검색합니다.


### All {#All}
```
public static final int All
```


모든 이메일 객체에서 검색합니다.


### getValues() {#getValues--}
```
public static final int[] getValues()
```


`[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)` 열거형의 모든 값 배열을 가져옵니다.


**Returns:**
int[] - `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)` 열거형의 모든 값 배열.

