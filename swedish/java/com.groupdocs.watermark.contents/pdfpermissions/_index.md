---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar användarens behörigheter för ett PDF-dokument."
type: docs
weight: 68
url: /sv/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Representerar användarens behörigheter för ett pdf-dokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Skriv ut innehållet. |
|
|  | [ModifyContent](#ModifyContent) | Ändra innehållet. |
|
|  | [ExtractContent](#ExtractContent) | Kopiera eller på annat sätt extrahera text och grafik från dokumentet. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Lägg till eller ändra textanteckningar. |
|
|  | [FillForm](#FillForm) | Fyll i befintliga interaktiva formulärfält. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Extrahera text och grafik. |
|
|  | [AssembleDocument](#AssembleDocument) | Sätt ihop innehållet. |
|
|  | [PrintingQuality](#PrintingQuality) | Skriv ut innehållet till en representation från vilken en trogen digital kopia av PDF-dokumentet kan genereras. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Skriv ut innehållet.

Säkerhetshanterare för revision 2: Skriv ut innehållet.

Säkerhetshanterare för revision 3 eller högre: Skriv ut innehållet
(möjligen inte på högsta kvalitetsnivå, beroende på om
`#PrintingQuality.PrintingQuality` är också satt).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Ändra innehållet.

Ändra dokumentets innehåll med andra operationer
än de som styrs av `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Kopiera eller på annat sätt extrahera text och grafik från dokumentet.

Säkerhetshanterare för revision 2: Kopiera eller på annat sätt extrahera text och grafik från innehållet,
inklusive extrahering av text och grafik (för att stödja tillgänglighet för användare med
funktionsnedsättningar eller för andra ändamål).

Säkerhetshanterare för revision 3 eller högre: Kopiera eller på annat sätt extrahera text och grafik från
innehållet med operationer annat än de som styrs av
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Lägg till eller ändra textanteckningar.

Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält,
och, om `#ModifyContent.ModifyContent` också är satt,
skapa eller ändra interaktiva formulärfält (inklusive signaturfält).


### FillForm {#FillForm}
```
public static final int FillForm
```


Fyll i befintliga interaktiva formulärfält.

Säkerhetshanterare för revision 3 eller högre: Fyll i befintliga interaktiva formulärfält
(inklusive signaturfält), även om `#ModifyTextAnnotations.ModifyTextAnnotations` är avmarkerad.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Extrahera text och grafik.

Säkerhetshanterare för revision 3 eller högre: Extrahera text och grafik
(för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Sätt ihop innehållet.

Säkerhetshanterare för revision 3 eller högre: Sammanställ innehållet (infoga, rotera eller ta bort sidor
och skapa bokmärken eller miniatyrbilder), även om `#ModifyContent.ModifyContent` är avmarkerad.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Skriv ut innehållet till en representation från vilken en trogen digital kopia av PDF-dokumentet kan genereras.

Säkerhetshanterare för revision 3 eller högre: Skriv ut innehållet till en representation från vilken en trogen
digital kopia av PDF-dokumentet kan genereras. När denna flagga är avmarkerad (och `#PrintDocument.PrintDocument`
är satt), begränsas utskrift till en låg nivå-representation av utseendet, möjligen med försämrad kvalitet.


