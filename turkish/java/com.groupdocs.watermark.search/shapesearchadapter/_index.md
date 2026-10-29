---
title: "ShapeSearchAdapter"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Su işareti aramasına dahil edilecek belge parçalarını içeren bir şekil için temel sınıf sağlar."
type: docs
weight: 56
url: /tr/java/com.groupdocs.watermark.search/shapesearchadapter/
---
**Inheritance:**
java.lang.Object
```
public abstract class ShapeSearchAdapter
```

Su işareti içine dahil edilecek belge parçalarını içeren bir şekil için temel sınıf sağlar.
arama.

## Yöntemler

| Yöntem | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageData | byte[] |  |

