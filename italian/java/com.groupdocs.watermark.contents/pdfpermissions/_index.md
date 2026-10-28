---
title: "PdfPermissions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i permessi degli utenti per un documento pdf."
type: docs
weight: 68
url: /it/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Rappresenta i permessi dell'utente per un documento PDF.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Stampa il contenuto. |
|
|  | [ModifyContent](#ModifyContent) | Modifica il contenuto. |
|
|  | [ExtractContent](#ExtractContent) | Copia o estrai in altro modo testo e grafica dal documento. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Aggiungi o modifica le annotazioni di testo. |
|
|  | [FillForm](#FillForm) | Compila i campi di modulo interattivi esistenti. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Estrai testo e grafica. |
|
|  | [AssembleDocument](#AssembleDocument) | Assembla il contenuto. |
|
|  | [PrintingQuality](#PrintingQuality) | Stampa il contenuto in una rappresentazione da cui può essere generata una copia digitale fedele del documento PDF. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Stampa il contenuto.

Gestori di sicurezza della revisione 2: Stampa il contenuto.

Gestori di sicurezza della revisione 3 o successive: Stampa il contenuto
(potenzialmente non al livello di qualità più alto, a seconda se
`#PrintingQuality.PrintingQuality` è anche impostato).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Modifica il contenuto.

Modifica i contenuti del documento mediante operazioni diverse
da quelle controllate da `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Copia o estrai in altro modo testo e grafica dal documento.

Gestori di sicurezza della revisione 2: Copia o estrai in altro modo testo e grafica dal contenuto,
inclusa l'estrazione di testo e grafica (a supporto dell'accessibilità per gli utenti con
disabilità o per altri scopi).

Gestori di sicurezza della revisione 3 o successive: Copia o estrai in altro modo testo e grafica da
il contenuto mediante operazioni diverse da quelle controllate da
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Aggiungi o modifica le annotazioni di testo.

Aggiungi o modifica le annotazioni di testo, compila i campi di modulo interattivi,
e, se `#ModifyContent.ModifyContent` è anche impostato,
creare o modificare campi modulo interattivi (inclusi i campi firma).


### FillForm {#FillForm}
```
public static final int FillForm
```


Compila i campi di modulo interattivi esistenti.

Gestori di sicurezza della revisione 3 o successive: Compilare i campi modulo interattivi esistenti
(inclusi i campi firma), anche se `#ModifyTextAnnotations.ModifyTextAnnotations` è disattivato.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Estrai testo e grafica.

Gestori di sicurezza della revisione 3 o successive: Estrarre testo e grafica
(a supporto dell'accessibilità per utenti con disabilità o per altri scopi).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Assembla il contenuto.

Gestori di sicurezza della revisione 3 o successive: Assemblare il contenuto (inserire, ruotare o eliminare pagine
e creare segnalibri o immagini in miniatura), anche se `#ModifyContent.ModifyContent` è disattivato.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Stampa il contenuto in una rappresentazione da cui può essere generata una copia digitale fedele del documento PDF.

Gestori di sicurezza della revisione 3 o successive: Stampare il contenuto in una rappresentazione da cui una fedele
copia digitale del documento PDF potrebbe essere generata. Quando questo bit è disattivato (e `#PrintDocument.PrintDocument`
è impostato), la stampa è limitata a una rappresentazione a basso livello dell'aspetto, possibilmente di qualità ridotta.


