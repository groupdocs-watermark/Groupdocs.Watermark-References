---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक strongly typed read-only सूची के लिए abstract base class प्रदान करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

एक strongly typed read-only सूची के लिए abstract base class प्रदान करता है।


T
: तत्व का प्रकार।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getCount()](#getCount--) | संग्रह में शामिल तत्वों की संख्या प्राप्त करता है। |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
|
|  | [contains(T item)](#contains-T-) | निर्धारित करता है कि क्या संग्रह में कोई विशिष्ट आइटम है। |
|
|  | [indexOf(T item)](#indexOf-T-) | संग्रह में किसी विशिष्ट आइटम का अनुक्रमांक निर्धारित करता है। |
|
|  | [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


संग्रह में शामिल तत्वों की संख्या प्राप्त करता है।


**Returns:**
int - संग्रह में शामिल तत्वों की संख्या।

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


संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | सूचकांक | int | प्राप्त करने वाले तत्व का शून्य-आधारित सूचकांक। मान: निर्दिष्ट सूचकांक पर तत्व। |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


निर्धारित करता है कि क्या संग्रह में कोई विशिष्ट आइटम है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | आइटम | T | संग्रह में खोजने के लिए आइटम। |
|

**Returns:**
boolean - यदि आइटम संग्रह में पाया जाता है तो True; अन्यथा false।

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


संग्रह में किसी विशिष्ट आइटम का अनुक्रमांक निर्धारित करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | आइटम | T | संग्रह में खोजने के लिए आइटम। |
|

**Returns:**
int - यदि आइटम संग्रह में पाया जाता है तो उसका सूचकांक; अन्यथा -1।

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


एक enumerator लौटाता है जो संग्रह के माध्यम से इटररेट करता है।


**Returns:**
java.util.Iterator<T> - एक IEnumerator{T} ऑब्जेक्ट जिसे संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है।

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आइटम | T |  |

