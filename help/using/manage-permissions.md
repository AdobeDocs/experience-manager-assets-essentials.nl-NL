---
title: Hoe te om toestemmingen voor omslagen in de Hoofdzaak van AEM Assets te beheren?
description: Met Assets Essentials kunnen beheerders de toegangsniveaus voor mappen die in de opslagplaats beschikbaar zijn, beheren. Creeer gebruikersgroepen en wijs toestemmingen aan die groepen toe om toegangsniveaus te beheren. Als beheerder, kunt u de toestemmingsbeheersvoorrechten aan gebruikersgroepen op omslag-niveau ook delegeren.
exl-id: 5ef01dbc-87c0-4013-9367-5da3774f4f20
source-git-commit: ec723ae4222254c64e8ddc2e03f8a523203f9f8a
workflow-type: tm+mt
source-wordcount: '1614'
ht-degree: 0%

---

# Machtigingen voor mappen beheren {#manage-permissions}

>[!CONTEXTUALHELP]
>id="assets_permissions_folders"
>title="Rechten beheren"
>abstract="Met [!DNL Assets Essentials] kunnen beheerders de toegangsniveaus beheren voor mappen die beschikbaar zijn in de opslagplaats. Als beheerder, kunt u gebruikersgroepen tot stand brengen en toestemmingen aan die groepen toewijzen om toegangsniveaus te beheren. U kunt de bevoegdheden voor machtigingsbeheer ook delegeren aan gebruikersgroepen op mapniveau."

Met Assets Essentials kunnen beheerders de toegangsniveaus voor mappen die in de opslagplaats beschikbaar zijn, beheren. Als beheerder, kunt u gebruikersgroepen tot stand brengen en toestemmingen aan die groepen toewijzen om toegangsniveaus te beheren. U kunt de bevoegdheden voor machtigingsbeheer ook delegeren aan gebruikersgroepen op mapniveau.

Het volgende gegevensstroomdiagram illustreert de opeenvolging van taken die u uitvoert om toestemmingen op omslagen te vormen en te beheren beschikbaar in de bewaarplaats van Assets Essentials:

![ de opties van de Toolbar wanneer u activa ](assets/permissions-management-new.png) selecteert

## Voordat u machtigingen voor mappen beheert {#before-managing-permissions}

Voordat u machtigingen voor mappen in de opslagplaats van Assets Essentials gaat beheren, moet u bepaalde taken uitvoeren, zoals het toevoegen van beheerders die een logische mapstructuur kunnen maken, gebruikersgroepen kunnen maken en mapmachtigingen voor verschillende gebruikersgroepen kunnen beheren.

### Beheerders toevoegen {#add-admin-users}

Voeg beheerders voor de toepassing van Assets Essentials toe zodat zij omslagtoestemmingen voor andere gebruikersgroepen kunnen beheren.

Beheerders toevoegen:

