---
title: "LoadOptions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir belge yüklenirken belge yükleme seçeneklerini temsil eder."
type: docs
weight: 24
url: /tr/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Bir belge yüklenirken belge yükleme seçeneklerini temsil eder.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Yeni bir `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` sınıfı örneği başlatır. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Belirtilen bir şifre ile yeni bir `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreli bir belgeyi açmak için şifreyi alır. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreli bir belgeyi açmak için şifreyi ayarlar. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Belgenin format ailesini alır, tipini gösterir (ör. Image, Pdf, Spreadsheet vb.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Belgenin format ailesini ayarlar, tipini gösterir (ör. Image, Pdf, Spreadsheet vb.). |
|
|  | [getFileType()](#getFileType--) | Dosyanın tipini alır, tipini gösterir (ör. docx, pdf, xlsx vb.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Dosyanın tipini ayarlar, tipini gösterir (ör. docx, pdf, xlsx vb.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Yeni bir `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` sınıfı örneği başlatır.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Belirtilen bir şifre ile yeni bir `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` sınıfı örneği başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | şifre | java.lang.String | Şifreli içeriği açmak için kullanılan şifre. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreli bir belgeyi açmak için şifreyi alır.


**Returns:**
java.lang.String - Şifreli bir belgeyi açmak için şifre.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreli bir belgeyi açmak için şifreyi ayarlar.

Şifre null veya boş bir dize olabilir. Varsayılan değer null'dur.
İçerik şifreli değilse, bunu null veya boş dizeye ayarlayın.

Aşağıdaki örnek, şifreyle korunan bir belgeyi nasıl yükleyeceğinizi gösterir.
>
> ````
> ```
>
>    LoadOptions loadOptions = new LoadOptions();
>    loadOptions.setPassword("pwd123");
>  
>    Watermarker watermarker = new Watermarker("D:\\doc.vsdx", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Şifreli bir belgeyi açmak için şifre. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Belgenin format ailesini alır, tipini gösterir (ör. Image, Pdf, Spreadsheet vb.).


**Returns:**
int - formatFamily Dosya tipi.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Belgenin format ailesini ayarlar, tipini gösterir (ör. Image, Pdf, Spreadsheet vb.).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | formatFamily | int | Dosya tipi. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Dosyanın tipini alır, tipini gösterir (ör. docx, pdf, xlsx vb.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Dosyanın tipini ayarlar, tipini gösterir (ör. docx, pdf, xlsx vb.).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Dosya tipi. |
|

