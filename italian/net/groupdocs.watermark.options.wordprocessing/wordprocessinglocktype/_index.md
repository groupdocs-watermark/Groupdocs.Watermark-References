---
title: WordProcessingLockType
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Specifica il tipo di blocco filigrana nel documento Word.
type: docs
weight: 2290
url: /it/net/groupdocs.watermark.options.wordprocessing/wordprocessinglocktype/
---
## WordProcessingLockType enumeration

Specifica il tipo di blocco filigrana nel documento Word.

```csharp
public enum WordProcessingLockType
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AllowOnlyRevisions | `0` | L'utente può solo aggiungere contrassegni di revisione al documento. |
| AllowOnlyComments | `1` | L'utente può modificare solo i commenti nel documento. |
| AllowOnlyFormFields | `2` | L'utente può inserire dati solo nei campi del modulo nel documento. |
| ReadOnly | `3` | L'intero documento è di sola lettura. |
| ReadOnlyWithEditableContent | `4` | Il documento è di sola lettura, ma tutto il contenuto tranne la filigrana è contrassegnato come modificabile. |
| NoLock | `-1` | Disabilita qualsiasi blocco su filigrana e documento. |

### Guarda anche

* spazio dei nomi [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->