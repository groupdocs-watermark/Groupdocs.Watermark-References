---
title: "metodo protect"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Protegge il documento dalle modifiche e imposta una password di protezione."
type: docs
url: /it/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Protegge il documento dalle modifiche e imposta una password di protezione.

Per rendere il contenuto del documento modificabile, utilizza il metodo appropriato per aggiungere una filigrana con il parametro `WordProcessingLockType.allow_only_form_fields` o `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Specifica il tipo di protezione per il documento. |
| password | `str` | La password con cui proteggere il documento. |

### Esempio

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

### Vedi anche
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
