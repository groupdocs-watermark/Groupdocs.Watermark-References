---
title: "PresentationFormattedTextFragment"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un frammento di testo formattato in un documento PowerPoint."
type: docs
weight: 82
url: /it/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

Rappresenta un frammento di testo formattato in un documento PowerPoint.

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
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Ottiene il collegamento ipertestuale associato al testo. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Imposta il collegamento ipertestuale associato al testo. |
|
### getText() {#getText--}
```
public String getText()
```


Ottiene il testo del frammento.


**Returns:**
java.lang.String - Il testo del frammento.

### getFont() {#getFont--}
```
public Font getFont()
```


Ottiene il carattere del testo.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Ottiene il colore di primo piano del testo.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ottiene il colore di sfondo del testo.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Ottiene il collegamento ipertestuale associato al testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | actionType | int | L'azione che attiva il collegamento ipertestuale. |
|

**Returns:**
java.lang.String - L'URL del collegamento ipertestuale che viene attivato sull'azione specificata.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Imposta il collegamento ipertestuale associato al testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | actionType | int | L'azione che attiva il collegamento ipertestuale. |
|
|  | URL | java.lang.String | L'URL del collegamento ipertestuale. |
|

