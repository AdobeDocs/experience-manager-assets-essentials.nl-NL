---
title: Uw digitale middelen beheren
description: Verplaats, verwijder, kopieer, hernoem, werk en versie uw activa in [!DNL Assets Essentials].
role: User,Leader
contentOwner: AG
exl-id: b01e98b9-0cc2-47c5-9f5b-79b8e6bef39f
source-git-commit: 638d1cef41c5cde1f4f16e231eef5852d779b7e1
workflow-type: tm+mt
source-wordcount: '1124'
ht-degree: 0%

---

# Elementen beheren {#manage-assets}

U kunt verschillende DAM-taken (Digital Asset Management) eenvoudig uitvoeren met de gebruiksvriendelijke interface van [!DNL Assets Essentials]. Nadat u de elementen hebt toegevoegd, kunt u uw elementen zoeken, downloaden, verplaatsen, kopiëren, hernoemen, verwijderen, bijwerken en bewerken.

Gebruiken [!DNL Assets Essentials] om de volgende taken voor middelenbeheer uit te voeren. Wanneer u een element selecteert, worden de volgende opties bovenaan op de werkbalk weergegeven.

![Werkbalkopties wanneer u een element selecteert](assets/asset-options.png)

*Afbeelding: op de werkbalk zijn opties beschikbaar voor een geselecteerde afbeelding.*

U kunt de elementen selecteren die in de zoekresultaten worden weergegeven en de volgende handelingen uitvoeren:

* ![pictogram deselecteren](assets/do-not-localize/close-icon.png) Schakel de selectie uit.

* ![vergelijkbaar pictogram zoeken](assets/do-not-localize/find-similar.svg) Vind gelijkaardig beeldmiddel in de UI van Activa die op de meta-gegevens en slimme markeringen wordt gebaseerd.

* ![detailpictogram](assets/do-not-localize/edit-in-icon.png) Klik om een voorvertoning van een element weer te geven en de gedetailleerde metagegevens weer te geven. Als u een voorvertoning weergeeft, kunt u de versies weergeven en een afbeelding bewerken.

* ![downloadpictogram](assets/do-not-localize/download-icon.png) Download het geselecteerde element naar uw lokale bestandssysteem.

* ![pictogram Verzameling toevoegen](assets/do-not-localize/add-collection.svg) Voeg het geselecteerde element toe aan een verzameling.

* ![Pictogram Elementen vastzetten](assets/do-not-localize/pin-quick-access.svg) Een element vastzetten om sneller toegang te krijgen wanneer u het later nodig hebt. Alle vastgezette items worden weergegeven in het dialoogvenster **Snelle toegang** van Mijn werkruimte.

* ![bewerken in pictogram Expressie](assets/do-not-localize/edit-e.svg) Bewerk een afbeelding in de geïntegreerde Adobe Express in Adobe Experience Manager Assets.

* ![middelenpictogram bewerken](assets/do-not-localize/edit-e.svg) Bewerk de afbeelding met Adobe Express.

* ![pictogram voor delen van elementkoppeling](assets/do-not-localize/share-link.svg) voor een middel met andere gebruikers zodat zij tot het kunnen toegang hebben en downloaden.

* ![verwijderpictogram](assets/do-not-localize/delete-icon.png) Verwijder het geselecteerde element of de geselecteerde map.

* ![kopieerpictogram](assets/do-not-localize/copy-icon.png) Kopieer het geselecteerde bestand of de geselecteerde map.

* ![verplaatsingspictogram](assets/do-not-localize/move-icon.png) Verplaats het geselecteerde element of de geselecteerde map naar een andere locatie in de hiërarchie van de opslagplaats.

* ![pictogram hernoemen](assets/do-not-localize/rename-icon.png) Wijzig de naam van het geselecteerde element of de geselecteerde map. Gebruik een unieke naam anders ontbreekt het anders noemen met een waarschuwing. U kunt het opnieuw proberen met een nieuwe naam.

* ![bibliotheekpictogram kopiëren](assets/do-not-localize/copy-icon.png) Voeg een element toe aan de bibliotheek.

