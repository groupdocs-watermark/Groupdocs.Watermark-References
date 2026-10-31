---
title: "metode protect"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Melindungi dokumen dari perubahan dan menetapkan kata sandi perlindungan."
type: docs
url: /id/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Melindungi dokumen dari perubahan dan menetapkan kata sandi perlindungan.

Agar konten dokumen dapat diedit, gunakan metode yang sesuai untuk menambahkan watermark dengan parameter `WordProcessingLockType.allow_only_form_fields` atau `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Menentukan jenis perlindungan untuk dokumen. |
| password | `str` | Kata sandi untuk melindungi dokumen. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")
```

### Lihat Juga
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
