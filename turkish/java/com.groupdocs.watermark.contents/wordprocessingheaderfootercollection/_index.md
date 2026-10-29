---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Word belgesindeki üstbilgi ve altbilgilerin bir koleksiyonunu temsil eder."
type: docs
weight: 132
url: /tr/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Bir Word belgesindeki üstbilgi ve altbilgilerin bir koleksiyonunu temsil eder.

Bu koleksiyon, `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` türündeki öğeleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Belirtilen tipteki üstbilgi veya altbilgiyi alır. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Tüm başlıkları ve altbilgileri ilgili olanlarla bağlar veya bağlamayı kaldırır |
önceki bölümdeki başlıkları ve altbilgileri.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Belirtilen tipteki üstbilgi veya altbilgiyi alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | headerFooterType | int | Alınacak üstbilgi/altbilgi tipini belirten bir `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` değeri. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Tüm başlıkları ve altbilgileri ilgili olanlarla bağlar veya bağlamayı kaldırır
önceki bölümdeki başlıkları ve altbilgileri.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | Başlıkları ve altbilgileri önceki bölüme bağlamak için true; bağlamayı kaldırmak için false. |
|

