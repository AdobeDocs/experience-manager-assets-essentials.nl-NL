---
title: Metagegevens beheren
description: Metagegevens van elementen beheren in [!DNL Assets Essentials]
role: Business Practitioner,Leader,Administrator,Architect,Developer
contentOwner: AG
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---


# Metagegevens in [!DNL Assets Essentials] {#metadata}

Metagegevens zijn gegevens of een beschrijving van de gegevens. Uw afbeeldingen als een element kunnen bijvoorbeeld informatie bevatten over de camera waarop u hebt geklikt of over copyrightgegevens. Deze informatie is metagegevens van de afbeelding. Metagegevens zijn essentieel voor efficiënt middelenbeheer. Metagegevens zijn de verzameling van alle gegevens die voor een element beschikbaar zijn, maar hoeven niet noodzakelijkerwijs in dat element te zijn opgenomen.

Met metagegevens kunt u elementen verder indelen. Dit is handig wanneer de hoeveelheid digitale informatie toeneemt. Het is mogelijk om een paar honderd bestanden te beheren op basis van alleen de bestandsnamen, miniaturen en het geheugen. Deze aanpak is echter niet schaalbaar. Het is te kort wanneer het aantal betrokken personen en het aantal beheerde activa toenemen.

Als er metagegevens worden toegevoegd, neemt de waarde van een digitaal element toe, omdat het element

* Toegankelijker - systemen en gebruikers kunnen het gemakkelijk vinden.
* Gemakkelijker te beheren - u kunt gemakkelijker middelen met de zelfde reeks eigenschappen vinden en veranderingen op hen toepassen.
* Volledig - asset bevat meer informatie en context met meer metagegevens.

Om deze redenen beschikt u over de juiste middelen om metagegevens voor uw digitale elementen te maken, te beheren en uit te wisselen.

## De metagegevens weergeven {#view-metadata}

Als u de metagegevens van een element wilt weergeven, bladert u naar het element of doorzoekt u het element, selecteert u het element en klikt u op **[!UICONTROL Details]** op de werkbalk.

![Metagegevens van een element weergeven](assets/metadata-view1.png)

*Afbeelding: Als u een element en de bijbehorende metagegevens wilt weergeven, klikt u **[!UICONTROL Details]**op de werkbalk of dubbelklikt u op het element.*

De basismetagegevens, zoals titel, beschrijving en uploaddatum, zijn beschikbaar op het tabblad [!UICONTROL Basic]. Het tabblad [!UICONTROL Advanced] bevat meer geavanceerde metagegevens, zoals cameramodel, lensdetails en geotags. Het tabblad [!UICONTROL Tags] bevat automatisch toegepaste tags op basis van de inhoud van de afbeelding.

## Metagegevens {#update-metadata} bijwerken

U kunt een aantal metagegevensvelden handmatig bijwerken. De velden omvatten [!UICONTROL Title], [!UICONTROL Description], [!UICONTROL Author], en [!UICONTROL Keywords].

## Tags {#tags}

[!DNL Assets Essentials] gebruikt artificiële intelligentie die door  [Adobe ](https://www.adobe.com/sensei.html) Senseito wordt verstrekt automatisch relevante markeringen op al uw geupload activa toepassen. Deze labels, met de juiste naam Slimme tags, verhogen de snelheid van de inhoud van uw projecten door u te helpen snel relevante elementen te vinden. De slimme tags zijn een voorbeeld van metagegevens die niet in de afbeelding voorkomen.

De slimme tags worden toegepast in de buurt van realtime en worden gegenereerd op basis van de inhoud van de afbeelding. Wanneer u een element uploadt, wordt in de gebruikersinterface [!UICONTROL Processing] gedurende enige tijd weergegeven op de elementminiatuur. Als de verwerking is voltooid, kunt u [de metagegevens](#view-metadata) en de slimme tags weergeven.

![Slimme tags van een element weergeven](assets/metadata-view-tags.png)

*Afbeelding: Als u de slimme tags van een element wilt weergeven, klikt u **[!UICONTROL Details]**op de werkbalk of dubbelklikt u op het element.*

Slimme tags bevatten ook een betrouwbaarheidsscore als percentage. Het geeft het vertrouwen aan dat aan de toegepaste tag is gekoppeld. U kunt de automatisch toegepaste slimme tags verkleinen.

## Codes {#manually-tag} toevoegen of bijwerken

U kunt meer tags toevoegen aan uw elementen, naast de slimme tags die automatisch worden toegevoegd met de slimme service [!DNL Adobe Sensei]. Open een element voor voorvertoning, klik op [!UICONTROL Tags] en typ de gewenste trefwoorden in het veld [!UICONTROL Keywords]. Druk op Return om de tag toe te voegen. [!DNL Assets Essentials] indexeert het sleutelwoord in dichtbij echt - tijd en uw team kan spoedig de bijgewerkte activa zoeken gebruikend de nieuwe sleutelwoorden.

U kunt ook codes uit de sectie [!UICONTROL Smart Tags] verwijderen die automatisch door [!DNL Assets Essentials] aan alle geüploade elementen worden toegevoegd.

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
