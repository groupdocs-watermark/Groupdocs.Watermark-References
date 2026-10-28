---
title: "FormattedTextFragmentCollectionType"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Specifica il numero di elementi che una collezione di frammenti di testo formattato può contenere."
type: docs
weight: 28
url: /it/java/com.groupdocs.watermark.search/formattedtextfragmentcollectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class FormattedTextFragmentCollectionType
```

Specifica il numero di elementi che una collezione di frammenti di testo formattato può contenere.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [UnlimitedFragments](#UnlimitedFragments) | Sono consentiti più stili, la collezione può contenere un numero illimitato di frammenti. |
|
|  | [SingleFragment](#SingleFragment) | L'intero testo può essere formattato con un unico stile, la collezione può contenere solo un frammento. |
|
|  | [NoFormattedText](#NoFormattedText) | L'oggetto genitore non supporta la formattazione del testo, la collezione è sempre vuota. |
|
### UnlimitedFragments {#UnlimitedFragments}
```
public static final int UnlimitedFragments
```


Sono consentiti più stili, la collezione può contenere un numero illimitato di frammenti.


### SingleFragment {#SingleFragment}
```
public static final int SingleFragment
```


L'intero testo può essere formattato con un unico stile, la collezione può contenere solo un frammento.


### NoFormattedText {#NoFormattedText}
```
public static final int NoFormattedText
```


L'oggetto genitore non supporta la formattazione del testo, la collezione è sempre vuota.


