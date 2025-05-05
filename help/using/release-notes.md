---
title: Release-opmerkingen
description: Opmerkingen bij de release en bekende problemen van  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 323e1ebd3ee81dfae0d15dc4120997ae3c4798b9
workflow-type: tm+mt
source-wordcount: '2964'
ht-degree: 0%

---

# Opmerkingen bij de release van [!DNL Assets Essentials] {#release-notes}

De huidige release van Assets Essentials wordt gepubliceerd op 25 juli 2024.

Enkele onlangs toegevoegde eigenschappen omvatten:

**de integratie van Content credentials**

Experience Manager Assets ondersteunt nu content credentials voor ondersteunde afbeeldingsindelingen. Dit biedt informatie over de relatie tussen het actief en de manier waarop het is gemaakt, inclusief of het is gewijzigd met behulp van GenAI.

![ Content credentials ](/help/using/assets/content-credentials.png)

**Visuele voorproeven van omslaginhoud**

Experience Manager Assets geeft nu visuele voorvertoningen van de inhoud van de map weer op de miniatuur van de map wanneer u naar inhoud bladert of zoekt, waardoor de beschikbare middelen in de AEM Assets-opslagruimte beter kunnen worden ontdekt.

**Contextual Onderzoek**

U kunt nu ook de middelen zoeken die beschikbaar zijn in de repository door tekstherinneringen te definiëren. Experience Manager Assets transformeert automatisch die tekstherinneringen om filters te zoeken en toont de onderzoeksresultaten. Met het deelvenster Filters kunt u automatische filters weergeven en wijzigen om de zoekresultaten verder te beperken.

![ de inzichten van het opslaggebruik ](/help/using/assets/contextual-search-text-prompt1.png)

<!--

**Dynamic renditions**

You can now view and download dynamic renditions (including smart crops) in Experience Manager Assets. Dynamic renditions are customized versions of image assets created in real-time to meet specific needs, such as resizing images based on device resolution or cropping to fit different aspect ratios. These renditions enable organizations to deliver personalized and optimized experiences to diverse audience needs.

![storage usage insights](/help/using/assets/renditions-view-download.png)

-->

**op plaats anders noemt voor activa en omslagen**

Experience Manager Assets biedt nu een vereenvoudigde gebruikerservaring door middel van de mogelijkheid om de naam van een element of map te wijzigen via één klik.

**Uitdrukkelijke video snelle acties**

Experience Manager Assets beschikt nu over eenvoudige en intuïtieve videobewerkingsgereedschappen, aangedreven door Adobe Express, om het hergebruik van inhoud te verbeteren en de snelheid van de inhoud te versnellen. Tot de bewerkingsopties behoren bijsnijden, bijsnijden, het formaat van een video wijzigen en het omzetten van een MP4 in een GIF-bestand.

![ gewas video met Adobe Express ](/help/using/assets/adobe-express-crop-video.png)

>[!NOTE]
> U hebt toegang tot [!DNL Adobe Express] nodig en ten minste één omgeving in AEM Assets. De omgeving kan een van de opslagruimten binnen [!DNL Assets as a Cloud Service] of [!DNL Assets Essentials] zijn.

**wijs of verwijder meta-gegevensvorm aan veelvoudige omslagen toe**

Een metagegevensformulier kan nu worden toegewezen aan of verwijderd uit meerdere mappen.

**beheert toestemmingen voor privé inzamelingen**

U kunt beheerders of niet-beheerders (andere gebruikers) toestaan om toegangsniveaus voor privé inzamelingen te beheren beschikbaar in de bewaarplaats. U kunt machtigingen zoals `Can View` en `Can Edit` toewijzen aan gebruikersgroepen of gebruikers. U kunt toestemmingsbeheervoorrechten aan gebruikersgroepen ook delegeren.


**Verbeteringen die op klant worden gebaseerd terugkoppelen**

Verbeteringen en foutoplossingen op basis van feedback van klanten.


## Bekende problemen {#known-issues}

De lijst met bekende problemen van [!DNL Assets Essentials] -aanbiedingen wordt voortdurend herzien en bijgewerkt.

<!--

* Assets Essentials does not support creating Private collections.

-->


<!--* Private collections are available to creator and the users with administrator privileges. As an administrator, you cannot delegate the permissions to access the collection to other users.-->

