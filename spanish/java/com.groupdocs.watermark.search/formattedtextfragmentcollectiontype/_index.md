---
title: "FormattedTextFragmentCollectionType"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Especifica el número de elementos que una colección de fragmentos de texto con formato puede contener."
type: docs
weight: 28
url: /es/java/com.groupdocs.watermark.search/formattedtextfragmentcollectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class FormattedTextFragmentCollectionType
```

Especifica el número de elementos que una colección de fragmentos de texto con formato puede contener.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [UnlimitedFragments](#UnlimitedFragments) | Se permiten varios estilos, la colección puede contener un número ilimitado de fragmentos. |
|
|  | [SingleFragment](#SingleFragment) | Todo el texto puede formatearse con un solo estilo, la colección solo puede contener un fragmento. |
|
|  | [NoFormattedText](#NoFormattedText) | El objeto padre no admite formato de texto, la colección siempre está vacía. |
|
### UnlimitedFragments {#UnlimitedFragments}
```
public static final int UnlimitedFragments
```


Se permiten varios estilos, la colección puede contener un número ilimitado de fragmentos.


### SingleFragment {#SingleFragment}
```
public static final int SingleFragment
```


Todo el texto puede formatearse con un solo estilo, la colección solo puede contener un fragmento.


### NoFormattedText {#NoFormattedText}
```
public static final int NoFormattedText
```


El objeto padre no admite formato de texto, la colección siempre está vacía.


