---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt die Benutzerberechtigungen für ein PDF‑Dokument dar."
type: docs
weight: 68
url: /de/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Stellt die Berechtigungen des Benutzers für ein PDF-Dokument dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Drucke den Inhalt. |
|
|  | [ModifyContent](#ModifyContent) | Ändere den Inhalt. |
|
|  | [ExtractContent](#ExtractContent) | Kopiere oder extrahiere anderweitig Text und Grafiken aus dem Dokument. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Füge Textanmerkungen hinzu oder ändere sie. |
|
|  | [FillForm](#FillForm) | Fülle vorhandene interaktive Formularfelder aus. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Extrahiere Text und Grafiken. |
|
|  | [AssembleDocument](#AssembleDocument) | Setze den Inhalt zusammen. |
|
|  | [PrintingQuality](#PrintingQuality) | Drucke den Inhalt in eine Darstellung, aus der eine getreue digitale Kopie des PDF‑Dokuments erzeugt werden kann. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Drucke den Inhalt.

Sicherheits-Handler der Revision 2: Drucke den Inhalt.

Sicherheits-Handler der Revision 3 oder höher: Drucke den Inhalt
(möglicherweise nicht auf höchstem Qualitätsniveau, abhängig davon, ob
`#PrintingQuality.PrintingQuality` ebenfalls gesetzt ist).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Ändere den Inhalt.

Ändere den Inhalt des Dokuments durch andere Vorgänge
als die, die von `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm` gesteuert werden.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Kopiere oder extrahiere anderweitig Text und Grafiken aus dem Dokument.

Sicherheits-Handler der Revision 2: Kopiere oder extrahiere anderweitig Text und Grafiken aus dem Inhalt,
einschließlich des Extrahierens von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Benutzer mit
Behinderungen oder zu anderen Zwecken).

Sicherheits-Handler der Revision 3 oder höher: Kopieren oder anderweitig Text und Grafiken extrahieren aus
dem Inhalt durch Vorgänge, die nicht von
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Füge Textanmerkungen hinzu oder ändere sie.

Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen,
und, wenn `#ModifyContent.ModifyContent` ebenfalls gesetzt ist,
interaktive Formularfelder (einschließlich Signaturfelder) erstellen oder ändern.


### FillForm {#FillForm}
```
public static final int FillForm
```


Fülle vorhandene interaktive Formularfelder aus.

Sicherheits-Handler der Revision 3 oder höher: Vorhandene interaktive Formularfelder ausfüllen
(einschließlich Signaturfelder), selbst wenn `#ModifyTextAnnotations.ModifyTextAnnotations` deaktiviert ist.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Extrahiere Text und Grafiken.

Sicherheits-Handler der Revision 3 oder höher: Text und Grafiken extrahieren
(zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Setze den Inhalt zusammen.

Sicherheits-Handler der Revision 3 oder höher: Inhalt zusammenstellen (einfügen, drehen oder Seiten löschen
und Lesezeichen oder Miniaturbilder erstellen), selbst wenn `#ModifyContent.ModifyContent` deaktiviert ist.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Drucke den Inhalt in eine Darstellung, aus der eine getreue digitale Kopie des PDF‑Dokuments erzeugt werden kann.

Sicherheits-Handler der Revision 3 oder höher: Inhalt drucken zu einer Darstellung, aus der eine getreue
digitale Kopie des PDF-Dokuments erzeugt werden kann. Wenn dieses Bit deaktiviert ist (und `#PrintDocument.PrintDocument`
gesetzt ist), ist der Druck auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, möglicherweise von verminderter Qualität.


