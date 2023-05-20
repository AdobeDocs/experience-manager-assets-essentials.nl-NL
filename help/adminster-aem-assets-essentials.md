---
title: Experience Manager Assets Essentials beheren
description: Configureer de toegang tot de Assets Essentials-toepassing met behulp van de Admin Console en beheer vervolgens de taken die kunnen worden uitgevoerd nadat u zich hebt aangemeld bij de Assets Essentials-toepassing.
exl-id: ffd65741-21b7-47cd-9779-63a7903879e6
source-git-commit: a40b608ec72691c10dfbf7dff518a2cfc87d6552
workflow-type: tm+mt
source-wordcount: '1385'
ht-degree: 0%

---

# Experience Manager Assets Essentials beheren {#administer-assets-essentials}

![Voorkeur voor schakelen tussen donker en licht thema](assets/cce-assets.png)

## Doelstelling

* **Publiek**: Assets Essentials-beheerders

* **Doelstelling**: Configureer de toegang tot de Assets Essentials-toepassing met behulp van de Admin Console en beheer vervolgens de taken die kunnen worden uitgevoerd nadat u zich hebt aangemeld bij de Assets Essentials-toepassing.

## Overzicht {#overview}


[!DNL Adobe Experience Manager Assets Essentials] is provisioned door Adobe voor zijn klanten. In het kader van de levering [!DNL Assets Essentials] wordt toegevoegd aan de organisatie van een klant in [!DNL Adobe Admin Console]. Beheerders gebruiken [!DNL Admin Console] om gebruikersrechten te beheren aan [!DNL Assets Essentials] oplossing, en wijs toepassingsbeheerders aan opstellingstoestemmingen en meta-gegevensformulieren in [!DNL Assets Essentials].

Het volgende gegevensstroomdiagram illustreert de opeenvolging van taken die een beheerder moet uitvoeren om Assets Essentials te vormen en te beheren:

![Assets Essentials-beheerderstroom](assets/permissions-management-cce-next.svg)

## Toegang tot de Admin Console {#access-admin-console}

Nadat de Assets Essentials-oplossing is ingericht, ontvangt de beheerder een e-mail van Adobe. Het e-mailbericht bevat een welkomstbericht en een koppeling om aan de slag te gaan. Daarnaast start Adobe het proces om Assets Essentials automatisch te implementeren. Het implementatieproces duurt een uur.

