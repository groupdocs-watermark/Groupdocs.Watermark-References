---
title: "WordProcessingShapeSettings"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示可应用于 Word 文档形状水印的设置。"
type: docs
weight: 71
url: /zh/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

表示可应用于 Word 文档形状水印的设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | 初始化 `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocked()](#isLocked--) | 获取一个值，指示在 Word 中是否禁止编辑形状。 |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | 设置一个值，指示在 Word 中是否禁止编辑形状。 |
|
|  | [getLockType()](#getLockType--) | 获取水印锁定类型。 |
|
|  | [setLockType(int value)](#setLockType-int-) | 设置水印锁定类型。 |
|
|  | [getPassword()](#getPassword--) | 获取用于锁定水印的密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置用于锁定水印的密码。 |
|
|  | [getPageNumbers()](#getPageNumbers--) | 获取要添加水印的页面编号。 |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 设置要添加水印的页面编号。 |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


初始化 `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` 类的新实例。


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取一个值，指示在 Word 中是否禁止编辑形状。


**Returns:**
boolean - 如果该值为 true，则禁止编辑形状。默认情况下，该值为 false，形状可以在 Word 中编辑。

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


设置一个值，指示在 Word 中是否禁止编辑形状。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果该值为 true，则形状编辑将被禁止。默认情况下，该值为 false，形状可以在 Word 中编辑。 |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


获取水印锁定类型。


**Returns:**
int - `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` 的水印锁定类型。

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


设置水印锁定类型。

值 `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` 不能与
类型为 `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` 的对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` 的水印锁定类型。 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取用于锁定水印的密码。


**Returns:**
java.lang.String - 用于锁定水印的密码。

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置用于锁定水印的密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 用于锁定水印的密码。 |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


获取要添加水印的页面编号。


**Returns:**
int[] - 要添加水印的页面编号。

<br />

*** ** * ** ***

所有数字必须大于或等于 1。此属性仅在向文档添加水印时使用。如果该值为 null，则水印会添加到所有页面。

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


设置要添加水印的页面编号。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 要添加水印的页面编号。 |

<br />

*** ** * ** ***

所有数字必须大于或等于 1。此属性仅在向文档添加水印时使用。如果该值为 null，则水印会添加到所有页面。

<br />

|

