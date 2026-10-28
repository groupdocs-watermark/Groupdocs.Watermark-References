---
title: "ShapeSearchAdapter"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce la classe base per una forma contenente parti specifiche del documento da includere nella ricerca di filigrana."
type: docs
weight: 56
url: /it/java/com.groupdocs.watermark.search/shapesearchadapter/
---
**Inheritance:**
java.lang.Object
```
public abstract class ShapeSearchAdapter
```

Fornisce la classe base per una forma contenente parti specifiche del documento da includere nella filigrana.
ricerca.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageData | byte[] |  |

