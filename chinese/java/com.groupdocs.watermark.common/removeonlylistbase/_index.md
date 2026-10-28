---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供强类型仅删除列表的抽象基类。"
type: docs
weight: 17
url: /zh/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

提供强类型仅删除列表的抽象基类。


T
: 元素的类型。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | 获取一个值，指示集合是否为只读。 |
|
|  | [clear()](#clear--) | 从集合中移除所有项。 |
|
|  | [remove(T item)](#remove-T-) | 从集合中移除特定对象的第一次出现。 |
|
|  | [removeAt(int index)](#removeAt-int-) | 移除指定索引处的项。 |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，指示集合是否为只读。


**Returns:**
boolean - 如果集合为只读则返回 true；否则返回 false。

### clear() {#clear--}
```
public final void clear()
```


从集合中移除所有项。


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


从集合中移除特定对象的第一次出现。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | item | T | 要从集合中移除的项。 |
|

**Returns:**
boolean - 如果成功移除项则为 true；否则为 false。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除指定索引处的项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | index | int | 要移除的项的零基索引。 |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | T |  |