Als u over om het even welke kwesties of zelfs verbeteringsverzoeken komt, [ verstrekt terugkoppelt ](#provide-feedback) aan het team.

## Eerdere versies {#past-releases}

### Release januari 2024 {#january-2024-release}

**Slimme lijst van gewezen personen van markeringen**

Met Assets Essentials kunt u nu lijst van gewezen personen definiëren die woorden bevat die niet als slimme tags aan elementen mogen worden toegevoegd wanneer deze naar de opslagplaats worden geüpload. Met deze functie kunt u de naleving van het merk handhaven en de inspanningen voor het reduceren van slimme tags verminderen.

![ de inzichten van het opslaggebruik ](/help/using/assets/block-tags.png)

**creeer beelden GenAI met Adobe Firefly**

Maak nieuwe afbeeldingen op basis van zoekquery&#39;s met een Adobe Firefly van de functie voor tekst naar afbeelding (licentie voor Adobe Firefly vereist).

![ de integratie van de Firefly van Assets ](/help/using/assets/assets-firefly-integration.png)

**vind Vergelijkbare Beelden**

U kunt nu eenvoudig inhoud zoeken door een afbeelding te selecteren en vergelijkbare afbeeldingen weer te geven in de Experience Manager Assets-opslagplaats.

**Ingebedde redacteur van de Adobe Express in AEM Assets**

Gebruikers met toegang tot Express beschikken nu over geïntegreerde gereedschappen voor het bewerken en maken van afbeeldingen op basis van Adobe Express en Adobe Firefly die rechtstreeks in AEM Assets beschikbaar zijn om het hergebruik van inhoud te verbeteren en de snelheid van de inhoud te versnellen.

![ wijs meta-gegevensvorm aan een omslag ](/help/using/assets/adobe-express-aem-assets.png) toe

**het gebruiksrapporten van de Opslag in Inzichten**:

Beheerders kunnen nu de rapporten over het opslaggebruik bekijken die beschikbaar zijn als onderdeel van Inzichten.

![ de inzichten van het opslaggebruik ](/help/using/assets/storage-usage-insights.png)

**Onderzoek eerste homepage configuratie**

Met Assets Essentials kunt u nu de homepage-ervaring voor uw organisatie configureren. Als u eerst zoeken selecteert als startpagina, kunt u de uitlijning van de zoekbalk, de achtergrondafbeelding en het logo voor uw organisatie configureren. Als u [!UICONTROL General Settings] kiest, wordt de standaardbestemmingspagina genegeerd. De standaardoplanding is bijvoorbeeld [!UICONTROL My Workspace] voor beheerders en [!UICONTROL Search First] voor niet-beheerders. Als u een van de opties onder Algemene instellingen kiest, geldt dat voor alle gebruikers

![ onderzoek eerste configuratie ](/help/using/assets/search-first-configuration.png)

### Release oktober 2023 {#october2023-release}

**Bulk de invoeractiva van Gegevensbron OneDrive**

De beheerders hebben nu de capaciteit om een groot aantal activa van OneDrive in AEM Assets [&#128279;](/help/using/bulk-import-assets-view.md) in te voeren.  De bijgewerkte lijst voor de ondersteunde gegevensbronnen voor bulkimport bevat Azure, AWS, Google Cloud, Dropbox en OneDrive.

![ wijs meta-gegevensvorm aan een omslag ](/help/using/assets/bulk-import-source-details.png) toe

**steun van de Entitlement van de dwars-Org voor Bibliotheken**

Experience Manager Assets stelt u nu in staat om toegang tot Creatives Cloud bibliotheken in een andere IMS-organisatie te configureren. Het maakt gemakkelijker toegang tot de recentste productoverschrijdende werkschema&#39;s tussen Creative Cloud en Experience Manager mogelijk en vermindert tijd en moeite voor creatieve personen.

### Release september 2023 {#september2023-release}

**wijs meta-gegevensvorm aan een omslag** toe

U kunt nu een metagegevensformulier toewijzen aan een specifieke map in de implementatie van Assets Essentials. Alle elementen in de map, inclusief de elementen in de submappen, geven vervolgens de eigenschappen weer die in het toegewezen metagegevensformulier zijn gedefinieerd.

![ wijs meta-gegevensvorm aan een omslag ](/help/using/assets/assign-to-folder.png) toe

**Bulk de invoeractiva van gegevensbronnen**

Beheerders kunnen nu een groot aantal elementen uit een gegevensbron importeren in AEM Assets. De beheerders hoeven geen afzonderlijke elementen of mappen meer te uploaden naar AEM Assets. Tot de ondersteunde gegevensbronnen voor bulkimport behoren Azure, AWS, Google Cloud en Dropbox.

![ Bulk invoert activa van een gegevensbron ](/help/using/assets/bulk-import.png)

**Beeld die hulpmiddelen uitgeven door Adobe Express** worden aangedreven

Eenvoudig en intuïtief gereedschap voor het bewerken van afbeeldingen, aangedreven door Adobe Express die rechtstreeks in AEM Assets beschikbaar is, om het hergebruik van inhoud te verhogen en de snelheid van de inhoud te versnellen.

![ Beeld dat met Adobe Express ](/help/using/assets/edit-adobe-express.png) uitgeeft

**Flexibiliteit terwijl het knijpen van punten voor Mijn Snelle Toegang van Workspace**

De mogelijkheid om items voor u, voor uw hele organisatie of voor een lijst met groepen te selecteren en vast te zetten, zodat deze in de sectie Snelle toegang van Mijn Workspace worden weergegeven op basis van uw selectie.

![ Vastzetten punten voor groepen ](assets/pin-items-for-groups.png)


### Release juli 2023 {#july2023-release}

**Verbeterd kunstmatig intelligentiekader voor beeld Slimme Markeringen**

Experience Manager Assets maakt nu gebruik van een verbeterd kunstmatig intelligentiekader voor slimme tags voor afbeeldingen. Deze inhoudsinfo geeft een betere relevantie en nauwkeurigheid van slimme tags die beschikbaar zijn voor alle afbeeldingselementen bij opname.

**vorm vertoning van kolommen voor de mening van de Lijst van Assets**

Met Assets Essentials kunt u nu de kolommen selecteren die in de lijstweergave van Assets worden weergegeven, zoals Status, Indeling, Dimensionen, Grootte, enzovoort.

![ vorm kolommen ](/help/using/assets/configure-columns.png)

**de onderzoeksresultaten van de Soort die op relevantie** worden gebaseerd

Assets Essentials sorteren nu standaard de zoekresultaten op Relevantie. U kunt de gezochte elementen in toenemende of afnemende volgorde van `Name`, `Relevance`, `Size`, `Modified` en `Created` sorteren.

### Release juni 2023 {#june2023-release}

**Hiërarchische het etiketteren van activa voor snellere onderzoekservaring**

Vlakke lijsten met gecontroleerde woordenboeken worden in de loop der tijd onbeheersbaar. Assets Essentials ondersteunen nu de hiërarchische coderingsstructuur, die het toepassen van relevante metagegevens, het indelen van elementen, het ondersteunen van zoeken, het hergebruiken van tags, het verbeteren van de ontdekkingsmogelijkheden, enzovoort, vergemakkelijkt.

![ het Taggen Beheer ](assets/tags-hierarchy.png)

**Vastzetten dossiers, omslagen, en inzamelingen voor snelle toegang**

U kunt nu bestanden, mappen en verzamelingen vastzetten zodat u deze items sneller kunt openen wanneer u ze later nodig hebt. De vastgezette punten tonen in de **Snelle toegang** sectie van Mijn Workspace. U kunt ze openen met Mijn Workspace in plaats van naar de locatie te navigeren waar ze zijn opgeslagen in de repository.

![ Taken in Workspace ](assets/quick-access.png)

**de activa van de Filter in de omslag van het Afval**

Met Assets Essentials kunt u nu de middelen filteren die beschikbaar zijn in de map Prullenbak. U kunt standaard- of aangepaste filters toepassen om te zoeken in de juiste middelen in de map met prullenmand om deze te herstellen of permanent te verwijderen.

**de voorproeven van de Duimnagel voor 3D activa**

Assets Essentials genereren nu miniatuurvoorvertoningen voor veelgebruikte 3D-bestandsindelingen, zoals gLB, USDz, FBX, 3DS, OBJ en SBSAR. Wanneer deze bestanden naar Assets Essentials worden geüpload, worden automatisch miniaturen gegenereerd door het systeem.

![ Taken in Workspace ](assets/3d-preview.png)

**hoogste gezochte termijnen van de Mening**

Assets Essentials steunen nu het bekijken van hoogste gezochte termijnen binnen uw plaatsing van Assets Essentials gebruikend de **sectie van Inzichten** van Mijn Workspace. U kunt ook naar gedetailleerde inzichten navigeren om de belangrijkste zoekopdrachten in de afgelopen 30 dagen of 12 maanden weer te geven.

![ Taken in Workspace ](assets/insights-top-searches.png)

**de vormverhogingen van meta-gegevens**

Met Assets Essentials kunt u nu tekst met meerdere waarden en vervolgkeuzelijsteigenschappen toevoegen aan de metagegevensformulieren.

### Meerdere releases in 2023 {#multiple-releases-2023}

De lijst met onlangs toegevoegde functies bevat:

**Hoogste gedownloade activa**

Mijn Workspace geeft nu de tien meest gedownloade middelen voor uw Assets Essentials-omgeving weer in de sectie [!UICONTROL Content] . U kunt ook het formaattype en het aantal downloads voor elk vermeld element bekijken.

**Bulk updates aan activa meta-gegevens**

Met updates van bulkmetagegevens kunt u algemene updates van metagegevens tegelijkertijd op meerdere elementen uitvoeren. U hoeft de records niet afzonderlijk bij te werken en kunt snel eigenschappen toepassen op elementen of mappen die via de zoekopdracht worden benaderd. Bovendien overschrijft updates van bulkmetagegevens alle bestaande waarden. Dit betekent dat bestaande trefwoorden worden overschreven door de update voor metagegevens van bulkgegevens.

**Mijn Workspace met configureerbare widgets**

Assets biedt nu een aangepaste werkruimte voor u, die fungeert als een one-stop oplossing voor eenvoudige toegang tot belangrijke gebieden van de Assets-gebruikersinterface en informatie die voor u het meest relevant is. Snellere toegang tot deze opties verhoogt de snelheid en efficiëntie van de inhoud van uw projecten.

Mijn Workspace bevat widgets voor Inzichten, Taken en Inhoud. U kunt bepalen hoe deze widgets in uw Workspace worden weergegeven op basis van uw voorkeuren.

**Speciale interface van het taakbeheer**

Met de Assets Essentials kunt u nu de lijst met taken beheren die u momenteel hebt toegewezen, die door u zijn gemaakt en die u al hebt voltooid op een gecentraliseerde locatie. Hiervoor gebruikt u de nieuwe optie **[!UICONTROL Tasks]** die beschikbaar is in het linkernavigatievenster. U kunt ook de juiste handelingen uitvoeren door een taak te selecteren om deze goed te keuren of af te wijzen of door de taakdetails te openen om deze goed te keuren, af te wijzen, te bewerken of te verwijderen.

![ Taken in Workspace ](assets/tasks-workspace.png)

**Auto-geproduceerde verbindingen om activa** te delen

Assets Essentials genereren nu automatisch een koppeling zodra u een element deelt via de gebruikersinterface van Assets Essentials. De gegenereerde koppeling blijft ook geldig als u de vervaldatum wijzigt.

![ Taken in Workspace ](assets/share-asset.png)


**Verbeteringen die op klant worden gebaseerd terugkoppelen**

Verbeteringen en foutoplossingen op basis van feedback van klanten.

### 2022 11,0 {#november-2022}

De release van november van [!DNL Assets Essentials] wordt uitgebracht op 17 november 2022.

Deze release biedt:

**de documenten van de Voorproef gebruikend de Kijker van het Document Cloud**

Met Assets Essentials kunt u nu documenten in andere ondersteunde indelingen uploaden en deze voorvertonen met de inbegrepen viewer voor Documenten Cloud. Tot de ondersteunde indelingstypen behoren TXT, RTF, DOC, DOCX, PPT, PPTX, XLS en XLSX.

<!--

**View Smart Tags moderation reports**

Asset reporting now provides administrators with visibility into the Smart Tags promoted or deleted for an asset. You can specify a folder path and the report lists the Smart Tags promoted or deleted for all assets available at the folder path.

-->

<!--
**Read-only access to large number of users**

Assets Essentials allows administrators to provide read-only access to a large number of users for selected assets or folders in the repository. 
You can easily synchronize the user groups available on the external identity management of an organization with Adobe Admin Console and then manage permissions in Admin Console and Assets Essentials to provide the users with read-only access for selected assets or folders.

-->


**Nieuwe sparen meta-gegevensoptie**

Er is nu een nieuwe optie voor metagegevens opslaan beschikbaar in de gebruikersinterface van Assets Essentials voor een beter beheer van metagegevens.

**Verbeteringen die op klant worden gebaseerd terugkoppelen**

Verbeteringen en foutoplossingen op basis van feedback van klanten.

**versie 3.3 van de Verbinding van Activa van de Adobe**

[&#128279;](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html) versie 3.3 van de Verbinding van Activa van de Adobe van 0&rbrace; wordt vrijgegeven op 13 december 2022, met de volgende eigenschappen:

* Steun voor [ Creative Cloud voor teams ](https://www.adobe.com/creativecloud/business/teams.html) naast het steunen van [ Creative Cloud voor onderneming ](https://www.adobe.com/creativecloud/business/enterprise.html) voordien.

* Ondersteuning voor de nieuwste Adobe InDesign-, Photoshop- en Illustrator 2023-toepassingen.

* Ondersteuning voor het gebruik van de Adobe Asset Link CEP-insteekmodule in omgevingen met proxyservers.

### 2022,8,0 {#august-2022}

De release van [!DNL Assets Essentials] in augustus wordt uitgebracht op 22 augustus 2022.

Deze release biedt:

**Meldingen voor inzamelingen**

Met meldingen over Assets Essentials kunt u nu de bewerkingen controleren die worden uitgevoerd op de verzamelingen die beschikbaar zijn in de opslagplaats. U moet de verzamelingen waarvoor de meldingen naar u worden verzonden selecteren en er een abonnement op nemen. U kunt ook de bewerkingen configureren waarvoor de meldingen worden verzonden, zoals bewerkingen voor het verwijderen, delen van koppelingen, verplaatsen, hernoemen en bijwerken van verzamelingen.

**geef Slimme Verzamelingen** uit

Assets Essentials bieden nu ook de mogelijkheid om de gebruikte zoekcriteria te bewerken tijdens het maken van een slimme verzameling.  Sla de nieuwe zoekcriteria op om de inhoud van de verzameling dynamisch bij te werken.

**levende statistieken van de Mening voor opslagrekening**

Met de Assets Essentials kunt u nu ook realtime opslagaccountgegevens voor uw Assets Essentials-omgeving bekijken met het dashboard Actieve statistieken. U kunt real-time gebeurtenismetriek voor de laatste 30 dagen of voor de laatste 12 maanden bekijken.

**Mening uploadt rapporten**

Middelenrapportage biedt beheerders nu inzicht in elementen die zijn geüpload naar de Adobe Experience Manager Assets Essentials-implementatie. Beheerders kunnen al rapporten genereren voor de elementen die zijn gedownload van de implementatie van Assets Essentials. Deze gegevens bevatten nuttige informatie over de manier waarop gebruikers met inhoud en het product werken.

**Verbeteringen die op klant worden gebaseerd terugkoppelen**

Verbeteringen en foutoplossingen op basis van feedback van klanten.

### 2022,6,0 {#june-2022}

De release van [!DNL Assets Essentials] in juni wordt uitgebracht op 14 juli 2022.

Deze release biedt:

**Slimme Verzamelingen**

Sla de zoekresultaten op als een slimme verzameling om de inhoud van de verzameling dynamisch bij te werken. Als er activa aan de gegevensopslagplaats worden toegevoegd die de onderzoekscriteria passen die terwijl [ worden bepaald die tot de Slimme Inzameling ](manage-collections.md#create-smart-collection) leiden, wordt de inhoud van de Slimme Inzameling automatisch bijgewerkt.

**Meldingen**

De berichten van Assets Essentials laten u toe om [ de verrichtingen te controleren die op de activa of de omslagen beschikbaar in de bewaarplaats ](manage-notifications.md) worden uitgevoerd. U moet de inhoud selecteren en zich erop abonneren waarvoor de meldingen naar u worden verzonden. U kunt ook de categorieën configureren waarvoor de meldingen naar u worden verzonden.

**Meldend**

Met Asset Reporting kunnen beheerders de gebruikersactiviteit binnen Adobe Experience Manager Assets Essentials beoordelen. De rapporten en het levende statistiekdashboard verstrekken nuttige informatie over hoe de gebruikers met activa in uw plaatsing in wisselwerking staan. [ gebruik de informatie in de rapporten ](manage-reports.md) om zeer belangrijke succesmetriek af te leiden om de goedkeuring van Assets binnen uw onderneming en door klanten te meten.

U kunt rapporten over het downloaden van middelen en de dashboardmodule voor live statistieken weergeven om te zien welke elementen worden gedownload en hoe vaak het downloaden plaatsvindt.

### 2022,5,0 {#may-2022}

De release van mei van [!DNL Assets Essentials] wordt uitgebracht op 16 juni 2022.

Deze release biedt:

{de verhogingen van de Status van activa 0} **&#x200B;**

* De Assets Essentials laten u nu toe om [ een vervaldatum voor activa ](manage-organize.md#set-asset-status) te plaatsen. Bovendien kunt u [ filteractiva ](search.md#refine-search-results) filtreren die op de `Expired` activastatus en een waaier van de vervaldatum worden gebaseerd.

* U kunt nu de statusindicator van het element weergeven voor alle middelen die beschikbaar zijn in de prullenbak. Hierdoor kunt u een beslissing nemen om een element te herstellen op basis van de status.

**de filterverhogingen van het Onderzoek**

* De Assets Essentials laten u nu toe [ filteractiva ](search.md#refine-search-results) gebruikend de `No Status` activastatus.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**de verhogingen van Inzamelingen**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials steunen nu [ het downloaden van een inzameling ](manage-collections.md).

* U kunt nu het metagegevensveld Beschrijving voor een verzameling bewerken.

**Verbeteringen van de Documentatie**

* Een nieuwe versie van de [ documentatie van het overzicht van Assets Essentials ](introduction.md) is nu beschikbaar.

**Verbeteringen die op klant worden gebaseerd terugkoppelen**

* Verbeteringen en foutoplossingen op basis van feedback van klanten.

### 2022,4,0 {#april-2022}

De huidige release van [!DNL Assets Essentials] wordt uitgebracht op 12 mei 2022. Deze release biedt:

* [!DNL Assets Essentials] steunt nu [ het creëren van inzamelingen ](manage-collections.md). Een verzameling is een set elementen binnen Experience Manager Assets Essentials. Gebruik verzamelingen om elementen tussen gebruikers te delen. In tegenstelling tot mappen kan een verzameling elementen van verschillende locaties bevatten.

* De Assets Essentials laten u nu ook toe om [ douanefilters ](search.md#custom-filters) aan het gebruikersinterface toe te voegen. Vervolgens kunt u deze aangepaste filters naast de standaardfilters toepassen om de zoekresultaten te verfijnen.

* De Assets Essentials staan u nu toe om status [&#128279;](manage-organize.md#set-asset-status) op activa te plaatsen beschikbaar in de bewaarplaats.  Stel een elementstatus in om het downstreamgebruik van digitale elementen beter te beheren en te beheren.

* Verbeteringen en foutoplossingen op basis van feedback van klanten.

#### Incognitomodus in Chrome {#incognito-mode}

Met deze release optimaliseren we de prestaties van de levering van de gebruikersinterface en zijn specifieke functies in Assets Essentials - opmerkingen maken over elementen en beeldbewerking - afhankelijk van de lokale browseropslag en van cookies van derden. De incognitomodus in de Chrome-webbrowser blokkeert cookies van derden standaard. Gebruikers hebben een aantal opties om toegang te blijven krijgen tot alle mogelijkheden:

* Gebruik Chrome-profielen in plaats van Incognito-modus wanneer de gebruiker browsersessies moet scheiden

* Schakel het scherm `Block third-party cookies` in de Incognito-modus in Chrome uit

### 2022,2,0 {#march-2022}

[!DNL Assets Essentials] wordt vrijgegeven op 9 maart 2022, met de volgende updates:

* [!DNL Assets Essentials] laat u nu toe om [ een verbinding te produceren en activa met externe belanghebbenden ](share-links-for-assets.md) te delen, die geen toegang tot de [!DNL Assets Essentials] toepassing hebben. U kunt een vervaldatum voor de verbinding bepalen en dan het delen met anderen gebruikend uw aangewezen communicatie methode zoals e-mail of overseinendiensten. Ontvangers van de koppeling kunnen een voorbeeld van de elementen bekijken en deze downloaden.

* [!DNL Assets Essentials] bestaat nu uit [ een profiel van het beheerderproduct ](deploy-administer.md#add-users-to-essentials) op Admin Console naast de bestaande regelmatige en consumentengebruikersproductprofielen. Een beheerder kan nu andere gebruikers toewijzen aan het beheerdersproductprofiel.

* De Assets Essentials staan nu de beheerders toe om [ de toegangsniveaus voor omslagen te beheren beschikbaar in de bewaarplaats ](manage-permissions.md). Als beheerder, kunt u gebruikersgroepen tot stand brengen en toestemmingen aan die groepen toewijzen om toegangsniveaus te beheren. U kunt de bevoegdheden voor machtigingsbeheer ook delegeren aan gebruikersgroepen op mapniveau.

* Verbeteringen en foutoplossingen op basis van feedback van klanten.

Bovendien [!DNL Adobe Asset Link] uitbreiding voor Creative Cloud (Photoshop, Illustrator, en InDesign) vrijgegeven a [ nieuwe versie 3.2 ](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html), met prestatiesverbeteringen in de tijd van het paneelopstarten en in downloadsnelheid.


### release 2022.1.0 {#january-2022}

[!DNL Assets Essentials] wordt vrijgegeven op 3 februari 2022, met de volgende updates:

* Prestatieverbeteringen voor de [!UICONTROL Create Folder] -bewerking. <!-- CQ-4338818 -->

### release 2021.11.0 {#november-2021}

[!DNL Assets Essentials] wordt vrijgegeven op 16 december 2021, met de volgende updates:

* Adobe implementeert automatisch Assets Essentials nadat het inrichtingsproces is voltooid. De beheerders hoeven geen aanvullende stappen uit te voeren om Assets Essentials in te voeren met behulp van de gebruikersinterface van [!DNL Cloud Manager] . Deze automatische implementatie is beschikbaar voor omgevingen die na 6 januari 2022 zijn ingericht.
* De nieuwe versies van Creative Cloud stoppen die met Assets Essentials werken zijn beschikbaar op Adobe Exchange - [ de Verbinding van Activa van de Adobe voor Adobe XD v 2.1.0 ](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) en [ de Verbinding van Activa van de Adobe voor Photoshop / InDesign / Illustrator 3.1.65 ](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Verschillende foutoplossingen en productverbeteringen, waaronder bekende problemen die zich eerder hebben voorgedaan (mappen worden nu correct weergegeven in de linkernavigatiestructuur na het uploaden <!-- CQ-4337638 --> , en het uploaden via slepen en neerzetten staat de gebruiker toe de huidige map of een submap te selecteren bij het neerzetten voor uploaden <!-- CQ-4327753 --> ).

### release 2021.8.0 {#august2021}

[!DNL Assets Essentials] 2021.8.0 wordt uitgebracht op 30 augustus 2021, met de volgende updates:

* Integraties met [!DNL Adobe Workfront] waarmee [!DNL Workfront] -gebruikers hun digitale middelen kunnen beheren in de context van het beheer van hun werk.

### release 2021.7.0 {#july2021}

[!DNL Assets Essentials] 2021.7.0 wordt uitgebracht op 29 juli 2021, met de volgende updates:

* U kunt aangepaste metagegevensformulieren maken en beheren die u kunt gebruiken voor de weergave van eigenschappen van metagegevens voor gebruikers in het scherm met bestandsdetails in de optie [!UICONTROL Metadata Forms] onder [!DNL Settings] . Zie [ meta-gegevensvormen ](metadata.md#metadata-forms).
* Verschillende opgeloste problemen en productverbeteringen, waaronder betere prestaties bij het uploaden van een geneste map met veel submappen.

### 2021.6.0-release {#june2021}

De eerste versie van [!DNL Assets Essentials], die op 21 juni 2021 beschikbaar is gesteld, biedt lichte mogelijkheden voor middelenbeheer. De volgende belangrijke functies en CRUD-bewerkingen (Maken, Lezen, Bijwerken en Verwijderen) worden ondersteund:

* Upload en voeg elementen toe, waaronder geneste mappen. Geef een voorvertoning weer van de elementen en versies.
* Volledige-tekstonderzoek, genummerde onderzoeksfilters, en bewaarde onderzoeken voor snelle activaontdekking.
* Elementbeheerbewerkingen zoals het bijwerken, verwijderen, downloaden en beheren van metagegevens.
* [!DNL Assets Essentials] is beschikbaar voor [!DNL Adobe Journey Optimizer] -gebruikers om de elementen te beheren wanneer ze berichten maken.
