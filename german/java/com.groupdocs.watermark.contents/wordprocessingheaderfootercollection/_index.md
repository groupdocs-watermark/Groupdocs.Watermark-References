---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von Kopf- und Fußzeilen in einem Word-Dokument dar."
type: docs
weight: 132
url: /de/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Stellt eine Sammlung von Kopf- und Fußzeilen in einem Word-Dokument dar.

Diese Sammlung enthält Elemente des Typs `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Ruft die Kopf- oder Fußzeile des angegebenen Typs ab. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Verknüpft oder löst die Verknüpfung aller Kopf‑ und Fußzeilen mit den entsprechenden |
Kopf‑ und Fußzeilen im vorherigen Abschnitt.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Ruft die Kopf- oder Fußzeile des angegebenen Typs ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | headerFooterType | int | Ein `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)`‑Wert, der den Typ der abzurufenden Kopf‑ oder Fußzeile angibt. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Verknüpft oder löst die Verknüpfung aller Kopf‑ und Fußzeilen mit den entsprechenden
Kopf‑ und Fußzeilen im vorherigen Abschnitt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | True, um die Kopf‑ und Fußzeilen mit dem vorherigen Abschnitt zu verknüpfen; false, um die Verknüpfung zu lösen. |
|

