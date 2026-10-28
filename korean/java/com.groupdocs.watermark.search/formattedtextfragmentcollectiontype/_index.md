---
title: "FormattedTextFragmentCollectionType"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "서식 있는 텍스트 조각 컬렉션이 포함할 수 있는 요소 수를 지정합니다."
type: docs
weight: 28
url: /ko/java/com.groupdocs.watermark.search/formattedtextfragmentcollectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class FormattedTextFragmentCollectionType
```

서식 있는 텍스트 조각 컬렉션이 포함할 수 있는 요소 수를 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [UnlimitedFragments](#UnlimitedFragments) | 여러 스타일을 허용하며, 컬렉션은 무제한 개수의 조각을 포함할 수 있습니다. |
|
|  | [SingleFragment](#SingleFragment) | 전체 텍스트는 단일 스타일로 포맷할 수 있으며, 컬렉션은 하나의 조각만 포함할 수 있습니다. |
|
|  | [NoFormattedText](#NoFormattedText) | 부모 객체는 텍스트 포맷을 지원하지 않으며, 컬렉션은 항상 비어 있습니다. |
|
### UnlimitedFragments {#UnlimitedFragments}
```
public static final int UnlimitedFragments
```


여러 스타일을 허용하며, 컬렉션은 무제한 개수의 조각을 포함할 수 있습니다.


### SingleFragment {#SingleFragment}
```
public static final int SingleFragment
```


전체 텍스트는 단일 스타일로 포맷할 수 있으며, 컬렉션은 하나의 조각만 포함할 수 있습니다.


### NoFormattedText {#NoFormattedText}
```
public static final int NoFormattedText
```


부모 객체는 텍스트 포맷을 지원하지 않으며, 컬렉션은 항상 비어 있습니다.


