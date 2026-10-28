---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة من الرؤوس والتذييلات في مستند Word."
type: docs
weight: 132
url: /ar/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

يمثل مجموعة من الرؤوس والتذييلات في مستند Word.

تحتوي هذه المجموعة على العناصر من النوع `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | يحصل على الرأس أو التذييل من النوع المحدد. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | يربط أو يفك ربط جميع الرؤوس والتذييلات بالمتطابق |
الرؤوس والتذييلات في القسم السابق.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


يحصل على الرأس أو التذييل من النوع المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | headerFooterType | int | قيمة `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` تحدد نوع الرأس/التذييل المراد الحصول عليه. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


يربط أو يفك ربط جميع الرؤوس والتذييلات بالمتطابق
الرؤوس والتذييلات في القسم السابق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | True لربط الرؤوس والتذييلات بالقسم السابق؛ false لفك ربطها. |
|

