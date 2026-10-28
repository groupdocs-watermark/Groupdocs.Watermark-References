---
title: "FontNotFoundException"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "当未找到请求的字体时抛出的异常。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

当未找到请求的字体时抛出的异常。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | 初始化一个新的 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 类实例。 |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | 使用指定的字体名称初始化一个新的 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 类实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFontName()](#getFontName--) | 获取请求的字体名称。 |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


初始化一个新的 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 类实例。


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


使用指定的字体名称初始化一个新的 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 类实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fontName | java.lang.String | 请求的字体名称。 |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


获取请求的字体名称。


**Returns:**
java.lang.String - 请求的字体名称。