Via de koppeling in de e-mail kunt u toegang krijgen tot en aanmelden bij [Admin Console](https://adminconsole.adobe.com). Als u beheerdertoegang tot meer dan één organisatierekening hebt, dan selecteer de aangewezen organisatie of schakelaar aan het gebruikend [organisatieselector](https://helpx.adobe.com/nl/enterprise/using/admin-console.html). Zodra het automatische plaatsingsproces volledig is, de productkaart voor [!DNL AEM Assets Essentials] is zichtbaar in de [!DNL Admin Console].

![Assets Essentials-implementatie](assets/admin-console-cards.png)

## Taken voor Admin Consoles beheren {#manage-admin-console-tasks}

Voer de volgende taken in Admin Console uit:

* [Gebruikers toevoegen aan productprofielen](#add-users-to-product-profiles)

* [Gebruikersgroepen toevoegen](#add-user-groups)

* [Gebruikers aan groepen toevoegen](#add-users-to-user-groups)

### Gebruikers toevoegen aan productprofielen {#add-users-to-product-profiles}

Voeg gebruikers toe aan productprofielen, zodat ze toegang hebben tot de Assets Essentials-toepassing.

Gebruikers toevoegen aan productprofielen:

1. Toegang [Admin Console](https://adminconsole.adobe.com) voor uw organisatie klikt u op **[!UICONTROL Products]** in de bovenste balk klikt u op **[!UICONTROL AEM Assets Essentials]** en klik vervolgens op de instantie voor [!DNL Assets Essentials]. De naam van de instantie kan anders zijn dan in de onderstaande schermafbeelding.
   >[!NOTE]
   >
   >[!DNL Cloud Manager] instance is voor speciaal admin gebruik slechts zoals het controleren van de dienststatus en het krijgen van toegang tot de dienstlogboeken en kan niet worden gebruikt om gebruikers aan het product toe te voegen. Zie voor meer informatie [beheerdershandleiding](deploy-administer.md#view-service-status-and-access-logs-view-logs).

   ![Beheerprofiel Admin Console](assets/assets-essentials-instance.png)

   [!DNL Assets Essentials] heeft drie productprofielen die toegang voor beheerders, regelmatige, en consumenten gebruikers vertegenwoordigen.

   ![Beheerprofiel Admin Console](assets/admin-console-admin-profile.png)

1. Als u een gebruiker aan het product wilt toevoegen, klikt u op een van de drie Assets Essentials-productprofielen en selecteert u **[!UICONTROL Add User]**, geef de gebruikersgegevens op en klik op **[!UICONTROL Save]**.

   ![Beheerdersprofiel voor gebruikers toevoegen](assets/add-users-admin-profile.png)

   Wanneer u een gebruiker toevoegt, ontvangt de gebruiker een e-mailuitnodiging om aan de slag te gaan. U kunt de e-mailuitnodigingen in de instellingen voor het productprofiel uitschakelen in [!DNL Admin Console].

1. Als u een gebruiker uit een groep wilt verwijderen, klikt u op de groep, selecteert u een bestaande gebruiker en selecteert u **[!UICONTROL Remove User]**.

   >[!NOTE]
   >
   >U moet een gebruiker toevoegen aan het Assets Essentials-productprofiel voor beheerders in de Admin Console om beheertaken uit te voeren in de Assets Essentials-toepassing. Deze taken omvatten [Mappenstructuur maken](#create-folder-structure), [Rechten voor mappen beheren](#manage-permissions-for-folders), en [Metagegevens Forms instellen](#metadata-forms).

### Gebruikersgroepen toevoegen {#add-user-groups}

Maak gebruikersgroepen en wijs uw gebruikers toe aan de gebruikersgroepen. Deze gebruikersgroepen zijn beschikbaar in de Assets Essentials-toepassing voor het instellen van machtigingen voor mappen.

U kunt gebruikers toevoegen aan gebruikersgroepen (1) en [gebruikers naar Assets Essentials-productprofielen (2)](#add-admin-users). U kunt gebruikersgroepen echter niet rechtstreeks toevoegen aan Assets Essentials-productprofielen (3).

![Gebruikers toevoegen aan groepen en productprofielen](assets/user-groups-product-profiles.svg)

Voor informatie over hoe te om gebruikersgroepen te beheren, zie `Create user groups` en `Edit user groups` beschikbaar op [Gebruikersgroepen beheren](https://helpx.adobe.com/enterprise/using/user-groups.html).

>[!NOTE]
>
>Als uw Admin Console is ingesteld om een extern systeem te gebruiken voor het beheer van gebruikers/groepen-toewijzingen, zoals Azure- of Google-connectors, het synchronisatieprogramma van de gebruiker of de gebruikersbeheerrusten-API, worden uw groepen en gebruikerstoewijzingen automatisch geconfigureerd. Zie voor meer informatie [Adobe Admin Console-gebruikers](https://helpx.adobe.com/enterprise/using/users.html).


### Gebruikers aan groepen toevoegen {#add-users-to-user-groups}

Nadat u gebruikersgroepen hebt gemaakt, kunt u beginnen met het toevoegen van gebruikers aan gebruikersgroepen.

Voor informatie over hoe te om het toevoegen van gebruikers aan gebruikersgroepen te beheren, zie `Add users to groups` beschikbaar op [Gebruikersgroepen beheren](https://helpx.adobe.com/in/enterprise/using/user-groups.html#add-users-to-groups).

## Assets Essentials-beheertaken beheren {#manage-assets-essentials-tasks}

Na het uitvoeren van de taken van de Admin Console, kunt u de volgende beleidstaken in de toepassing van Assets Essentials nu uitvoeren:

* [Mappenstructuur maken](#create-folder-structure)

* [Rechten voor mappen beheren](#manage-permissions-for-folders)

* [Metagegevens Forms instellen](#metadata-forms)

>[!NOTE]
>
>Om deze taken te kunnen beheren, vooral het beheren van toestemmingen, moet uw gebruiker toepassingsbeheerrechten hebben - het moet aan worden toegevoegd [Assets Essentials-productprofiel voor beheerders](#add-users-to-product-profiles).


### Mappenstructuur maken {#create-folder-structure}

U kunt de volgende methoden gebruiken om een mapstructuur te maken in de Assets Essentials-opslagplaats:

* Klik op de knop **[!UICONTROL Create Folder]** in de werkbalk kunt u een lege map maken.

* Klikken **[!UICONTROL Add Assets]** in de werkbalk beschikbaar voor [uploadt u een mapstructuur die beschikbaar is op uw lokale computer](add-delete.md).

Creeer een omslagstructuur die goed met de bedrijfsdoelstellingen voor de organisatie werkt. Als u een bestaande mapstructuur uploadt naar de Assets Essentials-opslagplaats, moet u de structuur controleren. Zie voor meer informatie [Tips en trucs voor effectief beheer van machtigingen](permission-management-best-practices.md).

Houd rekening met de volgende punten wanneer u van plan bent een mapstructuur te maken in de Assets Essentials-opslagplaats:

* Toekomstig bestuur: De mappen die worden beheerd door beheerders en de mappen die [gedelegeerd aan andere gebruikers als eigenaars](manage-permissions.md##manage-permissions-folders).

* Schaalbaar: De mappenstructuur moet voldoen aan de toekomstige behoeften van uw organisatie en moet eenvoudig schaalbaar zijn.

* Grootte: Een map mag niet te veel elementen bevatten. Dit kan tot gebruiksproblemen leiden en kan moeilijk te beheren worden.

* Intuïtief: De mapstructuur moet eenvoudig te doorbladeren zijn en intuïtief voor de eindgebruikers. Gebruikers moeten gemakkelijk kunnen zien waar ze een nieuw element in de mapstructuur kunnen uploaden.

Er zijn diverse mogelijke typen mapstructuur die u voor uw organisatie kunt gebruiken. Hieronder volgen enkele voorbeelden van gangbare mapstructuren:

![Typische mapstructuren](assets/folder-structure.svg)

### Rechten voor mappen beheren {#manage-permissions-for-folders}

Met Assets Essentials kunnen beheerders de toegangsniveaus voor mappen in de opslagplaats beheren. Als beheerder, kunt u gebruikersgroepen tot stand brengen en toestemmingen aan die groepen toewijzen om toegangsniveaus te beheren. U kunt de bevoegdheden voor machtigingsbeheer ook delegeren aan gebruikersgroepen op mapniveau.

>[!VIDEO](https://video.tv.adobe.com/v/341104)

Zie voor meer informatie [Rechten voor mappen beheren](manage-permissions.md).

### Metagegevens Forms instellen {#metadata-forms}

Assets Essentials biedt standaard vele standaardmetagegevensvelden. Organisaties hebben extra behoeften aan metagegevens en hebben meer metagegevensvelden nodig om bedrijfsspecifieke metagegevens toe te voegen. Met metagegevensformulieren kunnen bedrijven aangepaste metagegevensvelden toevoegen aan het element [!UICONTROL Details] pagina. De bedrijfsspecifieke metagegevens verbeteren het beheer en de ontdekking van de bedrijfsmiddelen. U kunt geheel nieuwe formulieren maken of een bestaand formulier opnieuw gebruiken.

U kunt metagegevensformulieren configureren voor verschillende typen elementen (verschillende MIME-typen). Gebruik dezelfde formuliernaam als het MIME-type van het bestand. Essentiële elementen komen automatisch overeen met het MIME-type voor geüploade elementen met de naam van het formulier en werken de metagegevens voor de geüploade elementen bij op basis van de formuliervelden.

Als een metagegevensformulier bijvoorbeeld op naam staat `PDF` of `pdf` bestaat, bevatten de geüploade PDF-documenten metagegevensvelden zoals gedefinieerd in het formulier.

Assets Essentials gebruikt de volgende reeks om te zoeken naar bestaande formuliernamen voor metagegevens om de metagegevensvelden toe te passen op de geüploade elementen van een bepaald type:

MIME-subtype > MIME-type > `default` form > Out-of-the-box form

Als een metagegevensformulier bijvoorbeeld op naam staat `PDF` of `pdf` bestaat, bevat het geüploade PDF-document metagegevensvelden zoals gedefinieerd in het formulier. Als een metagegevensformulier met de naam `PDF` of `pdf` bestaat niet. Assets Essentials komt overeen als er een metagegevensformulier met de naam bestaat `application`. Als er een metagegevensformulier met de naam `application`bevat de geüploade PDF-documenten metagegevensvelden zoals gedefinieerd in het formulier. Als Assets Essentials nog steeds geen overeenkomend metagegevensformulier vindt, wordt gezocht naar de `default` een metagegevensformulier om de in het formulier gedefinieerde metagegevensvelden toe te passen op de geüploade PDF-documenten. Als geen van deze stappen werkt, past Assets Essentials metagegevensvelden die in het formulier buiten de box zijn gedefinieerd, toe op alle geüploade PDF-documenten.

>[!IMPORTANT]
>
>Het nieuwe metagegevensformulier voor een specifiek bestandstype vervangt volledig het standaardformulier voor metagegevens dat [!DNL Assets Essentials] verstrekt. Als u een metagegevensformulier verwijdert of de naam ervan wijzigt, zijn de standaardmetagegevensvelden weer beschikbaar voor nieuwe elementen.

>[!VIDEO](https://video.tv.adobe.com/v/341275)

Ga voor meer informatie over Metadata Forms naar [Metagegevens Forms in Assets Essentials](metadata.md#metadata-forms).

## Volgende functies

Nu u de Assets Essentials-toepassing hebt geconfigureerd en beheerd, [Creative Cloud-toepassingen integreren met de toepassing Experience Manager Assets Essentials](integrate-assets-essentials-creative-cloud.md).
