---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een verzameling kop- en voetteksten in een Word-document voor."
type: docs
weight: 132
url: /nl/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Stelt een verzameling kop- en voetteksten in een Word-document voor.

Deze collectie bevat de items van het type `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Haalt de koptekst of voettekst op van het opgegeven type. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Koppelt of ontkoppelt alle kopteksten en voetteksten aan de overeenkomstige |
kopteksten en voetteksten in de vorige sectie.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Haalt de koptekst of voettekst op van het opgegeven type.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | headerFooterType | int | Een `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` waarde die het type van de op te halen koptekst/voettekst specificeert. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Koppelt of ontkoppelt alle kopteksten en voetteksten aan de overeenkomstige
kopteksten en voetteksten in de vorige sectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | True om de kopteksten en voetteksten aan de vorige sectie te koppelen; false om ze te ontkoppelen. |
|

