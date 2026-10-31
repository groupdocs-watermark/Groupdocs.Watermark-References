---
title: "méthode protect"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Protège le document contre les modifications et définit un mot de passe de protection."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Protège le document contre les modifications et définit un mot de passe de protection.

Pour rendre le contenu du document modifiable, utilisez la méthode appropriée d'ajout d'un filigrane avec le paramètre `WordProcessingLockType.allow_only_form_fields` ou `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Spécifie le type de protection du document. |
| password | `str` | Le mot de passe pour protéger le document. |

### Exemple

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

### Voir aussi
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
