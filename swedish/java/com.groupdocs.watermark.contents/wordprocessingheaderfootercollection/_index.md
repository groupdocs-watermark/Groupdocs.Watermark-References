---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling sidhuvuden och sidfötter i ett Word-dokument."
type: docs
weight: 132
url: /sv/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Representerar en samling sidhuvuden och sidfötter i ett Word-dokument.

Denna samling innehåller objekten av typen `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Hämtar sidhuvudet eller sidfoten av angiven typ. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Länkar eller avlänkar alla sidhuvuden och sidfötter till motsvarande |
sidhuvuden och sidfötter i föregående avsnitt.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Hämtar sidhuvudet eller sidfoten av angiven typ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | headerFooterType | int | Ett `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)`-värde som anger typen av sidhuvud/sidfots som ska hämtas. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Länkar eller avlänkar alla sidhuvuden och sidfötter till motsvarande
sidhuvuden och sidfötter i föregående avsnitt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | Sant för att länka sidhuvuden och sidfötter till föregående avsnitt; falskt för att avlänka dem. |
|

