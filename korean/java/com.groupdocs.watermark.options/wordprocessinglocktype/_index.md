---
title: "WordProcessingLockType"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서에서 워터마크 잠금 유형을 지정합니다."
type: docs
weight: 68
url: /ko/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Word 문서에서 워터마크 잠금 유형을 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | 사용자는 문서에 수정 표시만 추가할 수 있습니다. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | 사용자는 문서의 주석만 수정할 수 있습니다. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | 사용자는 문서의 양식 필드에만 데이터를 입력할 수 있습니다. |
|
|  | [ReadOnly](#ReadOnly) | 전체 문서는 읽기 전용입니다. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | 문서는 읽기 전용이지만 워터마크를 제외한 모든 내용은 편집 가능하도록 표시됩니다. |
|
|  | [NoLock](#NoLock) | 워터마크와 문서에 대한 모든 잠금을 해제합니다. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


사용자는 문서에 수정 표시만 추가할 수 있습니다.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


사용자는 문서의 주석만 수정할 수 있습니다.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


사용자는 문서의 양식 필드에만 데이터를 입력할 수 있습니다.

<br />

*** ** * ** ***

문서는 한 페이지 섹션으로 분할되고, 인접한 두 콘텐츠 섹션 사이에 워터마크가 포함된 잠긴 섹션이 추가됩니다.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


전체 문서는 읽기 전용입니다.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


문서는 읽기 전용이지만 워터마크를 제외한 모든 내용은 편집 가능하도록 표시됩니다.


### NoLock {#NoLock}
```
public static final int NoLock
```


워터마크와 문서에 대한 모든 잠금을 해제합니다.


