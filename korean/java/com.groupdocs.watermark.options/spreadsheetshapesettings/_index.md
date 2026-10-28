---
title: "SpreadsheetShapeSettings"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 도형 워터마크에 적용할 수 있는 설정을 나타냅니다."
type: docs
weight: 54
url: /ko/java/com.groupdocs.watermark.options/spreadsheetshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class SpreadsheetShapeSettings extends OfficeShapeSettings
```

Excel 문서의 도형 워터마크에 적용할 수 있는 설정을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetShapeSettings()](#SpreadsheetShapeSettings--) | `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLocked()](#isLocked--) | Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 설정합니다. |
|
### SpreadsheetShapeSettings() {#SpreadsheetShapeSettings--}
```
public SpreadsheetShapeSettings()
```


`[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` 클래스의 새 인스턴스를 초기화합니다.


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, 도형은 Excel에서 편집할 수 있습니다.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, 도형은 Excel에서 편집할 수 있습니다. |
|

