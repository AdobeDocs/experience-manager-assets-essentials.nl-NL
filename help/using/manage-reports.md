---
title: Rapporten beheren in Assets Essentials
description: Heb toegang tot de gegevens in de rapportsectie van Assets Essentials om product en eigenschapgebruik te beoordelen en inzichten van zeer belangrijke succesmetriek af te leiden.
exl-id: c7155459-05d9-4a95-a91f-a1fa6ae9d9a4
source-git-commit: 810bb62cd5eb664e36a6ea267050dd025828e900
workflow-type: tm+mt
source-wordcount: '1221'
ht-degree: 0%

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

## Een rapport maken {#create-report}

De AEM Assets Essentials-omgeving biedt uitgebreide rapportagemogelijkheden via het Dashboard Rapporten. Met deze mogelijkheid kunnen gebruikers CSV-rapporten genereren en downloaden waarin de uploads en downloads van bedrijfsmiddelen binnen een opgegeven tijdsspanne worden beschreven, variërend van een eenmalig tot een dagelijks, wekelijks, maandelijks of jaarlijks interval.

**om een rapport tot stand te brengen:**

1. Navigeer aan **Rapporten** en klik **creëren rapport** (van het hoogste recht). **creeer rapport** dialoogdoos toont de hieronder gebieden:
   ![ creeer-rapport ](/help/using/assets/executed-reports1.svg)

   **In het lusje van de Configuratie:**

   1. **type van Rapport:** Uitgezocht onder [!UICONTROL Upload] of [!UICONTROL Download] rapporttype.
   1. **Titel:** voeg een titel aan het rapport toe.
   1. **Beschrijving:** voeg een facultatieve beschrijving aan het rapport toe.
   1. **Uitgezochte omslagweg:** selecteer een omslagweg om het rapport van geupload en gedownloade activa binnen die specifieke omslag te produceren. Als u bijvoorbeeld het rapport met middelen nodig hebt die naar een map zijn geüpload, geeft u het pad naar die map op.
   1. **Uitgezochte datuminterval:** selecteer de datumwaaier om te bekijken uploadt of downloadactiviteit binnen de omslag.

   <br>

   >[!NOTE]
   >
   > Assets Essentials zetten alle lokale tijdzones om in UTC (Coordinated Universal Time).

   **in het Lusje van Kolommen:** selecteer de kolomnamen in het rapport te tonen. In de volgende tabel wordt het gebruik van alle kolommen uitgelegd:

   <table>
    <tbody>
     <tr>
      <th><strong>Kolomnaam</strong></th>
      <th><strong>Beschrijving</strong></th>
      <th><strong>Rapporttype</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>De titel van het element.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>Pad</td>
      <td>Het mappad waar het element beschikbaar is in Assets Essentials.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>MIME-type</td>
      <td>Het MIME-type voor het element.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>Grootte</td>
      <td>De grootte van het element in bytes.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>Gedownload door</td>
      <td>De e-mailid van de gebruiker die het element heeft gedownload.</td>
      <td>Downloaden</td>
     </tr>
     <tr>
      <td>Downloaddatum</td>
      <td>De datum waarop de handeling voor het downloaden van middelen wordt uitgevoerd.</td>
      <td>Downloaden</td>
     </tr>
     <tr>
      <td>Auteur</td>
      <td>De auteur voor het element.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>Aanmaakdatum</td>
      <td>De datum waarop het element naar Assets Essentials wordt geüpload.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>Wijzigingsdatum</td>
      <td>De datum waarop het element voor het laatst is gewijzigd.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>Verlopen</td>
      <td>De vervalstatus van het actief.</td>
      <td>Uploaden en downloaden</td>
     </tr>
     <tr>
      <td>Gedownload op gebruikersnaam</td>
      <td>De naam van de gebruiker die het element heeft gedownload.</td>
      <td>Downloaden</td>
     </tr>              
    </tbody>
   </table>



## Bestaand rapport weergeven en downloaden {#View-and-download-existing-report}

De bestaande rapporten tonen onder **Uitvoerde Rapporten** tabel. Klik **Rapporten** en selecteer **Uitvoerde Rapporten** om alle gecreeerde rapporten met de status te bekijken zoals **voltooide**, erop wijzend zij klaar zijn te downloaden. Om het rapport in formaat te downloaden CSV of het rapport te schrappen, de rapportrij te selecteren en **te selecteren CSV van de Download** of **Schrapping**.
![ mening en download bestaande rapporten ](/help/using/assets/view-download-existing-report.png)

## Een rapport plannen {#schedule-report}

