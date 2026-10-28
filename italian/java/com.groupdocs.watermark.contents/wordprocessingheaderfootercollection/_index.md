---
title: "WordProcessingHeaderFooterCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di intestazioni e piè di pagina in un documento Word."
type: docs
weight: 132
url: /it/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Rappresenta una raccolta di intestazioni e piè di pagina in un documento Word.

Questa raccolta contiene gli elementi di tipo `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Ottiene l'intestazione o il piè di pagina del tipo specificato. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Collega o scollega tutte le intestazioni e i piè di pagina al corrispondente |
intestazioni e piè di pagina nella sezione precedente.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Ottiene l'intestazione o il piè di pagina del tipo specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | headerFooterType | int | Un valore `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` che specifica il tipo di intestazione/piè di pagina da ottenere. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Collega o scollega tutte le intestazioni e i piè di pagina al corrispondente
intestazioni e piè di pagina nella sezione precedente.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | True per collegare le intestazioni e i piè di pagina alla sezione precedente; false per scollegarli. |
|

