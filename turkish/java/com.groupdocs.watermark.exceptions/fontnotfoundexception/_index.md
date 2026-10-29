---
title: "FontNotFoundException"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Talep edilen yazı tipi bulunamadığında atılan istisna."
type: docs
weight: 12
url: /tr/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

Talep edilen yazı tipi bulunamadığında atılan istisna.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | Yeni bir `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` sınıfı örneği başlatır. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | Belirtilen bir yazı tipi adıyla yeni bir `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFontName()](#getFontName--) | İstenen yazı tipi adını alır. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


Yeni bir `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` sınıfı örneği başlatır.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


Belirtilen bir yazı tipi adıyla yeni bir `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` sınıfı örneği başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fontName | java.lang.String | İstenen yazı tipi adı. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


İstenen yazı tipi adını alır.


**Returns:**
java.lang.String - İstenen yazı tipi adı.

