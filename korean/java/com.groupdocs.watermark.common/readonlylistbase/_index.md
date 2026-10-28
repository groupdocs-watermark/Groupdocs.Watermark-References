---
title: "ReadOnlyListBase"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "강력히 형식이 지정된 읽기 전용 목록에 대한 추상 기본 클래스를 제공합니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

강력히 형식이 지정된 읽기 전용 목록에 대한 추상 기본 클래스를 제공합니다.


T
: 요소의 유형.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCount()](#getCount--) | 컬렉션에 포함된 요소 수를 가져옵니다. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | 컬렉션에서 지정된 인덱스에 있는 요소를 가져옵니다. |
|
|  | [contains(T item)](#contains-T-) | 컬렉션에 특정 항목이 포함되어 있는지 확인합니다. |
|
|  | [indexOf(T item)](#indexOf-T-) | 컬렉션에서 특정 항목의 인덱스를 확인합니다. |
|
|  | [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


컬렉션에 포함된 요소 수를 가져옵니다.


**Returns:**
int - 컬렉션에 포함된 요소 수.

### getInnerList() {#getInnerList--}
```
public final System.Collections.Generic.List<T> getInnerList()
```


<br />



**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### get_Item(int index) {#get-Item-int-}
```
public T get_Item(int index)
```


컬렉션에서 지정된 인덱스에 있는 요소를 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int | 가져올 요소의 0부터 시작하는 인덱스. 값: 지정된 인덱스에 있는 요소. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


컬렉션에 특정 항목이 포함되어 있는지 확인합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 항목 | T | 컬렉션에서 찾을 항목. |
|

**Returns:**
boolean - 컬렉션에서 항목을 찾으면 true, 그렇지 않으면 false.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


컬렉션에서 특정 항목의 인덱스를 확인합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 항목 | T | 컬렉션에서 찾을 항목. |
|

**Returns:**
int - 컬렉션에서 항목을 찾으면 해당 인덱스, 찾지 못하면 -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.


**Returns:**
java.util.Iterator<T> - 컬렉션을 순회하는 데 사용할 수 있는 IEnumerator{T} 객체.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 항목 | T |  |

