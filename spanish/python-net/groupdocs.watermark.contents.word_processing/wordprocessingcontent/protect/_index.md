---
title: "método protect"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Protege el documento de cambios y establece una contraseña de protección."
type: docs
url: /es/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Protege el documento de cambios y establece una contraseña de protección.

Para que el contenido del documento sea editable, use el método apropiado de agregar una marca de agua con el parámetro `WordProcessingLockType.allow_only_form_fields` o `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Especifica el tipo de protección del documento. |
| password | `str` | La contraseña con la que proteger el documento. |

### Ejemplo

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

### Ver también
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
