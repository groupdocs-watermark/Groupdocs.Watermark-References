---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معايير تسمح بالترشيح حسب زاوية دوران العلامة المائية."
type: docs
weight: 52
url: /ar/java/com.groupdocs.watermark.search/rotateanglesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class RotateAngleSearchCriteria extends SearchCriteria
```

يمثل معايير تسمح بالترشيح حسب زاوية دوران العلامة المائية.

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
|  | [RotateAngleSearchCriteria(double minAngle, double maxAngle)](#RotateAngleSearchCriteria-double-double-) | ينشئ مثيلاً جديداً للفئة `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` مع زاوية بداية وزاوية نهاية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMinimumAngle()](#getMinimumAngle--) | يحصل على زاوية البداية بالدرجات. |
|
|  | [getMaximumAngle()](#getMaximumAngle--) | يحصل على زاوية النهاية بالدرجات. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### RotateAngleSearchCriteria(double minAngle, double maxAngle) {#RotateAngleSearchCriteria-double-double-}
```
public RotateAngleSearchCriteria(double minAngle, double maxAngle)
```


ينشئ مثيلاً جديداً للفئة `[RotateAngleSearchCriteria](../../com.groupdocs.watermark.search/rotateanglesearchcriteria)` مع زاوية بداية وزاوية نهاية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | minAngle | double | زاوية البداية بالدرجات. |
|
|  | maxAngle | double | زاوية النهاية بالدرجات. |
|

### getMinimumAngle() {#getMinimumAngle--}
```
public final double getMinimumAngle()
```


يحصل على زاوية البداية بالدرجات.


**Returns:**
double - زاوية البداية.

### getMaximumAngle() {#getMaximumAngle--}
```
public final double getMaximumAngle()
```


يحصل على زاوية النهاية بالدرجات.


**Returns:**
double - زاوية النهاية.

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

