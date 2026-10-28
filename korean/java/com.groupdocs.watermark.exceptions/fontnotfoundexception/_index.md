---
title: "FontNotFoundException"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "요청된 폰트를 찾을 수 없을 때 발생하는 예외입니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.watermark.exceptions/fontnotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.groupdocs.watermark.exceptions.WatermarkException](../../com.groupdocs.watermark.exceptions/watermarkexception)
```
public class FontNotFoundException extends WatermarkException
```

요청된 폰트를 찾을 수 없을 때 발생하는 예외입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FontNotFoundException()](#FontNotFoundException--) | 새 인스턴스를 초기화합니다 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 클래스. |
|
|  | [FontNotFoundException(String fontName)](#FontNotFoundException-java.lang.String-) | 지정된 폰트 이름으로 새 인스턴스를 초기화합니다 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 클래스. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFontName()](#getFontName--) | 요청된 폰트 이름을 가져옵니다. |
|
### FontNotFoundException() {#FontNotFoundException--}
```
public FontNotFoundException()
```


새 인스턴스를 초기화합니다 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 클래스.


### FontNotFoundException(String fontName) {#FontNotFoundException-java.lang.String-}
```
public FontNotFoundException(String fontName)
```


지정된 폰트 이름으로 새 인스턴스를 초기화합니다 `[FontNotFoundException](../../com.groupdocs.watermark.exceptions/fontnotfoundexception)` 클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fontName | java.lang.String | 요청된 폰트 이름. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


요청된 폰트 이름을 가져옵니다.


**Returns:**
java.lang.String - 요청된 폰트 이름.

