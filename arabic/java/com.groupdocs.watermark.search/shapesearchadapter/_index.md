---
title: "ShapeSearchAdapter"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر الفئة الأساسية لشكل يحتوي على أجزاء محددة من المستند التي يجب تضمينها في بحث العلامة المائية."
type: docs
weight: 56
url: /ar/java/com.groupdocs.watermark.search/shapesearchadapter/
---
**Inheritance:**
java.lang.Object
```
public abstract class ShapeSearchAdapter
```

يوفر الفئة الأساسية لشكل يحتوي على أجزاء محددة من المستند التي يجب تضمينها في العلامة المائية.
بحث.

## الطرق

| طريقة | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | byte[] |  |

