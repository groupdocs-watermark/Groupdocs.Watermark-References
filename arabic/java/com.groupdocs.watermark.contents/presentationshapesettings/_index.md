---
title: "PresentationShapeSettings"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل الإعدادات التي يمكن تطبيقها على علامة مائية للشكل في مستند PowerPoint."
type: docs
weight: 95
url: /ar/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

يمثل الإعدادات التي يمكن تطبيقها على علامة مائية للشكل في مستند PowerPoint.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | ينشئ مثيلاً جديداً لفئة `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLocked()](#isLocked--) | يحصل على قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | يضبط قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | يحصل على قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | يضبط قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


ينشئ مثيلاً جديداً لفئة `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)`.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


يحصل على قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا.


**Returns:**
منطقي - `true` إذا كان تحرير الشكل ممنوعًا، `false` إذا كان يمكن تحرير الشكل في PowerPoint.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظورًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | `true` إذا كان يجب منع تحرير الشكل، `false` إذا كان يمكن تحرير الشكل في PowerPoint. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


يحصل على قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة.

يطبق هذا الحماية فقط عندما تُعيد الدالة `#isLocked().isLocked()` القيمة `true`.


**Returns:**
boolean - قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة.

يطبق هذا الحماية فقط عندما تُعيد الدالة `#isLocked().isLocked()` القيمة `true`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |
|

