---
title: Metagegevens beheren
description: Metagegevens van elementen beheren in [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: 274028a1fb224b045c047e63539a9b96b1cc4357
workflow-type: tm+mt
source-wordcount: '1213'
ht-degree: 0%

---

# Metagegevens in [!DNL Assets Essentials] {#metadata}

Metagegevens zijn gegevens of een beschrijving van de gegevens. Uw afbeeldingen als element kunnen bijvoorbeeld informatie bevatten over de camera waarop u hebt geklikt of over copyrightgegevens. Deze informatie is metagegevens van de afbeelding. Metagegevens zijn essentieel voor efficiënt middelenbeheer. Metagegevens zijn de verzameling van alle gegevens die voor een element beschikbaar zijn, maar hoeven niet noodzakelijkerwijs in dat element te zijn opgenomen.

Met metagegevens kunt u elementen verder indelen. Dit is handig wanneer de hoeveelheid digitale informatie toeneemt. Het is mogelijk om een paar honderd bestanden te beheren op basis van alleen de bestandsnamen, miniaturen en het geheugen. Deze aanpak is echter niet schaalbaar. Het is te kort wanneer het aantal betrokken personen en het aantal beheerde activa toenemen.

Als er metagegevens worden toegevoegd, neemt de waarde van een digitaal element toe, omdat het element

* Toegankelijker - systemen en gebruikers kunnen het gemakkelijk vinden.
* Gemakkelijker te beheren - u kunt gemakkelijker middelen met de zelfde reeks eigenschappen vinden en veranderingen op hen toepassen.
* Volledig - asset bevat meer informatie en context met meer metagegevens.

Om deze redenen beschikt u over de juiste middelen om metagegevens voor uw digitale elementen te maken, beheren en uit te wisselen.

## De metagegevens weergeven {#view-metadata}

Als u de metagegevens van een element wilt weergeven, bladert u naar het element of doorzoekt u het element, selecteert u het element en klikt u op **[!UICONTROL Details]** in de werkbalk.

![Metagegevens van een element weergeven](assets/metadata-view1.png)

*Afbeelding: Als u een element en de bijbehorende metagegevens wilt weergeven, klikt u op **[!UICONTROL Details]**op de werkbalk of dubbelklikt u op het element.*

De basismetagegevens, zoals titel, beschrijving en uploaddatum, zijn beschikbaar in het dialoogvenster [!UICONTROL Basic] tab. De [!UICONTROL Advanced] bevat geavanceerdere metagegevens, zoals cameramodel, lensdetails en geotags. De [!UICONTROL Tags] bevat automatisch toegepaste tags op basis van de inhoud van de afbeelding.

## Metagegevens bijwerken {#update-metadata}

U kunt een aantal metagegevensvelden handmatig bijwerken. De velden bevatten [!UICONTROL Title], [!UICONTROL Description], [!UICONTROL Author], en [!UICONTROL Keywords].

## Tags {#tags}

[!DNL Assets Essentials] maakt gebruik van kunstmatige intelligentie, verstrekt door [Adobe Sensei](https://www.adobe.com/sensei.html) om automatisch relevante tags toe te passen op alle geüploade elementen. Deze labels, met de juiste naam Slimme tags, verhogen de snelheid van de inhoud van uw projecten door u te helpen snel relevante elementen te vinden. De slimme tags zijn een voorbeeld van metagegevens die niet in de afbeelding voorkomen.

De slimme tags worden toegepast in de buurt van realtime en worden gegenereerd op basis van de inhoud van de afbeelding. Wanneer u een element uploadt, wordt de gebruikersinterface weergegeven [!UICONTROL Processing] gedurende enige tijd op de miniatuur van het element. Zodra de verwerking is voltooid, kunt u [de metagegevens weergeven](#view-metadata) en de slimme tags.

![Slimme tags van een element weergeven](assets/metadata-view-tags.png)

*Afbeelding: Als u de slimme tags van een element wilt weergeven, klikt u op **[!UICONTROL Details]**op de werkbalk of dubbelklikt u op het element.*

Slimme tags bevatten ook een betrouwbaarheidsscore als percentage. Het geeft het vertrouwen aan dat aan de toegepaste tag is gekoppeld. U kunt de automatisch toegepaste slimme tags verkleinen.

## Tags toevoegen of bijwerken {#manually-tag}

U kunt meer tags toevoegen aan uw elementen, naast de slimme tags die automatisch worden toegevoegd met de opdracht [!DNL Adobe Sensei] intelligente service. Een element openen voor een voorvertoning, klikt u op [!UICONTROL Tags]en typ de gewenste trefwoorden in het veld [!UICONTROL Keywords] veld. Druk op Return om de tag toe te voegen. [!DNL Assets Essentials] indexeert het sleutelwoord in dichtbij echt - tijd en uw team kan spoedig de bijgewerkte activa zoeken gebruikend de nieuwe sleutelwoorden.

U kunt ook tags verwijderen uit het dialoogvenster [!UICONTROL Smart Tags] sectie die automatisch wordt toegevoegd door [!DNL Assets Essentials] naar alle geüploade elementen.

## Metagegevens Forms {#metadata-forms}

>[!CONTEXTUALHELP]
>id="assets_metadata_forms"
>title="Metagegevens Forms"
>abstract="[!DNL Experience Manager Assets] biedt standaard veel standaardmetagegevensvelden. Organisaties hebben extra metagegevensvereisten en hebben meer metagegevensvelden nodig om bedrijfsspecifieke metagegevens toe te voegen. Met metagegevensformulieren kunnen bedrijven aangepaste metagegevensvelden toevoegen aan de pagina Details van een element. De bedrijfsspecifieke metagegevens verbeteren het beheer en de ontdekking van de bedrijfsmiddelen."

Assets Essentials biedt standaard vele standaardmetagegevensvelden. Organisaties hebben extra behoeften aan metagegevens en hebben meer metagegevensvelden nodig om bedrijfsspecifieke metagegevens toe te voegen. Met metagegevensformulieren kunnen bedrijven aangepaste metagegevensvelden toevoegen aan het element [!UICONTROL Details] pagina. De bedrijfsspecifieke metagegevens verbeteren het beheer en de ontdekking van de bedrijfsmiddelen. U kunt geheel nieuwe formulieren maken of een bestaand formulier opnieuw gebruiken.

U kunt metagegevensformulieren configureren voor verschillende typen elementen (verschillende MIME-typen). Gebruik dezelfde formuliernaam als het MIME-type van het bestand. Assets Essentials past het MIME-type voor geüploade elementen automatisch aan de naam van het formulier aan en werkt de metagegevens voor de geüploade elementen bij op basis van de formuliervelden.

Als een metagegevensformulier bijvoorbeeld op naam staat `PDF` of `pdf` bestaat, bevatten de geüploade PDF-documenten metagegevensvelden zoals gedefinieerd in het formulier.

Assets Essentials gebruikt de volgende reeks om te zoeken naar bestaande formuliernamen voor metagegevens om de metagegevensvelden toe te passen op de geüploade elementen van een bepaald type:

MIME-subtype > MIME-type > `default` form > Out-of-the-box form

Als een metagegevensformulier bijvoorbeeld op naam staat `PDF` of `pdf` bestaat, bevat het geüploade PDF-document metagegevensvelden zoals gedefinieerd in het formulier. Als een metagegevensformulier met de naam `PDF` of `pdf` bestaat niet. Assets Essentials komt overeen als er een metagegevensformulier met de naam bestaat `application`. Als er een metagegevensformulier met de naam `application`bevat de geüploade PDF-documenten metagegevensvelden zoals gedefinieerd in het formulier. Als Assets Essentials nog steeds geen overeenkomend metagegevensformulier vindt, wordt gezocht naar de `default` een metagegevensformulier om de in het formulier gedefinieerde metagegevensvelden toe te passen op de geüploade PDF-documenten. Als geen van deze stappen werkt, past Assets Essentials metagegevensvelden die in het formulier buiten de box zijn gedefinieerd, toe op alle geüploade PDF-documenten.

>[!IMPORTANT]
>
>Het nieuwe metagegevensformulier voor een specifiek bestandstype vervangt volledig het standaardformulier voor metagegevens dat [!DNL Assets Essentials] verstrekt. Als u een metagegevensformulier verwijdert of de naam ervan wijzigt, zijn de standaardmetagegevensvelden weer beschikbaar voor nieuwe elementen.

Ga als volgt te werk om een metagegevensformulier te maken:

1. Klik in het linkerspoor op **[!UICONTROL Settings]** > **[!UICONTROL Metadata Forms]**.

   ![metagegevensformulieren, optie in linkerzijbalk](assets/metadata-forms-sidebar.png)

1. Klikken **[!UICONTROL Create]** in de rechterbovenhoek van de gebruikersinterface.
1. Geef een naam op voor het formulier en klik op **[!UICONTROL Create]**.
1. Geef een naam op voor de tab in **[!UICONTROL Settings]** in het rechterspoor.
1. Van de **[!UICONTROL Components]** Sleep de vereiste componenten naar een tabblad in het formulier. Sleep de componenten in de gewenste volgorde.

   ![metagegevensformulieren, optie in linkerzijbalk](assets/metadata-form-new.png)

   *Afbeelding: Metagegevens maken interface met opties voor het toevoegen van componenten en optie voor het weergeven van een voorbeeld van het formulier.*

1. Geef voor elke component in het dialoogvenster een naam op in het dialoogvenster **[!UICONTROL Settings]** in de rechterspoorstaaf een kaart van de ondersteunde eigenschappen leveren.
1. Selecteer optioneel voor een component **[!UICONTROL Required]** om het metagegevensveld verplicht te maken en selecteer **[!UICONTROL Read-Only]** om het veld in het element onbewerkbaar te maken [!UICONTROL Details] pagina.
1. Klik optioneel op **[!UICONTROL Preview]** om een voorbeeld te bekijken van het formulier dat u maakt.
1. Voeg desgewenst meer tabbladen en de vereiste componenten toe aan elk tabblad.
1. Klikken **[!UICONTROL Save]** wanneer het formulier volledig is.

Bekijk deze video om de reeks stappen weer te geven:

>[!VIDEO](https://video.tv.adobe.com/v/341275)

Nadat een formulier is gemaakt, wordt het automatisch toegepast wanneer gebruikers een element van het overeenkomende MIME-type uploaden.

Als u een bestaand formulier opnieuw wilt gebruiken om een nieuw formulier te maken, selecteert u een metagegevensformulier. Klik op **[!UICONTROL Copy]** Geef een naam op in de werkbalk en klik op **[!UICONTROL Confirm]**. U kunt een metagegevensformulier bewerken om het te wijzigen. Wanneer u een formulier wijzigt, wordt dit gebruikt voor elementen die na de wijziging worden geüpload. De bestaande activa blijven ongewijzigd.

## Volgende stappen {#next-steps}

* [Een video bekijken om metagegevensformulieren te beheren in Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/metadata-forms.html)

* Feedback geven op het product met de [!UICONTROL Feedback] -optie beschikbaar in de gebruikersinterface van Assets Essentials

* Documentfeedback geven met [!UICONTROL Edit this page] ![de pagina bewerken](assets/do-not-localize/edit-page.png) of [!UICONTROL Log an issue] ![een GitHub-probleem maken](assets/do-not-localize/github-issue.png) beschikbaar op de rechterzijbalk

* Contact [Klantenservice](https://experienceleague.adobe.com/?support-solution=General#support)

<!-- TBD: Cannot create a form using the second option. Documenting only the first option for now.
To reuse an existing form to create a new form, do one of these:

* Select a metadata form and click **[!UICONTROL Copy]** from the toolbar, provide a name, and click **[!UICONTROL Confirm]**.

* Click **[!UICONTROL Create]**, select **[!UICONTROL Use existing form structure as template]** option, and select an existing form. 
-->

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
