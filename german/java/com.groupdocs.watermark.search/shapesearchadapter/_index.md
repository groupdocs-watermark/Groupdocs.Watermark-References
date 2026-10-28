---
title: "ShapeSearchAdapter"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die Basisklasse für ein Shape bereit, das bestimmte Dokumentteile enthält, die in die Wasserzeichen‑Suche einbezogen werden sollen."
type: docs
weight: 56
url: /de/java/com.groupdocs.watermark.search/shapesearchadapter/
---
**Inheritance:**
java.lang.Object
```
public abstract class ShapeSearchAdapter
```

Stellt die Basisklasse für ein Shape bereit, das bestimmte Dokumentteile enthält, die in das Wasserzeichen einbezogen werden sollen.
Suche.

## Methoden

| Methode | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageData | byte[] |  |

