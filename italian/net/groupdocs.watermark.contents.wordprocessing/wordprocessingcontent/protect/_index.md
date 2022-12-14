---
title: Protect
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Protegge il documento dalle modifiche e imposta una password di protezione.
type: docs
weight: 50
url: /it/net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/protect/
---
## WordProcessingContent.Protect method

Protegge il documento dalle modifiche e imposta una password di protezione.

```csharp
public void Protect(WordProcessingProtectionType protectionType, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| protectionType | WordProcessingProtectionType | Specifica il tipo di protezione per il documento. |
| password | String | La password con cui proteggere il documento. |

### Osservazioni

Per rendere modificabile il contenuto del documento, utilizzare un metodo appropriato per aggiungere filigrana con AllowOnlyFormFields o ReadOnlyWithEditableContent parametro.

### Guarda anche

* enum [WordProcessingProtectionType](../../wordprocessingprotectiontype)
* class [WordProcessingContent](../../wordprocessingcontent)
* spazio dei nomi [GroupDocs.Watermark.Contents.WordProcessing](../../wordprocessingcontent)
* assemblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
