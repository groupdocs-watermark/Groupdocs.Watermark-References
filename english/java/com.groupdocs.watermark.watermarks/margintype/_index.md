---
title: MarginType
second_title: GroupDocs.Watermark for Java API Reference
description: Specifies how margin values should be interpreted.
type: docs
weight: 14
url: /java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Specifies how margin values should be interpreted.
## Fields

| Field | Description |
| --- | --- |
| [Absolute](#Absolute) | Margin value measured in content units. |
| [RelativeToParentDimensions](#RelativeToParentDimensions) | Margin value should be interpreted as a portion of appropriate parent dimension. |
| [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Margin value should be interpreted as a portion of parent minimum dimension. |
## Methods

| Method | Description |
| --- | --- |
| [toString(int value)](#toString-int-) | Returns a string representation of the `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` value. |
| [parse(String value)](#parse-java.lang.String-) | Parses a string to a `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumeration value. |
### Absolute {#Absolute}
```
public static final int Absolute
```


Margin value measured in content units.

### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Margin value should be interpreted as a portion of appropriate parent dimension.

Left and right margins are relative to parent width, top and bottom margins are relative to parent height. If this type is chosen, margin value must be between 0.0 and 1.0.

### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Margin value should be interpreted as a portion of parent minimum dimension.

If this type is chosen, margin value must be between 0.0 and 1.0.

### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Returns a string representation of the `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value to convert. |

**Returns:**
java.lang.String - The string representation of the `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` value.
### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Parses a string to a `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumeration value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The string to parse. |

**Returns:**
int - The `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumeration value.
