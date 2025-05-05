---
title: Ondersteunde bestandsindelingen
description: Ondersteunde bestandsindelingen voor de verschillende gebruiksgevallen van  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: 243a41aef81cd1fdcbad8f4355fe2d888db394d1
workflow-type: tm+mt
source-wordcount: '520'
ht-degree: 0%

---

# Ondersteuning voor bestandsindelingen in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] ondersteunt een groot aantal bestandsindelingen en elke functie biedt verschillende ondersteuning voor verschillende bestandstypen.

* ![ het type van beelddossier pictogram ](assets/image-icon.svg) Beelden: JPG, PNG, GIF, TIFF, en anderen
* ![ creatieve wolkentypepictogram ](assets/creative-cloud-files.svg) dossiers van het Creative Cloud: PSD, PSB, AI, en INDD
* ![ het pictogram van het cameratype ](assets/camera-icon.svg) Camera Raw dossiers: CR2/CR3, NEF, SRW/SRF en anderen
* ![ het type van documentdossier pictogram ](assets/document-icon.svg) Documenten: DOCX, PDF, PPTX, en XLSX
* ![ het type van videodossier pictogram ](assets/video-icon.svg) Video&#39;s: MP4

[!DNL Assets Essentials] ondersteunt elke binaire bestandsindeling met basisservices, zoals opslag, uploaden, kopiëren, verplaatsen, verwijderen en toevoegen van metagegevens.

[!DNL Assets Essentials] biedt ook ondersteuning voor Camera RAW-bestanden van een groot aantal toonaangevende camerafabrikanten, waaronder Canon (CR2/CR3), Nikon (NEF), Sony (SRW/SRF), Fujifilm (RAF), Olympus (ORF) en andere, aangedreven door Adobe Camera Raw.

De verschillende bestandstypen bieden verschillende mate van ondersteuning voor de gebruiksgevallen en -functies, zoals hieronder wordt beschreven. Gebruik de legenda om het steunniveau te begrijpen.

| Ondersteuningsniveau | Beschrijving |
|-------------------|-------------------------|
| ✓ | Ondersteund |
| ✓ ‡ | Voorwaardelijk ondersteund |
| - | Niet van toepassing |

## Elementen toevoegen, uploaden en weergeven {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Type element | [ doorbladeren ](/help/using/navigate-view.md) | Kopiëren | [ uploadt ](/help/using/add-delete.md) | Maken | [ Schrapping ](/help/using/add-delete.md#delete-assets) | Details | Zoomen op afbeelding | [ onlangs Bekeken ](/help/using/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4-video&#39;s | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD, AI, PSB en INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| Overige binaire bestanden | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Elementen zoeken, gebruiken en bewerken {#support-to-search-use-edit}

| Type element | [ Download ](/help/using/manage-organize.md#download) | Slepen en slepen | [ redacteur van het Beeld ](/help/using/edit-images.md) | [Zoeken](/help/using/search.md) | [ Slimme Markeringen ](/help/using/metadata.md#tags) | [ anders noemen ](/help/using/manage-organize.md) | [ Versies ](/help/using/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| Video&#39;s | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| CC Libraries | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD en PSB | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| AI en INDD | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| Overige binaire bestanden | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## Elementen controleren en samenwerken {#support-to-review-collaborate}

| Type element | Annoteren | Opmerking | Taken maken en revisie uitvoeren |
|---------------|----------|----------|-------------------------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | ✓ |
| Mappen | - | - | - |
| Video&#39;s | - | ✓ | ✓ |
| CC Libraries | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD, PSB, AI en INDD | - | ✓ | ✓ |
| Overige binaire bestanden | - | ✓ | ✓ |
| DOC | - | ✓ | ✓ |
| DOCX | - | ✓ | ✓ |
| PPT | - | ✓ | ✓ |
| PPTX | - | ✓ | ✓ |
| XLS | - | ✓ | ✓ |
| XLSX | - | ✓ | ✓ |
| TXT | - | ✓ | ✓ |
| RTF | - | ✓ | ✓ |

## Overige taken voor vermogensbeheer {#support-to-manage-assets}

| Type element | [ Metagegevens ](/help/using/metadata.md) | [ Vertoningen ](/help/using/add-delete.md#renditions) | [ Afval ](/help/using/add-delete.md#delete-assets) | Kopiëren | Verplaatsen |
|---------------|-------------------|------------|----------|----------|----------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW-bestanden | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ | - | ✓ | ✓ | ✓ |
| Video&#39;s | ✓ | - | ✓ | ✓ | ✓ |
| CC Libraries | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| AI en INDD | ✓ | - | ✓ | ✓ | ✓ |
| PSD en PSB | ✓ | ✓ | ✓ | ✓ | ✓ |
| Overige binaire bestanden | ✓ | - | ✓ | ✓ | ✓ |

Gebruikers van [!DNL Adobe Asset Link] kunnen bestanden uploaden en inchecken (een nieuwe versie uploaden) in de [!DNL Assets Essentials] -opslagplaats vanuit de ondersteunde [!DNL Adobe Creative Cloud] -bureaubladtoepassingen.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD, PSB           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

## Volgende stappen {#next-steps}

* Feedback geven op het product met de optie [!UICONTROL Feedback] die beschikbaar is in de gebruikersinterface van Assets Essentials

* Verstrek documentatie terugkoppelt gebruikend [!UICONTROL Edit this page] ![ uitgeeft de pagina ](assets/do-not-localize/edit-page.png) of [!UICONTROL Log an issue] ![ creeer een kwestie GitHub ](assets/do-not-localize/github-issue.png) beschikbaar op juiste sidebar

* De Zorg van de Klant van het contact [&#128279;](https://experienceleague.adobe.com/?support-solution=General#support)
