---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Optionen dar, wenn das Wasserzeichen zu einem Kopf- bzw. Fußzeilenbereich eines Word-Abschnitts hinzugefügt wird."
type: docs
weight: 74
url: /de/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Stellt Optionen dar, wenn das Wasserzeichen zu einem Kopf- bzw. Fußzeilenbereich eines Word-Abschnitts hinzugefügt wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Initialisiert eine neue Instanz der `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Ermittelt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Setzt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Ermittelt den Wert, der den Typ von Kopf- oder Fußzeile identifiziert, zu dem das Wasserzeichen hinzugefügt werden soll. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Legt den Wert fest, der den Typ von Kopf- oder Fußzeile identifiziert, zu der das Wasserzeichen hinzugefügt werden soll. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Initialisiert eine neue Instanz der `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` Klasse.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Ermittelt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Setzt den Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Index eines Abschnitts, zu dem das Wasserzeichen hinzugefügt werden soll. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Ermittelt den Wert, der den Typ von Kopf- oder Fußzeile identifiziert, zu dem das Wasserzeichen hinzugefügt werden soll.


**Returns:**
int - Der Wert des Typs `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)`, der den Typ von Kopf- oder Fußzeile identifiziert, zu der das Wasserzeichen hinzugefügt werden soll.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Legt den Wert fest, der den Typ von Kopf- oder Fußzeile identifiziert, zu der das Wasserzeichen hinzugefügt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Der Wert des Typs `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)`, der den Typ von Kopf- oder Fußzeile identifiziert, zu der das Wasserzeichen hinzugefügt werden soll. |
|

