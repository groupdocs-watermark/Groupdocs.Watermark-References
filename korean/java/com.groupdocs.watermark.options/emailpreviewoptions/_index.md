---
title: "EmailPreviewOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이메일 문서 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

이메일 문서 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` 클래스의 새 인스턴스를 초기화하고 출력 스트림을 닫습니다. |
|
|  | [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` 클래스의 새 인스턴스를 초기화하고 출력 스트림을 클라이언트에 반환하여 추가로 사용할 수 있게 합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | 기본 해상도(인치당 도트 수). |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getResolution()](#getResolution--) | 생성된 이미지의 해상도를 인치당 도트 수로 가져옵니다. |
|
|  | [setResolution(float value)](#setResolution-float-) | 생성된 이미지의 해상도를 인치당 도트 수로 설정합니다. |
|
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


`[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` 클래스의 새 인스턴스를 초기화하고 출력 스트림을 닫습니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


`[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` 클래스의 새 인스턴스를 초기화하고 출력 스트림을 클라이언트에 반환하여 추가로 사용할 수 있게 합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 페이지 미리보기 생성이 완료되었음을 알리고 출력 스트림을 가져옵니다. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


기본 해상도(인치당 도트 수).


### getResolution() {#getResolution--}
```
public final float getResolution()
```


생성된 이미지의 해상도를 인치당 도트 수로 가져옵니다.


**Returns:**
float - 생성된 이미지의 해상도(인치당 도트 수)입니다.

<br />

*** ** * ** ***

기본값은 96입니다.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


생성된 이미지의 해상도를 인치당 도트 수로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | float | 생성된 이미지의 해상도, 인치당 도트 수. |

<br />

*** ** * ** ***

기본값은 96입니다.

<br />

|

