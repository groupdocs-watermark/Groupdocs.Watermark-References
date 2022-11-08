---
title: FormattedTextFragmentCollectionType
second_title: GroupDocs.Watermark for Java API Reference
description: Specifies the number of elements a formatted text fragment collection can contain.
type: docs
weight: 28
url: /java/com.groupdocs.watermark.search/formattedtextfragmentcollectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class FormattedTextFragmentCollectionType
```

Specifies the number of elements a formatted text fragment collection can contain.
## Fields

| Field | Description |
| --- | --- |
| [UnlimitedFragments](#UnlimitedFragments) | Multiple styles are allowed, the collection can contain unlimited count of fragments. |
| [SingleFragment](#SingleFragment) | Whole text can be formatted with a single style, the collection can contain only one fragment. |
| [NoFormattedText](#NoFormattedText) | Parent object doesn't support text formatting, the collection is always empty. |
### UnlimitedFragments {#UnlimitedFragments}
```
public static final int UnlimitedFragments
```


Multiple styles are allowed, the collection can contain unlimited count of fragments.

### SingleFragment {#SingleFragment}
```
public static final int SingleFragment
```


Whole text can be formatted with a single style, the collection can contain only one fragment.

### NoFormattedText {#NoFormattedText}
```
public static final int NoFormattedText
```


Parent object doesn't support text formatting, the collection is always empty.

