---
title: "TextFormattingSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri che consentono il filtraggio per formattazione del testo."
type: docs
weight: 66
url: /it/java/com.groupdocs.watermark.search/textformattingsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria)
```
public class TextFormattingSearchCriteria extends SearchCriteria
```

Rappresenta i criteri che consentono il filtraggio per formattazione del testo.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Il seguente esempio dimostra come rimuovere eventuali filigrane con un particolare
formattazione del testo (indipendentemente dal tipo di documento).
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.doc");
>    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
>
>    criteria.setForegroundColorRange(new ColorRange());
>    criteria.getForegroundColorRange().setMinHue(-5);
>    criteria.getForegroundColorRange().setMaxHue(10);
>    criteria.getForegroundColorRange().setMinBrightness(0.01f);
>    criteria.getForegroundColorRange().setMaxBrightness(0.99f);
>    criteria.setBackgroundColorRange(new ColorRange());
>    criteria.getBackgroundColorRange().setEmpty(true);
>    criteria.setFontName("Arial");
>    criteria.setMinFontSize(19);
>    criteria.setMaxFontSize(42);
>    criteria.setFontBold(true);
>
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    watermarks.clear();
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TextFormattingSearchCriteria()](#TextFormattingSearchCriteria--) | Inizializza una nuova istanza della classe `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getForegroundColorRange()](#getForegroundColorRange--) | Ottiene l'intervallo di colori utilizzati per filtrare le filigrane per colore di primo piano del testo. |
|
|  | [setForegroundColorRange(ColorRange value)](#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Imposta l'intervallo di colori utilizzati per filtrare le filigrane per colore di primo piano del testo. |
|
|  | [getBackgroundColorRange()](#getBackgroundColorRange--) | Ottiene l'intervallo di colori utilizzati per filtrare le filigrane per colore di sfondo del testo. |
|
|  | [setBackgroundColorRange(ColorRange value)](#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-) | Imposta l'intervallo di colori utilizzati per filtrare le filigrane per colore di sfondo del testo. |
|
|  | [getFontName()](#getFontName--) | Ottiene il nome del carattere utilizzato nella possibile formattazione del testo della filigrana. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Imposta il nome del carattere utilizzato nella possibile formattazione del testo della filigrana. |
|
|  | [getMinFontSize()](#getMinFontSize--) | Ottiene il valore iniziale della dimensione del carattere. |
|
|  | [setMinFontSize(float value)](#setMinFontSize-float-) | Imposta il valore iniziale della dimensione del carattere. |
|
|  | [getMaxFontSize()](#getMaxFontSize--) | Ottiene il valore finale della dimensione del carattere. |
|
|  | [setMaxFontSize(float value)](#setMaxFontSize-float-) | Imposta il valore finale della dimensione del carattere. |
|
|  | [getFontBold()](#getFontBold--) | Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in grassetto. |
|
|  | [setFontBold(Boolean value)](#setFontBold-java.lang.Boolean-) | Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in grassetto. |
|
|  | [getFontItalic()](#getFontItalic--) | Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in corsivo. |
|
|  | [setFontItalic(Boolean value)](#setFontItalic-java.lang.Boolean-) | Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in corsivo. |
|
|  | [getFontUnderline()](#getFontUnderline--) | Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è sottolineato. |
|
|  | [setFontUnderline(Boolean value)](#setFontUnderline-java.lang.Boolean-) | Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è sottolineato. |
|
|  | [getFontStrikeout()](#getFontStrikeout--) | Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è barrato. |
|
|  | [setFontStrikeout(Boolean value)](#setFontStrikeout-java.lang.Boolean-) | Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è barrato. |
|
| [isSatisfiedBy(PossibleWatermark candidate)](#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-) |  |
| [accept(ICriteriaVisitor visitor)](#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-) |  |
### TextFormattingSearchCriteria() {#TextFormattingSearchCriteria--}
```
public TextFormattingSearchCriteria()
```


Inizializza una nuova istanza della classe `[TextFormattingSearchCriteria](../../com.groupdocs.watermark.search/textformattingsearchcriteria)`.


### getForegroundColorRange() {#getForegroundColorRange--}
```
public final ColorRange getForegroundColorRange()
```


Ottiene l'intervallo di colori utilizzati per filtrare le filigrane per colore di primo piano del testo.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text foreground color.

### setForegroundColorRange(ColorRange value) {#setForegroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setForegroundColorRange(ColorRange value)
```


Imposta l'intervallo di colori utilizzati per filtrare le filigrane per colore di primo piano del testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | L'intervallo di colori utilizzati per filtrare le filigrane per colore di primo piano del testo. |
|

### getBackgroundColorRange() {#getBackgroundColorRange--}
```
public final ColorRange getBackgroundColorRange()
```


Ottiene l'intervallo di colori utilizzati per filtrare le filigrane per colore di sfondo del testo.


**Returns:**
[ColorRange](../../com.groupdocs.watermark.search/colorrange) - The range of colors which are used to filter watermarks by text background color.

### setBackgroundColorRange(ColorRange value) {#setBackgroundColorRange-com.groupdocs.watermark.search.ColorRange-}
```
public final void setBackgroundColorRange(ColorRange value)
```


Imposta l'intervallo di colori utilizzati per filtrare le filigrane per colore di sfondo del testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ColorRange](../../com.groupdocs.watermark.search/colorrange) | L'intervallo di colori utilizzati per filtrare le filigrane per colore di sfondo del testo. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Ottiene il nome del carattere utilizzato nella possibile formattazione del testo della filigrana.


**Returns:**
java.lang.String - Il valore predefinito è null, il che significa che il filtro non è applicato.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Imposta il nome del carattere utilizzato nella possibile formattazione del testo della filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il valore predefinito è null, il che significa che il filtro non è applicato. |
|

### getMinFontSize() {#getMinFontSize--}
```
public final float getMinFontSize()
```


Ottiene il valore iniziale della dimensione del carattere.


**Returns:**
float - Il valore iniziale della dimensione del carattere.

### setMinFontSize(float value) {#setMinFontSize-float-}
```
public final void setMinFontSize(float value)
```


Imposta il valore iniziale della dimensione del carattere.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | Il valore iniziale della dimensione del carattere. |
|

### getMaxFontSize() {#getMaxFontSize--}
```
public final float getMaxFontSize()
```


Ottiene il valore finale della dimensione del carattere.


**Returns:**
float - Il valore finale della dimensione del carattere.

### setMaxFontSize(float value) {#setMaxFontSize-float-}
```
public final void setMaxFontSize(float value)
```


Imposta il valore finale della dimensione del carattere.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | Il valore finale della dimensione del carattere. |
|

### getFontBold() {#getFontBold--}
```
public final Boolean getFontBold()
```


Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in grassetto.


**Returns:**
java.lang.Boolean - Il valore predefinito è null, il che significa che il filtro non è applicato.

### setFontBold(Boolean value) {#setFontBold-java.lang.Boolean-}
```
public final void setFontBold(Boolean value)
```


Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in grassetto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.Boolean | Il valore predefinito è null, il che significa che il filtro non è applicato. |
|

### getFontItalic() {#getFontItalic--}
```
public final Boolean getFontItalic()
```


Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in corsivo.


**Returns:**
java.lang.Boolean - Il valore predefinito è null, il che significa che il filtro non è applicato.

### setFontItalic(Boolean value) {#setFontItalic-java.lang.Boolean-}
```
public final void setFontItalic(Boolean value)
```


Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è in corsivo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.Boolean | Il valore predefinito è null, il che significa che il filtro non è applicato. |
|

### getFontUnderline() {#getFontUnderline--}
```
public final Boolean getFontUnderline()
```


Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è sottolineato.


**Returns:**
java.lang.Boolean - Il valore predefinito è null, il che significa che il filtro non è applicato.

### setFontUnderline(Boolean value) {#setFontUnderline-java.lang.Boolean-}
```
public final void setFontUnderline(Boolean value)
```


Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è sottolineato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.Boolean | Il valore predefinito è null, il che significa che il filtro non è applicato. |
|

### getFontStrikeout() {#getFontStrikeout--}
```
public final Boolean getFontStrikeout()
```


Ottiene un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è barrato.


**Returns:**
java.lang.Boolean - Il valore predefinito è null, il che significa che il filtro non è applicato.

### setFontStrikeout(Boolean value) {#setFontStrikeout-java.lang.Boolean-}
```
public final void setFontStrikeout(Boolean value)
```


Imposta un valore che indica se il carattere utilizzato nella formattazione del testo della filigrana è barrato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.Boolean | Il valore predefinito è null, il che significa che il filtro non è applicato. |
|

### isSatisfiedBy(PossibleWatermark candidate) {#isSatisfiedBy-com.groupdocs.watermark.search.PossibleWatermark-}
```
public boolean isSatisfiedBy(PossibleWatermark candidate)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| candidate | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) |  |

**Returns:**
boolean
### accept(ICriteriaVisitor visitor) {#accept-com.groupdocs.watermark.internal.ICriteriaVisitor-}
```
public void accept(ICriteriaVisitor visitor)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| visitor | [ICriteriaVisitor](../../com.groupdocs.watermark.internal/icriteriavisitor) |  |

