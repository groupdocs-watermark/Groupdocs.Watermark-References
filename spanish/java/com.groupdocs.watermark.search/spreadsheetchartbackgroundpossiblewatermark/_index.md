---
title: "SpreadsheetChartBackgroundPossibleWatermark"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una posible marca de agua de imagen en el fondo de un gráfico de Excel."
type: docs
weight: 61
url: /es/java/com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public class SpreadsheetChartBackgroundPossibleWatermark extends TwoDObjectPossibleWatermark
```

Representa una posible marca de agua de imagen en el fondo de un gráfico de Excel.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SpreadsheetChartBackgroundPossibleWatermark(SpreadsheetChart chart)](#SpreadsheetChartBackgroundPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetChart-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getParent()](#getParent--) | Obtiene el padre de este `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtiene el ángulo de rotación de este `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` en grados. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Obtiene la `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### SpreadsheetChartBackgroundPossibleWatermark(SpreadsheetChart chart) {#SpreadsheetChartBackgroundPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetChart-}
```
public SpreadsheetChartBackgroundPossibleWatermark(SpreadsheetChart chart)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | [SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Obtiene el padre de este `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtiene el ángulo de rotación de este `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)` en grados.


**Returns:**
double - El valor es siempre 0 para este tipo de marca de agua posible.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Obtiene la `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)`.


**Returns:**
int - La `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de este `[SpreadsheetChartBackgroundPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetchartbackgroundpossiblewatermark)`.

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




