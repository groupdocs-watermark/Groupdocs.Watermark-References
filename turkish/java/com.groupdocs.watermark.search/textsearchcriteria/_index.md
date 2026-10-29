---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Filigran metnine göre filtrelemeye izin veren kriterleri temsil eder."
type: docs
weight: 67
url: /tr/java/com.groupdocs.watermark.search/textsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria)
```
public class TextSearchCriteria extends PageSearchCriteria
```

Filigran metnine göre filtrelemeye izin veren kriterleri temsil eder.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Aşağıdaki örnek, arama kriteri kullanarak filigranı nasıl bulup kaldıracağını gösterir.
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
|  | [TextSearchCriteria(Pattern pattern)](#TextSearchCriteria-java.util.regex.Pattern-) | Belirtilen bir düzenli ifadeyle `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` sınıfının yeni bir örneğini başlatır. |
|
| [TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)](#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-) |  |
|  | [TextSearchCriteria(String searchString, boolean isMatchCase)](#TextSearchCriteria-java.lang.String-boolean-) | Arama dizesi ve karşılaştırma için bir bayrakla `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` sınıfının yeni bir örneğini başlatır. |
|
|  | [TextSearchCriteria(String searchString)](#TextSearchCriteria-java.lang.String-) | Arama dizesiyle `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPattern()](#getPattern--) | Arama desenini alır. |
|
| [getPatternInternal()](#getPatternInternal--) |  |
|  | [getSkipUnreadableCharacters()](#getSkipUnreadableCharacters--) | Dize karşılaştırması sırasında okunamayan karakterlerin atlanacağını belirten bir değeri alır. |
|
|  | [setSkipUnreadableCharacters(boolean value)](#setSkipUnreadableCharacters-boolean-) | Dize karşılaştırması sırasında okunamayan karakterlerin atlanacağını belirten bir değeri ayarlar. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextSearchCriteria(Pattern pattern) {#TextSearchCriteria-java.util.regex.Pattern-}
```
public TextSearchCriteria(Pattern pattern)
```


Belirtilen bir düzenli ifadeyle `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | desen | java.util.regex.Pattern | Eşleşecek düzenli ifade. |
|

### TextSearchCriteria(System.Text.RegularExpressions.Regex pattern) {#TextSearchCriteria-com.aspose.ms.System.Text.RegularExpressions.Regex-}
```
public TextSearchCriteria(System.Text.RegularExpressions.Regex pattern)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| desen | com.aspose.ms.System.Text.RegularExpressions.Regex |  |

### TextSearchCriteria(String searchString, boolean isMatchCase) {#TextSearchCriteria-java.lang.String-boolean-}
```
public TextSearchCriteria(String searchString, boolean isMatchCase)
```


Arama dizesi ve karşılaştırma için bir bayrakla `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchString | java.lang.String | Aranacak tam dize. |
|
|  | isMatchCase | boolean | `false` karşılaştırma sırasında büyük/küçük harfi yok saymak için; aksi takdirde `true`. |
|

### TextSearchCriteria(String searchString) {#TextSearchCriteria-java.lang.String-}
```
public TextSearchCriteria(String searchString)
```


Arama dizesiyle `[TextSearchCriteria](../../com.groupdocs.watermark.search/textsearchcriteria)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchString | java.lang.String | Aranacak tam dize. |
|

### getPattern() {#getPattern--}
```
public final Pattern getPattern()
```


Arama desenini alır.


**Returns:**
java.util.regex.Pattern - Eşleşecek düzenli ifade deseni.

### getPatternInternal() {#getPatternInternal--}
```
public final System.Text.RegularExpressions.Regex getPatternInternal()
```




**Returns:**
com.aspose.ms.System.Text.RegularExpressions.Regex
### getSkipUnreadableCharacters() {#getSkipUnreadableCharacters--}
```
public final boolean getSkipUnreadableCharacters()
```


Dize karşılaştırması sırasında okunamayan karakterlerin atlanacağını belirten bir değeri alır.


**Returns:**
boolean - Dize karşılaştırması sırasında okunamayan karakterlerin atlanacağını belirten bir değer.

### setSkipUnreadableCharacters(boolean value) {#setSkipUnreadableCharacters-boolean-}
```
public final void setSkipUnreadableCharacters(boolean value)
```


Dize karşılaştırması sırasında okunamayan karakterlerin atlanacağını belirten bir değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Okunamayan karakterlerin dize karşılaştırması sırasında atlanacağını belirten bir değer. |
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

