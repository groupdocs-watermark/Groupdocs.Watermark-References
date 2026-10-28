---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供强类型只读列表的抽象基类。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

提供强类型只读列表的抽象基类。


T
: 元素的类型。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCount()](#getCount--) | 获取集合中包含的元素数量。 |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | 获取集合中指定索引处的元素。 |
|
|  | [contains(T item)](#contains-T-) | 确定集合是否包含特定项。 |
|
|  | [indexOf(T item)](#indexOf-T-) | 确定集合中特定项的索引。 |
|
|  | [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


获取集合中包含的元素数量。


**Returns:**
int - 集合中包含的元素数量。

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


获取集合中指定索引处的元素。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | index | int | 要获取的元素的零基索引。值：指定索引处的元素。 |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


确定集合是否包含特定项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | item | T | 要在集合中定位的项。 |
|

**Returns:**
boolean - 如果在集合中找到该项则为 true；否则为 false。

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


确定集合中特定项的索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | item | T | 要在集合中定位的项。 |
|

**Returns:**
int - 如果在集合中找到该项则返回其索引；否则返回 -1。

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


返回一个遍历集合的枚举器。


**Returns:**
java.util.Iterator<T> - 可用于遍历集合的 IEnumerator{T} 对象。

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | T |  |

