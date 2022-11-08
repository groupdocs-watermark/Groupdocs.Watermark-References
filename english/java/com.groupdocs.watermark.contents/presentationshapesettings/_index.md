---
title: PresentationShapeSettings
second_title: GroupDocs.Watermark for Java API Reference
description: Represents settings that can be applied to a shape watermark for a PowerPoint document.
type: docs
weight: 95
url: /java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

Represents settings that can be applied to a shape watermark for a PowerPoint document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationShapeSettings()](#PresentationShapeSettings--) | Initializes a new instance of the `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` class. |
## Fields

| Field | Description |
| --- | --- |
| [UnreadableCharacter](#UnreadableCharacter) |  |
## Methods

| Method | Description |
| --- | --- |
| [isLocked()](#isLocked--) | Gets a value indicating whether an editing of the shape in PowerPoint is forbidden. |
| [setLocked(boolean value)](#setLocked-boolean-) | Sets a value indicating whether an editing of the shape in PowerPoint is forbidden. |
| [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | Gets a value indicating whether the text watermark characters are mixed with unreadable characters. |
| [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | Sets a value indicating whether the text watermark characters are mixed with unreadable characters. |
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


Initializes a new instance of the `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` class.

### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```




### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gets a value indicating whether an editing of the shape in PowerPoint is forbidden.

**Returns:**
boolean - `true` if shape editing is forbidden, `false` if the shape can be edited in PowerPoint.
### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Sets a value indicating whether an editing of the shape in PowerPoint is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if shape editing should be forbidden, `false` if the shape can be edited in PowerPoint. |

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


Gets a value indicating whether the text watermark characters are mixed with unreadable characters.

This protection applies only when the `#isLocked().isLocked()` returns `true`.

**Returns:**
boolean - A value indicating whether the text watermark characters are mixed with unreadable characters.
### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


Sets a value indicating whether the text watermark characters are mixed with unreadable characters.

This protection applies only when the `#isLocked().isLocked()` returns `true`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating whether the text watermark characters are mixed with unreadable characters. |

