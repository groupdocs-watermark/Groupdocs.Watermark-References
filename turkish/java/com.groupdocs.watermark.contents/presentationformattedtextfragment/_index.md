---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PowerPoint belgesindeki biçimlendirilmiş metnin bir parçasını temsil eder."
type: docs
weight: 82
url: /tr/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

PowerPoint belgesindeki biçimlendirilmiş metnin bir parçasını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | Parçanın metnini alır. |
|
|  | [getFont()](#getFont--) | Metnin yazı tipini alır. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Metnin ön plan rengini alır. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Metnin arka plan rengini alır. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Metinle ilişkili hiperlinki alır. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Metinle ilişkili hiperlinki ayarlar. |
|
### getText() {#getText--}
```
public String getText()
```


Parçanın metnini alır.


**Returns:**
java.lang.String - Parça metni.

### getFont() {#getFont--}
```
public Font getFont()
```


Metnin yazı tipini alır.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Metnin ön plan rengini alır.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Metnin arka plan rengini alır.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Metinle ilişkili hiperlinki alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | actionType | int | Hiperlinki etkinleştiren eylem. |
|

**Returns:**
java.lang.String - Belirtilen eylemde etkinleştirilen hiperlinkin URL'si.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Metinle ilişkili hiperlinki ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | actionType | int | Hiperlinki etkinleştiren eylem. |
|
|  | url | java.lang.String | Hiperlink URL'si. |
|

