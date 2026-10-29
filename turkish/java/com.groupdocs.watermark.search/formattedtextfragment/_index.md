---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "İçerikte biçimlendirilmiş metin parçacığı için soyut temel sınıf sağlar."
type: docs
weight: 26
url: /tr/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

İçerikte biçimlendirilmiş metin parçacığı için soyut temel sınıf sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
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
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Parçanın metnini alır.


**Returns:**
java.lang.String - Parça metni.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Metnin yazı tipini alır.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Metnin ön plan rengini alır.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Metnin arka plan rengini alır.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

