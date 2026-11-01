---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "새 WordProcessingWatermarkPagesOptions 클래스 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

새 WordProcessingWatermarkPagesOptions 클래스 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# 특정 페이지에 워터마크를 적용하기 위한 옵션을 생성합니다.
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### 또 보기
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
