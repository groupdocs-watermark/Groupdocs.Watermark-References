---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "WatermarkResult 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

새 [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/) 클래스 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

특정 값으로 새 WatermarkResult 인스턴스를 초기화합니다.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_document_size | `int` | 원본 문서의 크기(바이트)입니다. |
| processing_time | `timedelta` | 처리 시간(밀리초 단위). |
| final_document_size | `int` | 최종 처리된 문서의 크기(바이트)입니다. |
| number_watermarks_applied | `int` | 문서에 적용된 워터마크 총 수입니다. |

### 또 보기
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
