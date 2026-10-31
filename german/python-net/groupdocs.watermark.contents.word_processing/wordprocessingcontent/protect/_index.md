---
title: "protect-Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Schützt das Dokument vor Änderungen und legt ein Schutzkennwort fest."
type: docs
url: /de/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Schützt das Dokument vor Änderungen und legt ein Schutzkennwort fest.

Um den Inhalt des Dokuments editierbar zu machen, verwenden Sie die passende Methode zum Hinzufügen eines Wasserzeichens mit dem Parameter `WordProcessingLockType.allow_only_form_fields` oder `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Gibt den Schutztyp für das Dokument an. |
| password | `str` | Das Passwort, mit dem das Dokument geschützt wird. |

### Beispiel

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

### Siehe auch
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
