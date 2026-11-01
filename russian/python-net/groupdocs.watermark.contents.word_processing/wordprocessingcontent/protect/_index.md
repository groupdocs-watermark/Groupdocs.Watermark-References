---
title: "Метод protect"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Защищает документ от изменений и задает пароль защиты."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Защищает документ от изменений и задает пароль защиты.

Чтобы содержимое документа было редактируемым, используйте соответствующий метод добавления водяного знака с параметром `WordProcessingLockType.allow_only_form_fields` или `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Указывает тип защиты документа. |
| password | `str` | Пароль для защиты документа. |

### Пример

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

### См. также
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
