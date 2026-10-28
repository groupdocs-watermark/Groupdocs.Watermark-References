---
title: "RemoveOnlyListBase"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "강력히 형식이 지정된 제거 전용 목록에 대한 추상 기본 클래스를 제공합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

강력히 형식이 지정된 제거 전용 목록에 대한 추상 기본 클래스를 제공합니다.


T
: 요소의 유형.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [clear()](#clear--) | 컬렉션의 모든 항목을 제거합니다. |
|
|  | [remove(T item)](#remove-T-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
|
|  | [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 항목을 제거합니다. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 컬렉션이 읽기 전용이면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

### clear() {#clear--}
```
public final void clear()
```


컬렉션의 모든 항목을 제거합니다.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 항목 | T | 컬렉션에서 제거할 항목. |
|

**Returns:**
boolean - 항목이 성공적으로 제거되면 true, 그렇지 않으면 false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


지정된 인덱스에 있는 항목을 제거합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int | 제거할 항목의 0 기반 인덱스. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 항목 | T |  |

