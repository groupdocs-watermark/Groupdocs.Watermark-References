---
title: SizingType
second_title: GroupDocs.Watermark for Java API Reference
description: Specifies how watermark size should be calculated.
type: docs
weight: 16
url: /java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Specifies how watermark size should be calculated.
## Fields

| Field | Description |
| --- | --- |
| [Auto](#Auto) | Watermark should be sized automatically according to its content. |
| [Absolute](#Absolute) | Watermark should be sized to an exact `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` and `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`. |
| [ScaleToParentDimensions](#ScaleToParentDimensions) | Watermark should be scaled relative to parent dimensions using specified `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`. |
| [ScaleToParentArea](#ScaleToParentArea) | Watermark should be scaled relative to parent area using specified `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`. |
## Methods

| Method | Description |
| --- | --- |
| [toString(int value)](#toString-int-) | Returns a string representation of the `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` value. |
| [parse(String value)](#parse-java.lang.String-) | Parses a string to a `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` enumeration value. |
### Auto {#Auto}
```
public static final int Auto
```


Watermark should be sized automatically according to its content.

### Absolute {#Absolute}
```
public static final int Absolute
```


Watermark should be sized to an exact `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` and `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.

### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Watermark should be scaled relative to parent dimensions using specified `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.

### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Watermark should be scaled relative to parent area using specified `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.

### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Returns a string representation of the `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value to convert. |

**Returns:**
java.lang.String - The string representation of the `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` value.
### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Parses a string to a `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` enumeration value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The string to parse. |

**Returns:**
int - The `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` enumeration value.
