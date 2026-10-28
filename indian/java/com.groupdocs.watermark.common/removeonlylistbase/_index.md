---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक strongly typed remove-only सूची के लिए abstract base class प्रदान करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

एक strongly typed remove-only सूची के लिए abstract base class प्रदान करता है।


T
: तत्व का प्रकार।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | कलेक्शन केवल-पढ़ने योग्य है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [clear()](#clear--) | कलेक्शन से सभी आइटम हटाता है। |
|
|  | [remove(T item)](#remove-T-) | कलेक्शन से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिति हटाता है। |
|
|  | [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर स्थित आइटम हटाता है। |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


कलेक्शन केवल-पढ़ने योग्य है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि कलेक्शन केवल-पढ़ने योग्य है तो true लौटाता है; अन्यथा false।

### clear() {#clear--}
```
public final void clear()
```


कलेक्शन से सभी आइटम हटाता है।


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


कलेक्शन से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिति हटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | आइटम | T | कलेक्शन से हटाने के लिए आइटम। |
|

**Returns:**
boolean - यदि आइटम सफलतापूर्वक हटाया गया तो true; अन्यथा false।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


निर्दिष्ट इंडेक्स पर स्थित आइटम हटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | सूचकांक | int | हटाने वाले आइटम का शून्य-आधारित इंडेक्स। |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आइटम | T |  |

