---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Geeft de rechten van gebruikers weer voor een pdf-document."
type: docs
weight: 68
url: /nl/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Stelt de rechten van de gebruiker voor een pdf-document voor.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Print de inhoud. |
|
|  | [ModifyContent](#ModifyContent) | Wijzig de inhoud. |
|
|  | [ExtractContent](#ExtractContent) | Kopieer of haal op andere wijze tekst en afbeeldingen uit het document. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Voeg tekstannotaties toe of wijzig ze. |
|
|  | [FillForm](#FillForm) | Vul bestaande interactieve formuliervelden in. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Haal tekst en afbeeldingen op. |
|
|  | [AssembleDocument](#AssembleDocument) | Stel de inhoud samen. |
|
|  | [PrintingQuality](#PrintingQuality) | Print de inhoud naar een representatie waaruit een getrouwe digitale kopie van het PDF-document kan worden gegenereerd. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Print de inhoud.

Beveiligingshandlers van revisie 2: Print de inhoud.

Beveiligingshandlers van revisie 3 of hoger: Print de inhoud
(mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of
`#PrintingQuality.PrintingQuality` is ook ingesteld).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Wijzig de inhoud.

Wijzig de inhoud van het document door andere bewerkingen
dan die beheerst worden door `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Kopieer of haal op andere wijze tekst en afbeeldingen uit het document.

Beveiligingshandlers van revisie 2: Kopieer of haal op andere wijze tekst en afbeeldingen uit de inhoud,
inclusief het extraheren van tekst en afbeeldingen (ter ondersteuning van toegankelijkheid voor gebruikers met
handicaps of voor andere doeleinden).

Beveiligingshandlers van revisie 3 of hoger: Kopieer of haal op andere wijze tekst en afbeeldingen uit
de inhoud door bewerkingen die anders zijn dan die beheerst door
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Voeg tekstannotaties toe of wijzig ze.

Voeg tekstannotaties toe of wijzig ze, vul interactieve formuliervelden in,
en, als `#ModifyContent.ModifyContent` ook is ingesteld,
maak of wijzig interactieve formuliervelden (inclusief handtekeningvelden).


### FillForm {#FillForm}
```
public static final int FillForm
```


Vul bestaande interactieve formuliervelden in.

Beveiligingshandlers van revisie 3 of hoger: Vul bestaande interactieve formuliervelden in
(inclusief handtekeningvelden), zelfs als `#ModifyTextAnnotations.ModifyTextAnnotations` niet is ingesteld.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Haal tekst en afbeeldingen op.

Beveiligingshandlers van revisie 3 of hoger: Extraheer tekst en afbeeldingen
(ter ondersteuning van toegankelijkheid voor gebruikers met een beperking of voor andere doeleinden).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Stel de inhoud samen.

Beveiligingshandlers van revisie 3 of hoger: Monteer de inhoud (invoegen, roteren of verwijderen van pagina's
en maak bladwijzers of miniatuurafbeeldingen), zelfs als `#ModifyContent.ModifyContent` niet is ingesteld.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Print de inhoud naar een representatie waaruit een getrouwe digitale kopie van het PDF-document kan worden gegenereerd.

Beveiligingshandlers van revisie 3 of hoger: Print de inhoud naar een representatie waaruit een getrouwe
digitale kopie van het PDF-document kan worden gegenereerd. Wanneer dit bit niet is ingesteld (en `#PrintDocument.PrintDocument`
is ingesteld), is afdrukken beperkt tot een low-level representatie van het uiterlijk, mogelijk van verminderde kwaliteit.


