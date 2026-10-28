---
title: "LoadOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "문서를 로드할 때 문서 로드 옵션을 나타냅니다."
type: docs
weight: 24
url: /ko/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

문서를 로드할 때 문서 로드 옵션을 나타냅니다.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | 지정된 비밀번호로 `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 암호화된 문서를 열기 위한 비밀번호를 가져옵니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 암호화된 문서를 열기 위한 비밀번호를 설정합니다. |
|
|  | [getFormatFamily()](#getFormatFamily--) | 문서의 형식 패밀리를 가져옵니다. 이는 문서 유형(예: Image, Pdf, Spreadsheet 등)을 나타냅니다. |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | 문서의 형식 패밀리를 설정합니다. 이는 문서 유형(예: Image, Pdf, Spreadsheet 등)을 나타냅니다. |
|
|  | [getFileType()](#getFileType--) | 파일 유형을 가져옵니다. 이는 파일 유형(예: docx, pdf, xlsx 등)을 나타냅니다. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | 파일 유형을 설정합니다. 이는 파일 유형(예: docx, pdf, xlsx 등)을 나타냅니다. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


`[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 클래스의 새 인스턴스를 초기화합니다.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


지정된 비밀번호로 `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 비밀번호 | java.lang.String | 암호화된 콘텐츠를 열기 위한 비밀번호. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


암호화된 문서를 열기 위한 비밀번호를 가져옵니다.


**Returns:**
java.lang.String - 암호화된 문서를 열기 위한 비밀번호.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


암호화된 문서를 열기 위한 비밀번호를 설정합니다.

비밀번호는 null이거나 빈 문자열일 수 있습니다. 기본값은 null입니다.
내용이 암호화되지 않은 경우, 이를 null 또는 빈 문자열로 설정합니다.

다음 예제는 비밀번호로 보호된 문서를 로드하는 방법을 보여줍니다.
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 암호화된 문서를 열기 위한 비밀번호. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


문서의 형식 패밀리를 가져옵니다. 이는 문서 유형(예: Image, Pdf, Spreadsheet 등)을 나타냅니다.


**Returns:**
int - formatFamily 파일 유형.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


문서의 형식 패밀리를 설정합니다. 이는 문서 유형(예: Image, Pdf, Spreadsheet 등)을 나타냅니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | formatFamily | int | 파일 유형. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


파일 유형을 가져옵니다. 이는 파일 유형(예: docx, pdf, xlsx 등)을 나타냅니다.


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


파일 유형을 설정합니다. 이는 파일 유형(예: docx, pdf, xlsx 등)을 나타냅니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | 파일 유형. |
|

