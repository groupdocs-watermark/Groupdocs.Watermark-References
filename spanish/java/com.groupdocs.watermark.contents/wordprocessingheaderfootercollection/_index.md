---
title: "WordProcessingHeaderFooterCollection"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una colección de encabezados y pies de página en un documento Word."
type: docs
weight: 132
url: /es/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Representa una colección de encabezados y pies de página en un documento Word.

Esta colección contiene los elementos del tipo `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Obtiene el encabezado o pie de página del tipo especificado. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Vincula o desvincula todos los encabezados y pies de página al correspondiente |
encabezados y pies de página en la sección anterior.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Obtiene el encabezado o pie de página del tipo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | headerFooterType | int | Un valor `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` que especifica el tipo de encabezado/pie de página a obtener. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Vincula o desvincula todos los encabezados y pies de página al correspondiente
encabezados y pies de página en la sección anterior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | True para vincular los encabezados y pies de página a la sección anterior; false para desvincularlos. |
|

