---
title: "protect methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Beschermt het document tegen wijzigingen en stelt een beschermingswachtwoord in."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Beschermt het document tegen wijzigingen en stelt een beschermingswachtwoord in.

Om de inhoud van het document bewerkbaar te maken, gebruik de juiste methode om een watermerk toe te voegen met de parameter `WordProcessingLockType.allow_only_form_fields` of `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Specificeert het type bescherming voor het document. |
| password | `str` | Het wachtwoord om het document mee te beveiligen. |

### Voorbeeld

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

### Zie ook
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
