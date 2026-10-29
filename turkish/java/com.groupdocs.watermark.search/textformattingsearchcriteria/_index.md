---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Metin biçimlendirmesine göre filtrelemeye izin veren kriterleri temsil eder."
type: docs
weight: 66
url: /tr/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Metin biçimlendirmesine göre filtrelemeye izin veren kriterleri temsil eder.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Aşağıdaki örnek, belirli bir
metin biçimlendirmesini (belge türünden bağımsız olarak).
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.doc");
>    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
>
>    criteria.setForegroundColorRange(new ColorRange());
>    criteria.getForegroundColorRange().setMinHue(-5);
>    criteria.getForegroundColorRange().setMaxHue(10);
>    criteria.getForegroundColorRange().setMinBrightness(0.01f);
>    criteria.getForegroundColorRange().setMaxBrightness(0.99f);
>    criteria.setBackgroundColorRange(new ColorRange());
>    criteria.getBackgroundColorRange().setEmpty(true);
>    criteria.setFontName("Arial");
>    criteria.setMinFontSize(19);
>    criteria.setMaxFontSize(42);
>    criteria.setFontBold(true);
>
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
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
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Yeni bir `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Metin ön plan rengine göre filigranları filtrelemek için kullanılan renk aralığını alır. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Metin ön plan rengine göre filigranları filtrelemek için kullanılan renk aralığını ayarlar. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Metin arka plan rengine göre filigranları filtrelemek için kullanılan renk aralığını alır. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Metin arka plan rengine göre filigranları filtrelemek için kullanılan renk aralığını ayarlar. |
|
|  | [getFontName()](#getFontName--) | Olası filigran metin biçimlendirmesinde kullanılan yazı tipinin adını alır. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Olası filigran metin biçimlendirmesinde kullanılan yazı tipinin adını ayarlar. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Yazı tipi boyutunun başlangıç değerini alır. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Yazı tipi boyutunun başlangıç değerini ayarlar. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Yazı tipi boyutunun bitiş değerini alır. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Yazı tipi boyutunun bitiş değerini ayarlar. |
|
|  | [getFontBold()](#getFontBold--) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin kalın olup olmadığını gösteren değeri alır. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin kalın olup olmadığını gösteren değeri ayarlar. |
|
|  | [getFontItalic()](#getFontItalic--) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin italik olup olmadığını gösteren değeri alır. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin italik olup olmadığını gösteren değeri ayarlar. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin altı çizili olup olmadığını gösteren değeri alır. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin altı çizili olup olmadığını gösteren değeri ayarlar. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin üstü çizili olup olmadığını gösteren değeri alır. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Filigran metin biçimlendirmesinde kullanılan yazı tipinin üstü çizili olup olmadığını gösteren değeri ayarlar. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Yeni bir `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)` sınıfı örneği başlatır.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Metin ön plan rengine göre filigranları filtrelemek için kullanılan renk aralığını alır.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Metin ön plan rengine göre filigranları filtrelemek için kullanılan renk aralığını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Metin ön plan rengine göre filigranları filtrelemek için kullanılan renk aralığı. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Metin arka plan rengine göre filigranları filtrelemek için kullanılan renk aralığını alır.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Metin arka plan rengine göre filigranları filtrelemek için kullanılan renk aralığını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | Metin arka plan rengine göre filigranları filtrelemek için kullanılan renk aralığı. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Olası filigran metin biçimlendirmesinde kullanılan yazı tipinin adını alır.


**Returns:**
java.lang.String - Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Olası filigran metin biçimlendirmesinde kullanılan yazı tipinin adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Yazı tipi boyutunun başlangıç değerini alır.


**Returns:**
float - Yazı tipi boyutunun başlangıç değeri.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Yazı tipi boyutunun başlangıç değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Yazı tipi boyutunun başlangıç değeri. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Yazı tipi boyutunun bitiş değerini alır.


**Returns:**
float - Yazı tipi boyutunun bitiş değeri.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Yazı tipi boyutunun bitiş değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | float | Yazı tipi boyutunun bitiş değeri. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin kalın olup olmadığını gösteren değeri alır.


**Returns:**
java.lang.Boolean - Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin kalın olup olmadığını gösteren değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Boolean | Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin italik olup olmadığını gösteren değeri alır.


**Returns:**
java.lang.Boolean - Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin italik olup olmadığını gösteren değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Boolean | Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin altı çizili olup olmadığını gösteren değeri alır.


**Returns:**
java.lang.Boolean - Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin altı çizili olup olmadığını gösteren değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Boolean | Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin üstü çizili olup olmadığını gösteren değeri alır.


**Returns:**
java.lang.Boolean - Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Filigran metin biçimlendirmesinde kullanılan yazı tipinin üstü çizili olup olmadığını gösteren değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Boolean | Varsayılan değer null'dur, bu da filtrenin uygulanmadığı anlamına gelir. |
|

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

