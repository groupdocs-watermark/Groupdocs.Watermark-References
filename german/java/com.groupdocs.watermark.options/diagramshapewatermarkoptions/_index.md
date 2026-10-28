---
title: "DiagramShapeWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Form‑Wasserzeichen zu einem Visio-Dokument hinzugefügt wird."
type: docs
weight: 14
url: /de/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Form‑Wasserzeichen zu einem Visio-Dokument hinzugefügt wird.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Das folgende Beispiel zeigt, wie man ein geschütztes Wasserzeichen zu allen Seiten des Visio-Dokuments hinzufügt.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Initialisiert eine neue Instanz der `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | Liefert einen Wert, der angibt, zu welchen Seiten ein Wasserzeichen hinzugefügt werden soll. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | Liefert oder setzt einen Wert, der angibt, zu welchen Seiten ein Wasserzeichen hinzugefügt werden soll. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Initialisiert eine neue Instanz der `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` Klasse.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Liefert einen Wert, der angibt, zu welchen Seiten ein Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, der angibt, zu welchen Seiten ein Wasserzeichen hinzugefügt werden soll.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Liefert oder setzt einen Wert, der angibt, zu welchen Seiten ein Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Der `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, der angibt, zu welchen Seiten ein Wasserzeichen hinzugefügt werden soll. |
|

