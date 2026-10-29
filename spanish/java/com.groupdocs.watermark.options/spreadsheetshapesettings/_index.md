---
title: "SpreadsheetShapeSettings"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa configuraciones que pueden aplicarse a una marca de agua de forma para un documento de Excel."
type: docs
weight: 54
url: /es/java/com.groupdocs.watermark.options/spreadsheetshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class SpreadsheetShapeSettings extends OfficeShapeSettings
```

Representa configuraciones que pueden aplicarse a una marca de agua de forma para un documento de Excel.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetShapeSettings()](#SpreadsheetShapeSettings--) | Inicializa una nueva instancia de la clase `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtiene un valor que indica si la edición de la forma en Excel está prohibida. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Establece un valor que indica si la edición de la forma en Excel está prohibida. |
|
### SpreadsheetShapeSettings() {#SpreadsheetShapeSettings--}
```
public SpreadsheetShapeSettings()
```


Inicializa una nueva instancia de la clase `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)`.


### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtiene un valor que indica si la edición de la forma en Excel está prohibida.


**Returns:**
boolean - Si el valor es verdadero, la edición de la forma estará prohibida. Por defecto, el valor es falso, la forma puede editarse en Excel.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Establece un valor que indica si la edición de la forma en Excel está prohibida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Si el valor es verdadero, la edición de la forma estará prohibida. Por defecto, el valor es falso, la forma puede editarse en Excel. |
|

