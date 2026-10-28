---
title: "FormattedTextFragmentCollectionType"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Spécifie le nombre d'éléments qu'une collection de fragments de texte formaté peut contenir."
type: docs
weight: 28
url: /fr/java/com.groupdocs.watermark.search/formattedtextfragmentcollectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class FormattedTextFragmentCollectionType
```

Spécifie le nombre d'éléments qu'une collection de fragments de texte formaté peut contenir.

## Champs

| Champ | Description |
| --- | --- |
|  | [UnlimitedFragments](#UnlimitedFragments) | Plusieurs styles sont autorisés, la collection peut contenir un nombre illimité de fragments. |
|
|  | [SingleFragment](#SingleFragment) | Le texte complet peut être formaté avec un seul style, la collection ne peut contenir qu'un seul fragment. |
|
|  | [NoFormattedText](#NoFormattedText) | L'objet parent ne prend pas en charge le formatage du texte, la collection est toujours vide. |
|
### UnlimitedFragments {#UnlimitedFragments}
```
public static final int UnlimitedFragments
```


Plusieurs styles sont autorisés, la collection peut contenir un nombre illimité de fragments.


### SingleFragment {#SingleFragment}
```
public static final int SingleFragment
```


Le texte complet peut être formaté avec un seul style, la collection ne peut contenir qu'un seul fragment.


### NoFormattedText {#NoFormattedText}
```
public static final int NoFormattedText
```


L'objet parent ne prend pas en charge le formatage du texte, la collection est toujours vide.


