---
title: "ShapeSearchAdapter"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크 검색에 포함될 문서의 특정 부분을 포함하는 도형에 대한 기본 클래스를 제공합니다."
type: docs
weight: 56
url: /ko/java/com.groupdocs.watermark.search/shapesearchadapter/
---
**Inheritance:**
java.lang.Object
```
public abstract class ShapeSearchAdapter
```

워터마크에 포함될 문서의 특정 부분을 포함하는 도형에 대한 기본 클래스를 제공합니다.
검색.

## 메서드

| 메서드 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageData | byte[] |  |

