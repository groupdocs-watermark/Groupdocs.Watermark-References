---
title: "protect yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belgeyi değişikliklere karşı korur ve bir koruma şifresi belirler."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Belgeyi değişikliklere karşı korur ve bir koruma şifresi belirler.

Belgenin içeriğinin düzenlenebilir olmasını sağlamak için, `WordProcessingLockType.allow_only_form_fields` veya `WordProcessingLockType.read_only_with_editable_content` parametresiyle bir filigran eklemek için uygun yöntemi kullanın.

```python
def protect(self, protection_type, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Belge için koruma tipini belirtir. |
| password | `str` | Belgeyi korumak için şifre. |

### Örnek

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

### Ayrıca Bakınız
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
