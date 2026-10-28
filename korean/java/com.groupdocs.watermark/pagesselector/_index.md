---
title: "PagesSelector"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: 
type: docs
weight: 10
url: /ko/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | 지정된 설정에 따라 페이지 목록을 가져옵니다. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | 지정된 기준에 따라 선택된 페이지 목록을 가져옵니다. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


지정된 설정에 따라 페이지 목록을 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | allPages | boolean | 모든 페이지를 포함할지 여부. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | 페이지 설정 구성입니다. |
|
|  | totalPages | int | 전체 페이지 수입니다. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | 특정 페이지 인덱스(0부터 시작)입니다. |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - 지정된 설정에 따른 페이지 목록입니다.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


지정된 기준에 따라 선택된 페이지 목록을 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | allPages | boolean | 모든 페이지를 포함할지 여부를 나타내는 플래그입니다. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | 페이지에 대한 설정 구성입니다. |
|
|  | totalPages | int | 문서의 전체 페이지 수입니다. |
|
|  | pageNumbers | int[] | 포함할 특정 페이지 번호 배열입니다. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - 정렬되고 중복 없는 선택된 페이지 번호 목록입니다.

