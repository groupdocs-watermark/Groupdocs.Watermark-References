---
title: "Получить поддерживаемые форматы файлов"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Перечислите все форматы файлов, поддерживаемые GroupDocs.Watermark для Python через .NET."
type: docs
url: /ru/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Быстро получите полный список форматов файлов, поддерживаемых GroupDocs.Watermark. Это позволяет вашему приложению динамически проверять совместимость перед обработкой документа — например, для проверки загруженных пользователями файлов.

## List supported file formats

`FileType.get_supported_file_types()` возвращает каждый поддерживаемый тип файла. Каждый элемент раскрывает своё `extension` и удобное описание.

{{< tabs \"code-example-get-supported-file-formats\">}}
{{< tab \"list_supported_formats.py\" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Перечислите все типы файлов, которые библиотека может открывать
    supported_file_types = FileType.get_supported_file_types()
    for file_type in sorted(supported_file_types, key=lambda x: x.extension):
        print(file_type)

if __name__ == "__main__":
    list_supported_formats()
```
{{< /tab >}}
{{< tab \"list-supported-formats.txt\" >}}
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