* ![taakpictogram toewijzen](assets/do-not-localize/review-delegate-icon.png) Taken toewijzen aan andere gebruikers om samen te werken aan een element.

* ![taakpictogram toewijzen](assets/do-not-localize/watch-asset.svg) De bewerkingen controleren die op een element worden uitgevoerd.

U kunt dezelfde opties weergeven op de miniaturen van elementen.

![Opties op elementminiatuur voor het beheren van elementen](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] Hiermee geeft u op de werkbalk alleen de relevante opties weer die afhankelijk zijn van het type geselecteerd element.

![Werkbalkopties wanneer u een element selecteert](assets/toolbar-folder-selected.png)

*Afbeelding: opties beschikbaar op de werkbalk voor een geselecteerde map.*

![Werkbalkopties wanneer u een element selecteert](assets/toolbar-pdf-selected.png)

*Afbeelding: op de werkbalk zijn opties beschikbaar voor een geselecteerd PDF-bestand.*

## Elementen downloaden en distribueren {#download}

U kunt een of meer elementen of mappen of een combinatie van beide selecteren en de selectie naar uw lokale bestandssysteem downloaden. U kunt de elementen bewerken en opnieuw uploaden of de elementen buiten de elementen distribueren [!DNL Assets Essentials]. U kunt ook [de vertoningen downloaden](/help/using/add-delete.md#renditions) van een actief.

## Asset versioning {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] Hiermee worden de elementen bijgewerkt of bewerkt wanneer de elementen opnieuw worden geüpload. U kunt versiegeschiedenis, oudere versies bekijken, en een vroegere versie van activa als recentste versie herstellen, die aan een vorige versie indien nodig wordt teruggezet. In de volgende scenario&#39;s worden versies van middelen gemaakt:

* Upload een nieuw element met dezelfde bestandsnaam als een bestaand element en in dezelfde map als het bestaande element. [!DNL Assets Essentials] vragen om het vorige element te overschrijven of het nieuwe element op te slaan als een versie. Zie [dubbele elementen uploaden](/help/using/add-delete.md#resolve-upload-fails).

  ![Versies maken tijdens uploaden](assets/uploads-manage-duplicates.png)

  *Afbeelding: wanneer u een element uploadt dat hetzelfde heet als een bestaand element, kunt u een versie van het element maken.*

* Een afbeelding bewerken en klikken **[!UICONTROL Save as Version]**. Zie [afbeeldingen bewerken](/help/using/edit-images.md).

  ![Bewerkte afbeelding opslaan als versie](assets/edit-image2.png)

  *Afbeelding: Bewerkte afbeelding opslaan als versie.*

* Open de versies van een bestaand element. Klikken **[!UICONTROL New Version]** en uploadt u een nieuwere versie van het middel in de repository.

  ![Optie voor het uploaden van een nieuwe versie van een element uit de versiegeschiedenis](assets/view-asset-versions2.png)

### Versies van een element weergeven {#view-versions}

Wanneer u een gedupliceerde kopie of een gewijzigde kopie van een element uploadt, kunt u de versies ervan maken. Met Versioning kunt u historische elementen controleren en desgewenst terugkeren naar een vorige versie.

Als u versies wilt weergeven, opent u de voorvertoning van een element en klikt u op **[!UICONTROL Versions]** ![Versiepictogram](assets/do-not-localize/versions-clock-icon.png) in de rechterzijbalk. Als u een voorvertoning van een specifieke versie wilt weergeven, selecteert u deze. Klik op **[!UICONTROL Make Latest]**.

U kunt ook versies maken van de tijdlijn van de versie. Selecteer de meest recente versie en klik op **[!UICONTROL New Version]** en uploadt u een nieuwe kopie van het element vanuit uw lokale bestandssysteem.

![Versies van een element weergeven](assets/view-asset-versions1.png)

*Afbeelding: U kunt versies van een element weergeven, terugkeren naar een vorige versie of een andere nieuwe versie uploaden.*

## De elementstatus beheren {#manage-asset-status}

**Vereiste machtigingen:**  `Can Edit`, `Owner`of beheerdersmachtigingen voor een middel.

Met Assets Essentials kunt u de status instellen voor middelen die beschikbaar zijn in de opslagplaats. Stel een elementstatus in om het downstreamgebruik van digitale elementen beter te beheren en te beheren.

U kunt de volgende status instellen voor elementen:

* Goedgekeurd

* Geweigerd

* Geen status

### Status van element instellen {#set-asset-status}

De elementstatus instellen:

1. Selecteer het element en klik op **[!UICONTROL Details]** in de werkbalk.

1. In de **[!UICONTROL Basic]** selecteert u de elementstatus in het menu **[!UICONTROL Status]** vervolgkeuzelijst. Mogelijke waarden zijn Goedgekeurd, Afgewezen en Geen status (standaardwaarde).

   >[!VIDEO](https://video.tv.adobe.com/v/342495)


### Vervaldatum van element instellen {#set-asset-expiration-date}

Met Assets Essentials kunt u ook een vervaldatum instellen voor de middelen die in de opslagplaats beschikbaar zijn. U kunt vervolgens [de zoekresultaten filteren](search.md#refine-search-results) op basis van een `Expired` status van het element. Daarnaast kunt u een datumbereik voor de vervaldatum voor elementen opgeven om de zoekresultaten verder te filteren.

De vervaldatum van het element instellen:

1. Selecteer het element en klik op **[!UICONTROL Details]** in de werkbalk.

1. In de **[!UICONTROL Basic]** de vervaldatum voor het element in met de  **[!UICONTROL Expiration date]** veld.

De `Expired` de indicator van de activakaart treedt `Approved` of `Rejected` voor een element ingestelde indicator.

U kunt ook elementen filteren op basis van een elementstatus. Zie voor meer informatie [Middelen zoeken in Assets Essentials](search.md).

## Metagegevensformulieren aanpassen om het statusveld voor elementen op te nemen {#customize-asset-status-metadata-form}

**Vereiste machtigingen:** Beheerder

Assets Essentials bieden standaard veel standaardvelden voor metagegevens. Organisaties hebben extra behoeften aan metagegevens en hebben meer metagegevensvelden nodig om bedrijfsspecifieke metagegevens toe te voegen. Met metagegevensformulieren kunnen bedrijven aangepaste metagegevensvelden toevoegen aan het element [!UICONTROL Details] pagina. De bedrijfsspecifieke metagegevens verbeteren het beheer en de ontdekking van de bedrijfsmiddelen.

Zie voor meer informatie over het toevoegen van extra metagegevensvelden aan het metagegevensformulier [Metagegevens Forms](metadata.md##metadata-forms).

**Veld voor metagegevens van elementstatus toevoegen aan het formulier**

Als u een metagegevensveld voor de elementstatus aan het formulier wilt toevoegen, sleept u **[!UICONTROL Asset Status]** van de linkerspoorstaaf naar het formulier. De toewijzingseigenschap wordt automatisch vooraf ingevuld. Sla het formulier op om de wijzigingen te bevestigen.

**Metagegevensveld Vervaldatum toevoegen aan het formulier**

Als u het metagegevensveld Vervaldatum aan het formulier wilt toevoegen, sleept u **[!UICONTROL Date]** van de linkerspoorstaaf naar het formulier. Opgeven **Vervaldatum** als het etiket en `pur:expirationDate` als de toewijzingseigenschap. Sla het formulier op om de wijzigingen te bevestigen.

## Volgende stappen {#next-steps}

* [Een video bekijken om elementen in Assets Essentials te beheren](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/managing.html)

* Feedback geven op het product met de [!UICONTROL Feedback] optie beschikbaar in de gebruikersinterface van Assets Essentials

* Documentfeedback geven met [!UICONTROL Edit this page] ![de pagina bewerken](assets/do-not-localize/edit-page.png) of [!UICONTROL Log an issue] ![een GitHub-probleem maken](assets/do-not-localize/github-issue.png) beschikbaar op de rechterzijbalk

* Contact [Klantenservice](https://experienceleague.adobe.com/?support-solution=General#support)
