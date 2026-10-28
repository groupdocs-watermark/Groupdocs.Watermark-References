---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير البحث للعثور على الصور في المحتوى."
type: docs
weight: 30
url: /ar/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

يمثل معايير البحث للعثور على الصور في المحتوى.

<br />

*** ** * ** ***

معيار البحث هذا يستخدم مخططات ألوان الصورة لحساب تشابه الصور.

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` بمسار ملف محدد. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | يقوم بتهيئة نسخة جديدة من الفئة `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` بتدفق محدد. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | يحصل على عدد الصناديق التي ستُستخدم لبناء مخططات الألوان. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | يضبط عدد الصناديق التي ستُستخدم لبناء مخططات الألوان. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


يقوم بتهيئة نسخة جديدة من الفئة `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` بمسار ملف محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لتحميل الصورة منه. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


يقوم بتهيئة نسخة جديدة من الفئة `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` بتدفق محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | java.io.InputStream | التدفق لتحميل الصورة منه. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


يحصل على عدد الصناديق التي ستُستخدم لبناء مخططات الألوان.


**Returns:**
byte - القيمة الافتراضية هي 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


يضبط عدد الصناديق التي ستُستخدم لبناء مخططات الألوان.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | byte | القيمة الافتراضية هي 10. |
|