1. De toegang [ Admin Console ](https://adminconsole.adobe.com) voor uw organisatie, klikt **[!UICONTROL Products]** in de hoogste bar, klikt **[!UICONTROL AEM Assets Essentials]**, en klikt dan [!DNL Assets Essentials] milieu. [!DNL Assets Essentials] heeft drie productprofielen die toegang vertegenwoordigen voor beheerders, gewone gebruikers en gebruikers van consumenten.

   ![ Admin Console admin profiel ](assets/admin-console-admin-profile.png)

1. Als u een gebruiker aan een groep wilt toevoegen, klikt u op de groep Assets Essentials Beheerders, selecteert u **[!UICONTROL Add User]** , geeft u de gebruikersgegevens op en klikt u op **[!UICONTROL Save]** .

   ![ voeg gebruikers admin profiel ](assets/add-users-admin-profile.png) toe

   Wanneer u een gebruiker toevoegt, ontvangt de gebruiker een e-mailuitnodiging om aan de slag te gaan. U kunt de e-mailuitnodigingen uitschakelen in de instellingen voor het productprofiel in [!DNL Admin Console] .

1. Als u een gebruiker uit een groep wilt verwijderen, klikt u op de groep, selecteert u een bestaande gebruiker en selecteert u **[!UICONTROL Remove User]** .

### Gebruikersgroepen toevoegen {#add-user-groups}

Maak gebruikersgroepen en wijs aan deze groepen machtigingen toe om de toegangsniveaus voor mappen in de opslagplaats van Assets Essentials te beheren. Vervolgens kunt u uw gebruikers toewijzen aan de gebruikersgroepen.

![ voeg gebruikers aan groepen en productprofielen ](assets/user-groups-product-profiles.svg) toe

U kunt gebruikers aan gebruikersgroepen (1) toevoegen en [ gebruikers aan de Profielen van het Product van Assets Essentials (2) ](#add-admin-users). U kunt gebruikersgroepen echter niet rechtstreeks toevoegen aan productprofielen van Assets Essentials (3).

Voor informatie over hoe te om gebruikersgroepen te beheren, zie `Create user groups` en `Edit user groups` beschikbaar bij [ gebruikersgroepen beheren ](https://helpx.adobe.com/enterprise/using/user-groups.html).

>[!NOTE]
>
>Als uw Admin Console is ingesteld om een extern systeem te gebruiken voor het beheer van gebruikers/groepen-toewijzingen, zoals Azure- of Google-connectors, het synchronisatieprogramma van de gebruiker of de gebruikersbeheerrusten-API, worden uw groepen en gebruikerstoewijzingen automatisch geconfigureerd. Voor meer informatie, zie [ gebruikers van Adobe Admin Console ](https://helpx.adobe.com/enterprise/using/users.html).


### Gebruikers aan groepen toevoegen {#add-users-to-uesr-groups}

Nadat u gebruikersgroepen hebt gemaakt, kunt u beginnen met het toevoegen van gebruikers aan gebruikersgroepen.

Voor informatie over hoe te om het toevoegen van gebruikers aan gebruikersgroepen te beheren, zie `Add users to groups` beschikbaar bij [ gebruikersgroepen beheren ](https://helpx.adobe.com/in/enterprise/using/user-groups.html#add-users-to-groups).

### Mappenstructuur maken {#create-folder-structure}

U kunt de volgende methoden gebruiken om een mapstructuur te maken in de opslagplaats van Assets Essentials:

* Klik op de optie **[!UICONTROL Create Folder]** op de werkbalk om een lege map te maken.

* Klik **[!UICONTROL Add Assets]** optie beschikbaar in de toolbar [ uploadt een omslagstructuur beschikbaar op uw lokale machine ](add-delete.md).

Creeer een omslagstructuur die goed met de bedrijfsdoelstellingen voor de organisatie werkt. Als u een bestaande mapstructuur uploadt naar de opslagplaats van Assets Essentials, moet u de structuur controleren. Voor meer informatie, zie [ Beste praktijken voor efficiënt toestemmingsbeheer ](permission-management-best-practices.md).

## Machtigingen beheren voor mappen {#manage-permissions-on-folders}

U kunt de volgende machtigingen toewijzen aan gebruikersgroepen of gebruikers. De Adobe adviseert niet om toestemmingen aan gebruikers toe te wijzen.

| Naam bevoegdheid | Beschrijving |
|-----|------|
| Kan worden weergegeven | <ul><li>Leestoegang voor weergave en navigatie in mappen </li><li>Elementen voorvertonen</li><li>Elementen downloaden</li><li>Elementen kopiëren</li><li>Koppelingen naar elementen delen</li><ul> |
| Kan bewerken | <ul><li>Alle rechten die beschikbaar zijn voor weergavemachtigingen </li><li>Mappen maken</li><li>Mappen verwijderen</li><li>Mappen hernoemen</li><li>Elementen maken</li><li>Elementen bijwerken</li><li>Elementen verwijderen</li><li>Elementen verplaatsen</li><li>Elementen hernoemen</li><ul> |
| Eigenaar | <ul><li>Alle rechten die beschikbaar zijn voor de machtiging Kan bewerken</li><li>Machtigingen beheren voor een map en de bijbehorende submappen</li>Met deze machtiging kunnen beheerders de beheerdersrechten delegeren aan anderen voor een map en de submappen.<ul> |
| Toegang weigeren | Met Verwijderen kunt u machtigingen voor een map en de submappen weergeven, bewerken en bewerken. |

**Standaardtoestemmingen**

Alle gebruikers die zijn geverifieerd en zich kunnen aanmelden bij de toepassing Assets Essentials, beschikken aanvankelijk over `Can Edit` -machtigingen voor de opslagplaats van Assets Essentials. De beheerder kan de standaardtoestemmingen aanpassen door [ het uitgeven toestemmingen voor de volledige bewaarplaats van Assets Essentials ](#edit-permissions-entire-repository).

**Opeenvolging om omslagtoestemmingen aan gebruikersgroepen** toe te wijzen

Maak regels om mapmachtigingen toe te wijzen aan gebruikersgroepen. De opeenvolging die u gebruikt om toestemmingen aan een omslag toe te wijzen is belangrijk en beslist de toegang beschikbaar aan de gebruikersgroepen en uiteindelijk gebruikers.

Als u bijvoorbeeld de `Can View` -machtigingen voor een map toewijst aan een supergroep en vervolgens `Can Edit` -machtigingen toewijst aan de subgroep, hebben alleen de leden van de subgroep bewerkingsmachtigingen voor de map. Gebruikers van de supergroep hebben toegang tot de map.

Als u alleen aan de marketingafdeling van uw organisatie bewerkingsmachtigingen voor de `Marketing` -map moet opgeven en machtigingen voor anderen wilt weergeven, wijst u `Can View` machtigingen aan supergroep `All Authenticated Users` en `Can Edit` machtigingen aan de subgroep `Marketing` toe.

![ wijs Toestemmingen ](assets/permissions-management-groups.svg) toe

**Overerving van de Toestemming**

Assets Essentials gebruiken machtigingsovererving, waarmee u de machtigingen kunt overnemen die zijn ingesteld voor de bovenliggende map in de onderliggende map. Als de bovenliggende map bijvoorbeeld `Can View` machtigingen heeft voor de `All Authenticated Users` -groep en de onderliggende map `Can Edit` machtigingen heeft voor de `Marketing` -gebruikersgroep, kunnen alle geverifieerde gebruikers weergavemachtigingen hebben voor de onderliggende map en kan de `Marketing` -gebruikersgroep beschikken over bewerkingsmachtigingen voor de onderliggende map. De gebruikersgroep van `Marketing` heeft bewerkingsmachtigingen voor verdere niveaus van mappen onder de onderliggende map (Marketing).

![ wijs Toestemmingen ](assets/permissions-inheritance.svg) toe

>[!NOTE]
>
> Het instellen van `Deny Access` -machtigingen voor een groep op een map op een hoger niveau en het herstellen van de toegang ( `Can view` , `Can edit` of `Owner` ) voor die groep of het betreffende lid wordt niet ondersteund. Maak spaarzaam gebruik van `Deny Access` .

### Machtigingen toevoegen aan gebruikersgroepen {#add-permissions}

Groepmachtigingen toewijzen voor mappen:

1. Selecteer de map en klik op **[!UICONTROL Manage Permissions]** .

1. Geef in het dialoogvenster **[!UICONTROL Manage Permissions]** de naam van de groep of een gebruiker op in het veld **[!UICONTROL Groups & Users]** .

1. Selecteer het [ niveau van toegang ](#manage-permissions-on-folders) van de **[!UICONTROL Access]** dropdown lijst.

1. Klik op **[!UICONTROL Add]** om de machtigingen voor de gebruiker of gebruikersgroep direct te wijzigen.

1. Herhaal stap 1-3 om meer regels toe te voegen aan het dialoogvenster **[!UICONTROL Manage Permissions]** .

   ![ voeg Toestemmingen ](assets/add-permissions.png) toe

   >[!NOTE]
   >
   > De volgorde die u gebruikt om machtigingen aan een map toe te wijzen, is belangrijk en bepaalt de toegang die beschikbaar is voor de gebruikersgroepen en uiteindelijk voor gebruikers die aan de groepen zijn toegevoegd.

   Als u machtigingen voor meerdere mappen beheert, kunt u ook een andere map in het linkerdeelvenster selecteren en de machtigingen voor die map beheren.

1. Klik op **[!UICONTROL Close]**.

>[!CAUTION]
>
> Het wordt aanbevolen om machtigingen voor gebruikersgroepen te beheren in tegenstelling tot individuele gebruikers. Het instellen van de machtiging `Deny access` wordt alleen ondersteund voor gebruikersgroepen, maar niet voor individuele gebruikers.

### Machtigingen bewerken die zijn toegewezen aan gebruikersgroepen {#edit-permissions}

Machtigingen bewerken die zijn toegewezen aan gebruikersgroepen in mappen:

1. Selecteer de map en klik op **[!UICONTROL Manage Permissions]** .

1. Voor de **[!UICONTROL Manage Permissions]** dialoog, geef het [ niveau van toegang ](#manage-permissions-on-folders) van de **[!UICONTROL Access]** dropdown lijst uit.

1. [ voeg meer gebruikersgroepen of gebruikers ](#add-permissions) aan de bestaande toestemmingsregels toe, indien nodig.

1. Klik op X om de machtigingen te verwijderen die aan een gebruikersgroep zijn toegewezen.

### Machtigingen bewerken voor de gehele gegevensopslagruimte van Assets Essentials {#edit-permissions-entire-repository}

Een toepassingsbeheerder kan machtigingen voor de gehele gegevensopslagruimte voor Assets Essentials bewerken van een standaardinstelling `Can Edit` tot een ander toegangsniveau.

Om toestemmingen voor de volledige bewaarplaats van Assets Essentials uit te geven:

1. Selecteer een willekeurige map en klik op **[!UICONTROL Manage Permissions]** .

1. Klik in het dialoogvenster **[!UICONTROL Manage Permissions]** op **[!UICONTROL All Assets]** in de linkertrack.

1. [ geeft de toestemmingen ](#edit-permissions) uit en sluit de dialoog.

>[!NOTE]
>
>Een beheerder kan het machtigingsniveau van `Deny Access` voor de gehele gegevensopslagruimte van Assets Essentials niet selecteren om ervoor te zorgen dat gebruikers ten minste leestoegang tot de toepassing hebben. Op dezelfde manier hebben `All Authenticated Users` ten minste leesmachtigingen voor de gegevensopslagruimte, zelfs als de beheerder expliciet de `Can Edit` -machtigingen in het dialoogvenster [!UICONTROL Manage Permissions] verwijdert.


## Voorbeelden voor effectief machtigingsbeheer {#example-permission-management}

**Geval van het Gebruik**

* Alle voor authentiek verklaarde Gebruikers hebben meningstoegang tot de bewaarplaats.
* Teamspecifieke gebruikersgroepen hebben bewerkingsmachtigingen voor hun eigen functiespecifieke map.
* De map Legal is niet beschikbaar voor weergave aan geverifieerde gebruikers, behalve het juridische team.

Maak de volgende gebruikersgroepen in Admin Console:

* Marketing Team

* Merk Approvers Team

* Team voor projectmanagers

* Project X-team

* Juridisch team

Het volgende diagram illustreert de mappenhiërarchie en de toestemmingen die aan elke gebruikersgroep worden toegewezen:
![ wijs Toestemmingen ](assets/use-case-permissions-management.png) toe

Hieronder ziet u de toegangsniveaus voor alle gebruikersgroepen in de mappenhiërarchie:

* /All Assets: Administrator wijzigt de machtigingen op het hoofdniveau van de standaardwaarde `Can Edit` in `Can View` . Alle gebruikers kunnen mappen en elementen weergeven, maar kunnen ze niet bewerken.

* /marketing: Alle gebruikers kunnen de omslagen en zijn subfolders bekijken die op toestemmingsovererving worden gebaseerd, nochtans, heeft de de gebruikersgroep van het Team van de Marketing toestemmingen aan de omslag uitgeven.

* /brand: Alle gebruikers kunnen de omslagen en zijn subfolders bekijken die op toestemmingsovererving worden gebaseerd, nochtans, heeft de de gebruikersgroep van het Team van de Approvers van de Merk toestemmingen aan de omslag uitgeven.

* /projects: All users can view the folders and its subfolders based on permission inheritance. De gebruikersgroep van het Team van de Managers van het project heeft:

   * Machtigingen bewerken

   * Machtigingen eigenaar: Rechten voor een map en de submappen beheren.

* /projects/project-x: Alle gebruikers kunnen de omslagen en zijn subfolders bekijken. De gebruikersgroep van het Team van de Managers van het project heeft uitgeeft toestemmingen en kan toestemmingen op een omslag en zijn subfolders (de toestemmingen van de Eigenaar) beheren. De gebruikersgroep van het Team van project X heeft uitgeeft toestemmingen.

* /legal: geen van de gebruikers heeft toegang tot de map op basis van de `Deny Access` -machtigingen voor `All Authenticated Users` -groep. De gebruikersgroep Juridisch team heeft bewerkingsmachtigingen.

## Volgende stappen {#next-steps}

* [ bekijk een video om toestemmingen in Assets Essentials te beheren ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/permissions-management.html)

* Verstrek documentatie terugkoppelt gebruikend [!UICONTROL Edit this page] ![ uitgeeft de pagina ](assets/do-not-localize/edit-page.png) of [!UICONTROL Log an issue] ![ creeer een kwestie GitHub ](assets/do-not-localize/github-issue.png) beschikbaar op juiste sidebar

* De Zorg van de Klant van het contact ](https://experienceleague.adobe.com/?support-solution=General#support)[
