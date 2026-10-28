---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Form‑Wasserzeichen zu einer bestimmten Seite eines Visio-Dokuments hinzugefügt wird."
type: docs
weight: 11
url: /de/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Form‑Wasserzeichen zu einer bestimmten Seite eines Visio-Dokuments hinzugefügt wird.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

Das folgende Beispiel zeigt, wie man ein geschütztes Wasserzeichen auf die erste Seite eines Visio-Dokuments hinzufügt.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
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
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Initialisiert eine neue Instanz der `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ermittelt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Initialisiert eine neue Instanz der `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` Klasse.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Ermittelt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |
|

