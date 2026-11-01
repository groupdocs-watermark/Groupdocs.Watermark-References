---
title: "지원되는 파일 형식 가져오기"
linkTitle: "Get supported file formats"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "GroupDocs.Watermark for Python via .NET가 지원하는 모든 파일 형식을 나열합니다."
type: docs
url: /ko/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


GroupDocs.Watermark가 지원하는 전체 파일 형식 목록을 빠르게 가져옵니다. 이를 통해 애플리케이션은 문서를 처리하기 전에 동적으로 호환성을 확인할 수 있습니다 — 예를 들어, 사용자가 업로드한 파일을 검증하는 경우.

## List supported file formats

`FileType.get_supported_file_types()`는 지원되는 모든 파일 유형을 반환합니다. 각 항목은 `extension`과 친절한 설명을 제공합니다.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
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
{{< /tab >}}
{{< tab "list-supported-formats.txt" >}}
```text
Bmp (.bmp) - Image
Doc (.doc) - WordProcessing
Docm (.docm) - WordProcessing
Docx (.docx) - WordProcessing
Dot (.dot) - WordProcessing
Dotm (.dotm) - WordProcessing
Dotx (.dotx) - WordProcessing
Eml (.eml) - Email
Emlx (.emlx) - Email
Gif (.gif) - Image
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-supported-file-formats/list_supported_formats/list-supported-formats.txt)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Build flexible applications that validate user-uploaded files and tell the user whether watermarking is supported.
