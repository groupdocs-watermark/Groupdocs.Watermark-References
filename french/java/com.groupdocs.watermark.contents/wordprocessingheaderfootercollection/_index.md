---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection d'en-têtes et pieds de page dans un document Word."
type: docs
weight: 132
url: /fr/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Représente une collection d'en-têtes et pieds de page dans un document Word.

Cette collection contient les éléments du type `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Obtient l'en-tête ou le pied de page du type spécifié. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Lie ou délie tous les en-têtes et pieds de page au correspondant |
en-têtes et pieds de page dans la section précédente.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Obtient l'en-tête ou le pied de page du type spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | headerFooterType | int | Une valeur `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` qui spécifie le type de l'en-tête/pied de page à obtenir. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Lie ou délie tous les en-têtes et pieds de page au correspondant
en-têtes et pieds de page dans la section précédente.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | Vrai pour lier les en-têtes et pieds de page à la section précédente ; faux pour les délier. |
|

