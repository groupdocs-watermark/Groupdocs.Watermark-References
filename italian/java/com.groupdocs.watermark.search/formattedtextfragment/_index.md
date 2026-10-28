---
title: "FormattedTextFragment"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce una classe base astratta per un frammento di testo formattato in un contenuto."
type: docs
weight: 26
url: /it/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

Fornisce una classe base astratta per un frammento di testo formattato in un contenuto.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getText()](#getText--) | Ottiene il testo del frammento. |
|
|  | [getFont()](#getFont--) | Ottiene il carattere del testo. |
|
|  | [getForegroundColor()](#getForegroundColor--) | Ottiene il colore di primo piano del testo. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Ottiene il colore di sfondo del testo. |
|
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


Ottiene il testo del frammento.


**Returns:**
java.lang.String - Il testo del frammento.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


Ottiene il carattere del testo.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


Ottiene il colore di primo piano del testo.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


Ottiene il colore di sfondo del testo.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