In de Hoofdzaak UI van de AEM, **het Rapport van het Programma** plaatst - omhoog een automatische generatie rapporten met gespecificeerde toekomstige intervallen zoals dagelijks, wekelijks, maandelijks, of jaarlijks. Met deze functie kunt u terugkerende rapportagebehoeften stroomlijnen en actuele gegevensupdates garanderen. Terwijl **Rapport** leidt produceert rapporten voor vroegere data. De voltooide rapporten worden vermeld onder **Uitvoerde Rapporten** en de komende rapporten worden gevonden onder **Geplande Rapporten**.

Volg onderstaande stappen om een rapport te plannen:

1. Klik op Rapporten in het linkervenster en klik vervolgens op Rapport maken (van rechtsboven).
1. In het dialoogvenster Rapport wordt de volgende informatie weergegeven:
   1. **type van Rapport:** Uitgezocht tussen uploadt en downloadtype.
   1. **Titel:** voeg een titel aan het rapport toe.
   1. **Beschrijving**: Voeg een facultatieve beschrijving aan het rapport toe.
   1. **Uitgezochte omslagweg:** selecteer een omslagweg om een rapport voor activa te produceren die aan of van die specifieke omslag in de toekomst zullen worden geupload.
   1. Wissel **rapport van het Programma:** Wissel om het rapport voor een recentere tijd of voor zijn herhaalde voorkomen te plannen.

      ![ planningsrapport ](/help/using/assets/schedule-reports1.svg)

   1. **kies frequentie:** specificeer het interval voor het produceren van het rapport (bijvoorbeeld, dagelijks, wekelijks, maandelijks, jaarlijks, of eens) en plaats de datum en de tijd om het rapport samen met de einddatum voor herhaling in werking te stellen. Voor een eenmalig rapport selecteert u het datumbereik voor het rapport over het geselecteerde activiteitstype in de AEM. Bijvoorbeeld, als u een rapport over gedownloade activa van de tiende tot 29e (toekomstige data) van een specifieke maand nodig hebt, selecteer deze data in het **Uitgezochte 1&rbrace; gebied van het datuminterval &lbrace;.**

   >[!NOTE]
   >
   > Assets Essentials zetten alle lokale tijdzones om in UTC (Coordinated Universal Time).

## Geplande rapporten weergeven {#view-scheduled-reports}

De geplande rapporten tonen onder **Geplande Rapporten** lusje op een systematisch georganiseerde manier. Alle voltooide rapporten voor elk gepland rapport worden opgeslagen binnen één enkele rapportomslag. Klik ![ uitvouwen samenvouwen ](/help/using/assets/expand-icon1.svg) om de voltooide rapporten te bekijken. Als u bijvoorbeeld een dagelijks rapport hebt gepland, worden alle voltooide rapporten gegroepeerd in één map. Deze organisatie vereenvoudigt zowel de navigatie als de ontdekkingsbaarheid van rapporten. Om geplande rapporten te bekijken, klik **Rapporten** en klik dan **Geplande Rapporten**. Alle geplande rapporten worden weergegeven met hun status als lopend of voltooid. Voltooide rapporten kunnen worden gedownload.
![ gepland rapport ](/help/using/assets/scheduled-reports-tab.png)

## Geplande rapporten bewerken en annuleren {#edit-cancel-scheduled-reports}

1. Navigeer aan de **Geplande Rapporten** tabel.
1. Selecteer de rapportrij.
1. Klik **uitgeven**.
1. Klik **annuleer Programma** en klik dan **bevestigen**, om het geplande rapport te annuleren. Voor geannuleerde rapporten, wordt de volgende runtime leeg en toont de status geannuleerd.
   ![ geef uit en annuleer gepland rapport ](/help/using/assets/cancel-edit-scheduled-reports.png)

### Plan hervatten {#resume-schedule}

Om het geannuleerde programma te hervatten, selecteer de rapportrij en klik **Programma van de Hervatting**. Wanneer deze wordt hervat, worden de volgende runtimegegevens opnieuw weergegeven en wordt de status weergegeven als zijnde actief.
![ hervat programma ](/help/using/assets/resume-schedule.png)

>[!NOTE]
>
> Als u een geannuleerd rapport hervat vóór de geplande einddatum, de rapporten van de annuleringsdatum aan de hervattingsdatum automatisch produceren.

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

* **Telling van Activa door grootte:** segmenteert het totale assetentelling in uw essentiële milieu van Assets in verschillende groottewaaiers, die de telling en het percentage activa in elke groottewaaier benadrukken, door een donutgrafiek wordt vertegenwoordigd.
  ![ inzichten-activa-telling-door-grootte ](/help/using/assets/insights-assets-count-by-size.svg)

* **Telling van Activa door het Type van Activa:** segmenteert het totale assetentelling in uw het essentiële milieu van Assets, die de telling en het percentage van activa benadrukken die op hun dossiertypes worden gebaseerd, door een donutgrafiek wordt vertegenwoordigd.
  ![ inzichten-activa-telling-door-grootte ](/help/using/assets/insights-assest-count-by-asset-type1.svg)

