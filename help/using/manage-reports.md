---
title: Rapporten beheren in Assets Essentials
description: Heb toegang tot de gegevens in de rapportsectie van Assets Essentials om product en eigenschapgebruik te beoordelen en inzichten van zeer belangrijke succesmetriek af te leiden.
exl-id: c7155459-05d9-4a95-a91f-a1fa6ae9d9a4
source-git-commit: 71a0381f5f7c32d3da1923778b3cd7b678391cae
workflow-type: tm+mt
source-wordcount: '827'
ht-degree: 1%

---

# Rapporten beheren {#manage-reports}

Middelenrapportage geeft beheerders inzicht in de activiteiten van de Adobe Experience Manager Assets Essentials-omgeving. Deze gegevens bevatten nuttige informatie over de manier waarop gebruikers met inhoud en het product werken. Alle gebruikers kunnen tot het dashboard van Inzichten toegang hebben en degenen die aan het het productprofiel van Beheerders worden toegewezen kunnen user-defined rapporten tot stand brengen.

## Toegangsrapporten {#access-reports}

Alle gebruikers die aan het [ het productprofiel van de Beheerders van Assets Essentials ](deploy-administer.md) worden toegewezen kunnen tot het dashboard van Inzichten toegang hebben of user-defined rapporten in Assets Essentials tot stand brengen.

Navigeer naar **[!UICONTROL Reports]** onder **[!UICONTROL Settings]** om rapporten te openen.

![ Rapporten ](assets/reports.png)
<!--
In the **[!UICONTROL Reports]** screen, various components are shown in the tabular format which includes the following:

* **Title**: Title of the report
* **Type**: Determines whether the report is uploaded or downloaded to the repository
* **Description**: Provide details of the report that was given during uploading/downloading the report
* **Status**: Determines whether the report is completed, under progress, or deleted.
* **Author**: Provides email of the author who has uploaded/downloaded the report.
* **Created**: Gives information of the date when the report was generated.
-->

## Inzichten weergeven {#view-live-statistics}

>[!CONTEXTUALHELP]
>id="assets_reports"
>title="Rapporten"
>abstract="Met het dashboard Inzichten kunt u real-time gegevens over gebeurtenissen weergeven voor uw Experience Manager Assets-omgeving in de afgelopen 30 dagen of de laatste 12 maanden. De lijst met gebeurtenissen bevat het aantal downloads, uploads, topzoekopdrachten, enzovoort."

Met Assets Essentials kunt u realtime gegevens voor uw Assets Essentials-omgeving weergeven met het dashboard Inzichten. U kunt real-time gebeurtenismetriek tijdens de laatste 30 dagen of voor de laatste 12 maanden bekijken.

<!--![Toolbar options when you select an asset](assets/assets-essentials-live-statistics.png)-->

Klik op **[!UICONTROL Insights]** beschikbaar in het linkernavigatievenster om de volgende automatisch gegenereerde grafieken weer te geven:

* **Downloads**: Het aantal activa die van het milieu van Assets Essentials in de laatste 30 dagen of 12 maanden worden gedownload vertegenwoordigden gebruikend een lijngrafiek.
  ![ downloads ](/help/using/assets/insights-downloads2341.svg)

* **uploadt**: Het aantal activa die aan het milieu van Assets Essentials in de laatste 30 dagen of 12 maanden worden geupload vertegenwoordigden gebruikend een lijngrafiek.
  ![ uploadt ](/help/using/assets/insights-uplods2.svg)

<!--* **Asset Count by Size**: The division of count of assets based on their range of various sizes from 0 MB to 100 GB.-->

* **gebruik van de Opslag**: Het opslaggebruik, in bytes, voor het milieu van Assets Essentials dat gebruikend een staafdiagram wordt vertegenwoordigd.
  ![ opslaggebruik ](/help/using/assets/insights-storage-usage1.svg)
  <!--* **Delivery**: The graph depicts the count of assets as the delivery dates.-->

<!--* **Asset Count by Asset Type**: Represents count of various MIME types of the available assets. For example, application/zip, image/png, video/mp4, application/postscripte.-->

* **Hoogste Zoekopdrachten**: De hoogste gezochte termijnen van de mening samen met het aantal tijden die termijnen binnen uw milieu van Assets Essentials in de laatste 30 dagen of 12 maanden worden gezocht die maanden in een tabelformaat worden vertegenwoordigd.
  ![ opslaggebruik ](/help/using/assets/insights-top-search.svg)

  <!--
   ![Insights](assets/insights1.png)
   ![Insights](assets/insights2.png)
   -->

## Een downloadrapport maken {#create-download-report}

Een downloadrapport maken:

1. Navigeer naar **[!UICONTROL Settings]** > **[!UICONTROL Reports]** en klik op **[!UICONTROL Create Report]** .

1. Geef op het tabblad [!UICONTROL Configuration] het rapporttype op als **[!UICONTROL Download]** .

1. Geef een titel en een optionele beschrijving voor het rapport op.

1. Selecteer met behulp van het veld **[!UICONTROL Select Folder Path]** het mappad met de elementen waarop het rapport moet worden uitgevoerd.

1. Selecteer het datuminterval voor het rapport.

   >[!NOTE]
   >
   > Assets Essentials zetten alle lokale tijdzones om in UTC (Coordinated Universal Time).

1. Selecteer op het tabblad [!UICONTROL Columns] de kolomnamen die u in het rapport wilt weergeven.

