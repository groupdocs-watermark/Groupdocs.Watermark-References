---
title: "protect-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Skyddar dokumentet från ändringar och sätter ett skyddslösenord."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Skyddar dokumentet från ändringar och sätter ett skyddslösenord.

För att göra dokumentets innehåll redigerbart, använd lämplig metod för att lägga till ett vattenmärke med parametern `WordProcessingLockType.allow_only_form_fields` eller `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Anger skyddstypen för dokumentet. |
| password | `str` | Lösenordet för att skydda dokumentet med. |

### Exempel

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

### Se även
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
