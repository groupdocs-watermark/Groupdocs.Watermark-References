---
title: "Watermarker"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe Watermarkergroupdocs.watermark/watermarker avec le chemin de document spécifié."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le chemin de document spécifié.

```csharp
public Watermarker(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à partir duquel charger le document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents : [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Charge et enregistre un contenu dans n'importe quel format pris en charge.

```csharp
// Charge un contenu à partir d'un fichier.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utilisez les méthodes de la classe Watermarker pour ajouter, rechercher ou supprimer des filigranes.

    // Enregistrez le document.
    watermarker.Save("D:\\output.pdf");
}
```

### Voir aussi

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le chemin de document spécifié et les options de chargement.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier pour charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents : [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Chargez un document PDF chiffré en utilisant le mot de passe.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Voir aussi

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le chemin de document spécifié et les paramètres.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier pour charger le document. |
| paramètres | WatermarkerSettings | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents : [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Définissez les objets recherchables globalement (pour tous les documents qui seront chargés après cela).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Le code pour travailler avec les filigranes trouvés va ici.
    }
}
```

### Voir aussi

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le chemin de document spécifié, les options de chargement et les paramètres.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier pour charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |
| paramètres | WatermarkerSettings | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents : [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Trouvez des fragments de texte particuliers dans le corps/sujet du message électronique.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Remarque, la recherche n'est effectuée que si vous transmettez une instance de TextSearchCriteria à la méthode Search.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Supprimer les fragments de texte trouvés
    watermarks.Clear();
    // Enregistrer les modifications
    watermarker.Save();
}
```

### Voir aussi

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le flux spécifié.

```csharp
public Watermarker(Stream document)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Charger et enregistrer un document dans n'importe quel format pris en charge.

```csharp
// Charger un contenu depuis un flux.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Utilisez les méthodes de la classe Watermarker pour ajouter, rechercher ou supprimer des filigranes.

    // Enregistrez les modifications.
    watermarker.Save(outputStream);
}
```

### Voir aussi

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le flux spécifié et les options de chargement.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Charger un document PDF chiffré à l'aide d'un mot de passe

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Voir aussi

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le flux spécifié et les paramètres.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |
| paramètres | WatermarkerSettings | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Définissez les objets recherchables globalement (pour tous les documents qui seront chargés après cela).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Le code pour travailler avec les filigranes trouvés va ici.
    }
}
```

### Voir aussi

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initialise une nouvelle instance de la classe [`Watermarker`](../../watermarker) avec le flux spécifié, les options de chargement et les paramètres.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |
| paramètres | WatermarkerSettings | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement des documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exemples

Trouvez des fragments de texte particuliers dans le corps/sujet du message électronique.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Remarque, la recherche n'est effectuée que si vous transmettez une instance de TextSearchCriteria à la méthode Search.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Supprimer les fragments de texte trouvés
    watermarks.Clear();
    // Enregistrer les modifications
    watermarker.Save();
}
```

### Voir aussi

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
