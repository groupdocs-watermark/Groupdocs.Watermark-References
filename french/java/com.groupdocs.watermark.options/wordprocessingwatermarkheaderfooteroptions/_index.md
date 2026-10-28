---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options lors de l'ajout du filigrane à l'en-tête/pied de page d'une section Word."
type: docs
weight: 74
url: /fr/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Représente les options lors de l'ajout du filigrane à l'en-tête/pied de page d'une section Word.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Initialise une nouvelle instance de la classe `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Obtient l'index d'une section où ajouter le filigrane. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Définit l'index d'une section où ajouter le filigrane. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Obtient la valeur qui identifie le type d'en-tête ou de pied de page où ajouter le filigrane. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Définit la valeur qui identifie le type d’en-tête ou de pied de page auquel ajouter le filigrane. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Initialise une nouvelle instance de la classe `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Obtient l'index d'une section où ajouter le filigrane.


**Returns:**
int - L’indice d’une section à laquelle ajouter le filigrane.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Définit l'index d'une section où ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L’indice d’une section à laquelle ajouter le filigrane. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Obtient la valeur qui identifie le type d'en-tête ou de pied de page où ajouter le filigrane.


**Returns:**
int - La valeur du type `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` qui identifie le type d’en-tête ou de pied de page auquel ajouter le filigrane.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Définit la valeur qui identifie le type d’en-tête ou de pied de page auquel ajouter le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | int | La valeur du type `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` qui identifie le type d’en-tête ou de pied de page auquel ajouter le filigrane. |
|

