---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير تسمح بالترشيح حسب حجم العلامة المائية."
type: docs
weight: 57
url: /ar/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

يمثل معايير تسمح بالترشيح حسب حجم العلامة المائية.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

المثال التالي يوضح كيفية العثور على العلامات المائية وإزالتها باستخدام معايير البحث.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
>    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
>    TextSearchCriteria textCriteria = new TextSearchCriteria(Pattern.compile("^Test watermark$"));
>
>    PossibleWatermarkCollection watermarks = watermarker.search(textCriteria.and(widthRange.or(rotateAngle)));
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | يقوم بتهيئة نسخة جديدة من الفئة `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` بأبعاد محددة، قيمة بداية وقيمة نهاية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | يحصل على قيمة البداية. |
|
|  | [getMaximum()](#getMaximum--) | يحصل على قيمة النهاية. |
|
|  | [getDimension()](#getDimension--) | يحصل على البُعد الخاص بالعلامة المائية للبحث به. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


يقوم بتهيئة نسخة جديدة من الفئة `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` بأبعاد محددة، قيمة بداية وقيمة نهاية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | dimension | int | البُعد `[Dimension](../../com.groupdocs.watermark.common/dimension)` للعلامة المائية للبحث به. |
|
|  | min | double | قيمة البداية. |
|
|  | الحد الأقصى | double | القيمة النهائية. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


يحصل على قيمة البداية.


**Returns:**
double - القيمة الابتدائية.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


يحصل على قيمة النهاية.


**Returns:**
double - القيمة النهائية.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


يحصل على البُعد الخاص بالعلامة المائية للبحث به.


**Returns:**
int - البُعد الذي يُبحث به عن العلامة المائية.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

