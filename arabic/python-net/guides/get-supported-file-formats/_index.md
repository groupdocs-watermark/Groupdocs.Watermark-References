---
title: "احصل على صيغ الملفات المدعومة"
linkTitle: "Get supported file formats"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "قائمة بجميع صيغ الملفات المدعومة من قبل GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


استرجع بسرعة القائمة الكاملة لصيغ الملفات المدعومة من قبل GroupDocs.Watermark. يتيح ذلك لتطبيقك التحقق من التوافق ديناميكياً قبل معالجة المستند — على سبيل المثال، للتحقق من صحة الملفات التي يرفعها المستخدم.

## List supported file formats

`FileType.get_supported_file_types()` تُرجع كل نوع ملف مدعوم. كل عنصر يُظهر امتداده `extension` ووصفًا ودودًا.

{{< tabs \"code-example-get-supported-file-formats\">}}
{{< tab \"list_supported_formats.py\" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # عدد جميع أنواع الملفات التي يمكن للمكتبة فتحها
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
