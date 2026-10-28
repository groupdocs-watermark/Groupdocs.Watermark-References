---
title: "Font"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Classe che rappresenta un font."
type: docs
weight: 11
url: /it/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Classe che rappresenta un font.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Inizializza una nuova istanza della classe `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nome di famiglia di caratteri specificato e una dimensione. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | Inizializza una nuova istanza della classe `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nome di famiglia di caratteri specificato, una dimensione e uno stile. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | Restituisce il nome della famiglia di questo `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione di questo `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getStyle()](#getStyle--) | Restituisce il `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` per questo `[Font](../../com.groupdocs.watermark.watermarks/font)`. |
|
|  | [getBold()](#getBold--) | Restituisce un valore che indica se il carattere è in grassetto. |
|
|  | [getItalic()](#getItalic--) | Restituisce un valore che indica se il carattere è in corsivo. |
|
|  | [getStrikeout()](#getStrikeout--) | Restituisce un valore che indica se il carattere specifica una linea orizzontale attraverso il carattere. |
|
|  | [getUnderline()](#getUnderline--) | Restituisce un valore che indica se il carattere è sottolineato. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Inizializza una nuova istanza della classe `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nome di famiglia di caratteri specificato e una dimensione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Il nome della famiglia di caratteri. |
|
|  | size | float | La dimensione del nuovo carattere. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


Inizializza una nuova istanza della classe `[Font](../../com.groupdocs.watermark.watermarks/font)` con un nome di famiglia di caratteri specificato, una dimensione e uno stile.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Il nome della famiglia di caratteri. |
|
|  | size | float | La dimensione del nuovo carattere. |
|
|  | style | int | Il `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` del nuovo carattere. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |
| style | [FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle) |  |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```




**Returns:**
java.lang.String
### setFolderPath(String folderPath) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String folderPath)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


Restituisce il nome della famiglia di questo `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
java.lang.String - Il nome della famiglia di questo `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getSize() {#getSize--}
```
public final float getSize()
```


Restituisce la dimensione di questo `[Font](../../com.groupdocs.watermark.watermarks/font)`.


**Returns:**
float - La dimensione di questo `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


Restituisce il `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` per questo `[Font](../../com.groupdocs.watermark.watermarks/font)`.

Il valore predefinito è `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)` (testo normale).


**Returns:**
int - Il `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` di questo `[Font](../../com.groupdocs.watermark.watermarks/font)`.

### getBold() {#getBold--}
```
public final boolean getBold()
```


Restituisce un valore che indica se il carattere è in grassetto.


**Returns:**
boolean - Vero se questo carattere è in grassetto; altrimenti, falso.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


Restituisce un valore che indica se il carattere è in corsivo.


**Returns:**
boolean - Vero se questo carattere è in corsivo; altrimenti, falso.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


Restituisce un valore che indica se il carattere specifica una linea orizzontale attraverso il carattere.


**Returns:**
boolean - Vero se questo carattere specifica una linea orizzontale attraverso il carattere; altrimenti, falso.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


Restituisce un valore che indica se il carattere è sottolineato.


**Returns:**
boolean - Vero se questo carattere è sottolineato; altrimenti, falso.