1. Klikken **[!UICONTROL Create]**

   ![ Rapport van de Download ](assets/download-reports-config.png)

De volgende lijst verklaart het gebruik van alle kolommen die u aan het rapport kunt toevoegen:

<table>
    <tbody>
     <tr>
      <th><strong>Kolomnaam</strong></th>
      <th><strong>Beschrijving</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>De titel van het element.</td>
     </tr>
     <tr>
      <td>Pad</td>
      <td>Het mappad waar het element beschikbaar is in Assets Essentials.</td>
     </tr>
     <tr>
      <td>MIME-type</td>
      <td>Het MIME-type voor het element.</td>
     </tr>
     <tr>
      <td>Grootte</td>
      <td>De grootte van het element in bytes.</td>
     </tr>
     <tr>
      <td>Gedownload door</td>
      <td>De e-mailid van de gebruiker die het element heeft gedownload.</td>
     </tr>
     <tr>
      <td>Downloaddatum</td>
      <td>De datum waarop de handeling voor het downloaden van middelen wordt uitgevoerd.</td>
     </tr>
     <tr>
      <td>Auteur</td>
      <td>De auteur voor het element.</td>
     </tr>
     <tr>
      <td>Aanmaakdatum</td>
      <td>De datum waarop het element naar Assets Essentials wordt geüpload.</td>
     </tr>
     <tr>
      <td>Wijzigingsdatum</td>
      <td>De datum waarop het element voor het laatst is gewijzigd.</td>
     </tr>
     <tr>
      <td>Verlopen</td>
      <td>De vervalstatus van het actief.</td>
     </tr>
     <tr>
      <td>Gedownload op gebruikersnaam</td>
      <td>De naam van de gebruiker die het element heeft gedownload.</td>
     </tr>           
    </tbody>
   </table>

## Een rapport voor uploaden maken {#create-upload-report}

Een rapport voor uploaden maken:

1. Navigeer naar **[!UICONTROL Settings]** > **[!UICONTROL Reports]** en klik op **[!UICONTROL Create Report]** .

1. Geef op het tabblad [!UICONTROL Configuration] het rapporttype op als **[!UICONTROL Upload]** .

1. Geef een titel en een optionele beschrijving voor het rapport op.

1. Selecteer met behulp van het veld **[!UICONTROL Select Folder Path]** het mappad met de elementen waarop het rapport moet worden uitgevoerd.

1. Selecteer het datuminterval voor het rapport.

1. Selecteer op het tabblad [!UICONTROL Columns] de kolomnamen die u in het rapport wilt weergeven.

1. Klik op **[!UICONTROL Create]**.

   ![ upload Rapport ](assets/upload-reports-config.png)

De volgende lijst verklaart het gebruik van alle kolommen die u aan het rapport kunt toevoegen:

<table>
    <tbody>
     <tr>
      <th><strong>Kolomnaam</strong></th>
      <th><strong>Beschrijving</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>De titel van het element.</td>
     </tr>
     <tr>
      <td>Pad</td>
      <td>Het mappad waar het element beschikbaar is in Assets Essentials.</td>
     </tr>
     <tr>
      <td>MIME-type</td>
      <td>Het MIME-type voor het element.</td>
     </tr>
     <tr>
      <td>Grootte</td>
      <td>De grootte van het element.</td>
     </tr>
     <tr>
      <td>Auteur</td>
      <td>De auteur voor het element.</td>
     </tr>
     <tr>
      <td>Aanmaakdatum</td>
      <td>De datum waarop het element naar Assets Essentials wordt geüpload.</td>
     </tr>
     <tr>
      <td>Wijzigingsdatum</td>
      <td>De datum waarop het element voor het laatst is gewijzigd.</td>
     </tr>
     <tr>
      <td>Verlopen</td>
      <td>De vervalstatus van het actief.</td>
     </tr>              
    </tbody>
   </table>

## Bestaande rapporten weergeven {#view-report-list}

Na [ creërend het rapport ](#create-download-report), kunt u de lijst van bestaande rapporten bekijken en selecteren om hen in een formaat te downloaden CSV of hen te schrappen.

Navigeer naar **[!UICONTROL Settings]** > **[!UICONTROL Reports]** om de lijst met rapporten weer te geven.

Voor elk rapport, kunt u rapporttitel, het type van het rapport, gespecificeerde beschrijving bekijken terwijl het creëren van het rapport, status van het rapport, e-mailidentiteitskaart van de auteur die het rapport creeerde, en de datum van de rapportverwezenlijking.

`Completed ` status van het rapport geeft aan dat het rapport gereed is voor downloaden.

![ Lijst van rapporten ](assets/list-of-reports.png)


## Een CSV-rapport downloaden {#download-csv-report}

Een rapport in CSV-indeling downloaden:

1. Ga naar **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

1. Selecteer een rapport en klik op **[!UICONTROL Download CSV]** .

Het geselecteerde rapport wordt gedownload in CSV-indeling. De kolommen die in het CSV-rapport worden weergegeven, zijn afhankelijk van de kolommen die u selecteert terwijl [ het rapport ](#create-download-report) maakt.

## Een rapport verwijderen {#delete-report}

Een rapport verwijderen:

1. Ga naar **[!UICONTROL Settings]** > **[!UICONTROL Reports]**.

1. Selecteer een rapport en klik op **[!UICONTROL Delete]** .

1. Klik nogmaals op **[!UICONTROL Delete]** om te bevestigen.
