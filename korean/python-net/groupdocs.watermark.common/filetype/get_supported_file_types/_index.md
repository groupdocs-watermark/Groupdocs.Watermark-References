---
title: "get_supported_file_types 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지원되는 파일 유형을 검색합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

지원되는 파일 유형을 검색합니다.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### 예시

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # 라이브러리가 열 수 있는 모든 파일 유형을 열거하십시오
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### 또 보기
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
