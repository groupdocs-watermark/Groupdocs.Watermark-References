---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير البحث للعثور على الصور في المحتوى."
type: docs
weight: 33
url: /ar/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

يمثل معايير البحث للعثور على الصور في المحتوى.

<br />

*** ** * ** ***

يستخدم هذا معيار البحث صورة مصغرة ثنائية لحساب تشابه الصور.

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | ينشئ مثيلًا جديدًا للفئة `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` بمسار ملف محدد. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | ينشئ مثيلًا جديدًا للفئة `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` بتدفق محدد. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | يحصل على حجم الصورة المصغرة. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | يضبط حجم الصورة المصغرة. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


ينشئ مثيلًا جديدًا للفئة `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` بمسار ملف محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لتحميل الصورة منه. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


ينشئ مثيلًا جديدًا للفئة `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` بتدفق محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | java.io.InputStream | التدفق لتحميل الصورة منه. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


يحصل على حجم الصورة المصغرة.


**Returns:**
byte - سيتم استخدام صورة مصغرة بحجم 32X32 بشكل افتراضي.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


يضبط حجم الصورة المصغرة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | byte | سيتم استخدام صورة مصغرة بحجم 32X32 بشكل افتراضي. |
|

