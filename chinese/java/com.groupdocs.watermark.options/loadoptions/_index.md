---
title: "LoadOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在加载文档时的文档加载选项。"
type: docs
weight: 24
url: /zh/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

表示在加载文档时的文档加载选项。

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | 初始化 `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 类的新实例。 |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | 使用指定的密码初始化 `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 获取打开加密文档的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置打开加密文档的密码。 |
|
|  | [getFormatFamily()](#getFormatFamily--) | 获取文档的格式族，指示其类型（例如，Image、Pdf、Spreadsheet 等）。 |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | 设置文档的格式族，指示其类型（例如，Image、Pdf、Spreadsheet 等）。 |
|
|  | [getFileType()](#getFileType--) | 获取文件的类型，指示其类型（例如，docx、pdf、xlsx 等）。 |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | 设置文件的类型，指示其类型（例如，docx、pdf、xlsx 等）。 |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


初始化 `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 类的新实例。


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


使用指定的密码初始化 `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 密码 | java.lang.String | 打开加密内容的密码。 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取打开加密文档的密码。


**Returns:**
java.lang.String - 打开加密文档的密码。

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置打开加密文档的密码。

密码可以为 null 或空字符串。默认值为 null。
如果内容未加密，请将此设置为 null 或空字符串。

以下示例演示如何加载受密码保护的文档。
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 打开加密文档的密码。 |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


获取文档的格式族，指示其类型（例如，Image、Pdf、Spreadsheet 等）。


**Returns:**
int - formatFamily 文件类型。

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


设置文档的格式族，指示其类型（例如，Image、Pdf、Spreadsheet 等）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | formatFamily | int | 文件类型。 |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


获取文件的类型，指示其类型（例如，docx、pdf、xlsx 等）。


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


设置文件的类型，指示其类型（例如，docx、pdf、xlsx 等）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | 文件类型。 |
|

