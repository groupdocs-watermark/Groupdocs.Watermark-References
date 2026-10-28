---
title: "PreviewOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다."
type: docs
weight: 47
url: /ko/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | 출력 스트림이 닫히도록 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 출력 스트림이 클라이언트에 반환되어 추가로 사용할 수 있도록 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 페이지 미리보기 너비를 가져옵니다. |
|
|  | [setWidth(int value)](#setWidth-int-) | 페이지 미리보기 너비를 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 페이지 미리보기 높이를 가져옵니다. |
|
|  | [setHeight(int value)](#setHeight-int-) | 페이지 미리보기 높이를 설정합니다. |
|
|  | [getPageNumbers()](#getPageNumbers--) | 미리보기를 생성할 페이지 번호 배열을 가져옵니다. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 미리보기를 생성할 페이지 번호 배열을 설정합니다. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | 미리보기 이미지 형식을 가져옵니다. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | 미리보기 이미지 형식을 설정합니다. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | 페이지 스트림 생성 클래스의 인스턴스를 가져옵니다. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | 페이지 스트림 생성 클래스의 인스턴스를 설정합니다. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | 페이지 미리보기 완료 클래스의 인스턴스를 가져옵니다. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | 페이지 미리보기 완료 클래스의 인스턴스를 설정합니다. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


출력 스트림이 닫히도록 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


출력 스트림이 클라이언트에 반환되어 추가로 사용할 수 있도록 `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 페이지 미리보기 생성이 완료되었음을 알리고 출력 스트림을 가져옵니다. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


페이지 미리보기 너비를 가져옵니다.


**Returns:**
int - 페이지 미리보기 너비.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


페이지 미리보기 너비를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 페이지 미리보기 너비. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


페이지 미리보기 높이를 가져옵니다.


**Returns:**
int - 페이지 미리보기 높이.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


페이지 미리보기 높이를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 페이지 미리보기 높이. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


미리보기를 생성할 페이지 번호 배열을 가져옵니다.


**Returns:**
int[] - 미리보기를 생성할 페이지 번호 배열.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


미리보기를 생성할 페이지 번호 배열을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int[] | 미리보기를 생성할 페이지 번호 배열. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


미리보기 이미지 형식을 가져옵니다.


**Returns:**
int - 미리보기 이미지 형식.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


미리보기 이미지 형식을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 미리보기 이미지 형식. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


페이지 스트림 생성 클래스의 인스턴스를 가져옵니다.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


페이지 스트림 생성 클래스의 인스턴스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 페이지 스트림 생성 클래스의 인스턴스. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


페이지 미리보기 완료 클래스의 인스턴스를 가져옵니다.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


페이지 미리보기 완료 클래스의 인스턴스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 페이지 미리보기 완료 대리자의 인스턴스. |
|

