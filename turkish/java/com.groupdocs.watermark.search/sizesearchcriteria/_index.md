---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Filigran boyutuna göre filtrelemeye izin veren kriterleri temsil eder."
type: docs
weight: 57
url: /tr/java/com.groupdocs.watermark.search/sizesearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class SizeSearchCriteria extends SearchCriteria
```

Filigran boyutuna göre filtrelemeye izin veren kriterleri temsil eder.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Aşağıdaki örnek, arama ölçütlerini kullanarak filigranları bulma ve kaldırma yöntemini gösterir.
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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SizeSearchCriteria(int dimension, double min, double max)](#SizeSearchCriteria-int-double-double-) | Belirtilen boyut, başlangıç değeri ve bitiş değeri ile `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMinimum()](#getMinimum--) | Başlangıç değerini alır. |
|
|  | [getMaximum()](#getMaximum--) | Bitiş değerini alır. |
|
|  | [getDimension()](#getDimension--) | Aranacak filigranın boyutunu alır. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### SizeSearchCriteria(int dimension, double min, double max) {#SizeSearchCriteria-int-double-double-}
```
public SizeSearchCriteria(int dimension, double min, double max)
```


Belirtilen boyut, başlangıç değeri ve bitiş değeri ile `[SizeSearchCriteria](../../com.groupdocs.watermark.search/sizesearchcriteria)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dimension | int | Aranacak bir filigranın `[Dimension](../../com.groupdocs.watermark.common/dimension)` boyutu. |
|
|  | min | double | Başlangıç değeri. |
|
|  | max | double | Son değer. |
|

### getMinimum() {#getMinimum--}
```
public final double getMinimum()
```


Başlangıç değerini alır.


**Returns:**
double - Başlangıç değeri.

### getMaximum() {#getMaximum--}
```
public final double getMaximum()
```


Bitiş değerini alır.


**Returns:**
double - Son değer.

### getDimension() {#getDimension--}
```
public final int getDimension()
```


Aranacak filigranın boyutunu alır.


**Returns:**
int - Arama yapılacak filigranın boyutu.

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

