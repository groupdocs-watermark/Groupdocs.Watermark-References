---
title: "create_page_stream 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "각 렌더링된 페이지에 대한 쓰기 가능한 스트림을 얻기 위해 사용되는 페이지 스트림 생성 대리자입니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

각 렌더링된 페이지에 대한 쓰기 가능한 스트림을 얻기 위해 사용되는 페이지 스트림 생성 대리자입니다.

GroupDocs.Watermark는 문서 페이지를 이미지로 렌더링합니다. 페이지 번호(`int`)를 받아 쓰기 가능한 `io.RawIOBase` 스트림을 반환하는 호출 가능한 객체를 제공하십시오; 라이브러리는 렌더링된 이미지를 스트림에 쓰고 스트림을 닫습니다.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### 또 보기
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
