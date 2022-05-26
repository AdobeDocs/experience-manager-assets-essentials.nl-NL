---
title: Ondersteunde bestandsindelingen
description: Ondersteunde bestandsindelingen voor de verschillende gebruiksgevallen van [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: 02f28c00b387fbcac4cd917fab7763124fdd5d70
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 5%

---

# Bestandsindelingen worden ondersteund in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] ondersteunt een groot aantal bestandsindelingen en elke functie biedt verschillende ondersteuning voor verschillende bestandstypen.

* ![pictogram type afbeeldingsbestand](assets/image-icon.svg) Afbeeldingen: JPG, PNG, GIF, TIFF en andere
* ![creative cloudtype, pictogram](assets/creative-cloud-files.svg) Creative Cloud-bestanden: PSD, AI en INDD
* ![cameratype, pictogram](assets/camera-icon.svg) Camera Raw bestanden: CR2/CR3, NEF, SRW/SRF en andere
* ![pictogram documenttype](assets/document-icon.svg) Documenten: DOCX, PDF, PPTX en XLSX
* ![pictogram videobestandstype](assets/video-icon.svg) Video&#39;s: MP4

[!DNL Assets Essentials] ondersteunt elke binaire bestandsindeling met basisservices, zoals opslaan, uploaden, kopiëren, verplaatsen, verwijderen en toevoegen van metagegevens.

[!DNL Assets Essentials] ondersteunt ook Camera RAW-bestanden van een groot aantal toonaangevende camerafabrikanten, waaronder Canon (CR2/CR3), Nikon (NEF), Sony (SRW/SRF), Fujifilm (RAF), Olympus (ORF) en andere, aangedreven door Adobe Camera Raw.

De verschillende bestandstypen bieden verschillende mate van ondersteuning voor de gebruiksgevallen en -functies, zoals hieronder wordt beschreven. Gebruik de legenda om het steunniveau te begrijpen.

| Ondersteuningsniveau | Beschrijving |
|-------------------|-------------------------|
| ✓ | Ondersteund |
| ✓ ‡ | voorwaardelijk ondersteund |
| - | Niet van toepassing |

## Elementen toevoegen, uploaden en weergeven {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Type element | [Bladeren](/help/navigate-view.md) | Kopiëren | [Uploaden](/help/add-delete.md) | Maken | [Verwijderen](/help/add-delete.md#delete-assets) | Details | Zoomen op afbeelding | [Onlangs bekeken](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4-video&#39;s | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD, AI en INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| Overige binaire bestanden | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Elementen zoeken, gebruiken en bewerken {#support-to-search-use-edit}

| Type element | [Downloaden](/help/manage-organize.md#download) | Slepen en neerzetten | [Afbeeldingseditor](/help/edit-images.md) | [Zoeken](/help/search.md) | [Slimme tags](/help/metadata.md#tags) | [Naam wijzigen](/help/manage-organize.md) | [Versies](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| Video&#39;s | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| CC-bibliotheken | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD, AI en INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Overige binaire bestanden | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## Elementen controleren en samenwerken {#support-to-review-collaborate}

| Type element | Annoteren | Opmerking | Taken en revisie maken |
|---------------|----------|----------|-------------------------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | ✓ |
| Mappen | - | - | - |
| Video&#39;s | - | ✓ | ✓ |
| CC-bibliotheken | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD, AI en INDD | - | ✓ | ✓ |
| Overige binaire bestanden | - | ✓ | ✓ |

## Overige taken voor vermogensbeheer {#support-to-manage-assets}

| Type element | [Metagegevens](/help/metadata.md) | [Uitvoeringen](/help/add-delete.md#renditions) | [Prullenbak](/help/add-delete.md#delete-assets) | Kopiëren | Verplaatsen |
|---------------|-------------------|------------|----------|----------|----------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ | - | ✓ | ✓ | ✓ |
| Video&#39;s | ✓ | - | ✓ | ✓ | ✓ |
| CC-bibliotheken | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD, AI en INDD | ✓ | - | ✓ | ✓ | ✓ |
| Overige binaire bestanden | ✓ | - | ✓ | ✓ | ✓ |

Gebruikers van [!DNL Adobe Asset Link] kan bestanden uploaden en inchecken (een nieuwe versie uploaden) in de [!DNL Assets Essentials] opslagplaats van de ondersteunde [!DNL Adobe Creative Cloud] bureaubladtoepassingen.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

## Volgende stappen {#next-steps}

* Feedback geven op het product met de [!UICONTROL Feedback] -optie beschikbaar in de gebruikersinterface van Assets Essentials

* Documentfeedback geven met [!UICONTROL Edit this page] ![de pagina bewerken](assets/do-not-localize/edit-page.png) of [!UICONTROL Log an issue] ![een GitHub-probleem maken](assets/do-not-localize/github-issue.png) beschikbaar op de rechterzijbalk

* Contact [Klantenservice](https://experienceleague.adobe.com/?support-solution=General#support)
