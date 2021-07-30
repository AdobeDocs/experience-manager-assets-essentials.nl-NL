---
title: Release-opmerkingen
description: Opmerkingen bij de release en bekende problemen van [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: fd95cf87ae8e5449471cd580405b228c32ede264
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 0%

---


# Opmerkingen bij de release van [!DNL Assets Essentials] {#release-notes}

De huidige release is de eerste openbare release van [!DNL Assets Essentials] die op 21 juni 2021 beschikbaar is gesteld. [!DNL Assets Essentials] biedt lichte mogelijkheden voor middelenbeheer en de eerste versie ervan ondersteunt de volgende belangrijke functies en CRUD-bewerkingen (maken, lezen, bijwerken en verwijderen):

* Upload en voeg elementen toe, waaronder geneste mappen. Geef een voorvertoning weer van de elementen en versies.
* Volledige-tekstonderzoek, genummerde onderzoeksfilters, en bewaarde onderzoeken voor snelle activaontdekking.
* Basisbewerkingen voor middelenbeheer, zoals het bijwerken, verwijderen, downloaden en beheren van metagegevens.
* Integratie met [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

[!DNL Assets Essentials] is momenteel beschikbaar voor [[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html) klanten.

Voor meer informatie over de oplossing, zie [inleiding aan  [!DNL Assets Essentials]](introduction.md). Zie [Aan de slag](/help/get-started.md) om de functies te gaan gebruiken.

## Huidige release {#release-notes-current}

De huidige release van Assets Essentials is 2021.7.0, uitgebracht op 29 juli 2021, met de volgende updates:

* U kunt aangepaste metagegevensformulieren maken en beheren die worden gebruikt voor de weergave van eigenschappen van metagegevens voor gebruikers in het scherm met de bestandsdetails in de optie [!UICONTROL Metadata Forms] onder [!DNL Settings].
* Verschillende opgeloste problemen en productverbeteringen, waaronder betere prestaties bij het uploaden van een geneste map met veel submappen.

## Bekende problemen {#known-issues}

De lijst met bekende problemen van [!DNL Assets Essentials]-aanbiedingen wordt voortdurend herzien en bijgewerkt:

* Als u een map of elementen wilt uploaden en de items naar een map met submappen in de opslagplaats sleept, wordt het uploaden automatisch naar een van de submappen uitgevoerd. De oplossing is om op [!DNL Upload assets] optie te klikken en in de dialoog te slepen. <!-- CQ-4327753 -->
* Nadat u de map hebt geüpload, worden nieuwe mappen soms onjuist weergegeven in de linkerrails in plaats van weer te geven in de boomstructuurweergave. De oplossing is de browser te vernieuwen. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

Als u problemen of zelfs verbeteringsverzoeken tegenkomt, [geef feedback](#provide-feedback) aan het team.
