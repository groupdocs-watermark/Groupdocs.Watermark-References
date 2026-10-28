---
title: "PresentationPreviewOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "프레젠테이션 문서 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

프레젠테이션 문서 미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 클래스의 새 인스턴스를 초기화하면 출력 스트림이 닫힙니다. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 클래스의 새 인스턴스를 초기화하면 출력 스트림이 클라이언트에 반환되어 추가로 사용할 수 있습니다. |
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
|  | [setResolution(long value)](#setResolution-long-) | 생성된 이미지의 해상도를 인치당 도트 수로 설정합니다. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


`[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 클래스의 새 인스턴스를 초기화하면 출력 스트림이 닫힙니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


`[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` 클래스의 새 인스턴스를 초기화하면 출력 스트림이 클라이언트에 반환되어 추가로 사용할 수 있습니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | 페이지 미리보기 생성이 완료되었음을 알리고 출력 스트림을 가져옵니다. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


기본 해상도(인치당 도트 수).


### getResolution() {#getResolution--}
```
public final long getResolution()
```


생성된 이미지의 해상도를 인치당 도트 수로 가져옵니다.


**Returns:**
long - 생성된 이미지의 해상도, 인치당 도트 수.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


생성된 이미지의 해상도를 인치당 도트 수로 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | long | 생성된 이미지의 해상도, 인치당 도트 수. |
|

