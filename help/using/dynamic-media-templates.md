---
title: Hoe te om Dynamische malplaatjes van Media te beheren?
description: Leer hoe u Dynamic Media-sjablonen maakt met een WYSIWYG-sjablooneditor en meerdere afbeeldingen en tekstlagen opneemt om snel banners en flyers te maken en deze te gebruiken in downstreamtoepassingen.
hide: true
role: User
exl-id: 07de648e-4ae2-4524-8e05-3cf10bb6006d
source-git-commit: 8bf4babf2fefb8735b14eb4d4cb08205c54a77bb
workflow-type: tm+mt
source-wordcount: '2705'
ht-degree: 0%

---

# Dynamische mediasjablonen{#dynamic-media-templates}

| [ Beste praktijken van het Onderzoek ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices) | [ Beste praktijken van Meta-gegevens ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices) | [ Content Hub ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview) | [ de ontwikkelaarsdocumentatie van AEM Assets ](https://developer.adobe.com/experience-cloud/experience-manager-apis/) |
| ------------- | --------------------------- |---------|-----|

>[!CONTEXTUALHELP]
>id="assets_dm_templates"
>title="Dynamische mediasjablonen beheren"
>abstract="Maak en personaliseer direct afbeeldingen en tekstbanners met een gebruiksvriendelijke WYSIWYG-interface en sluit de Dynamic Media URL in een eerste of een andere toepassing in om bijzonder aantrekkelijke ervaringen te creëren. Probeer het maar eens!"
>additional-url="https://images-tv.adobe.com/mpcv3/4477/b74738ca-888c-4a37-9a9e-14fabd68ee45_1738206841.854x480at800_h264.mp4" text="Video bekijken"

Maak dynamische mediasjablonen met een WYSIWYG-sjablooneditor en voeg meerdere afbeeldingen en tekstlagen toe om snel banners en flyers te maken en deze te gebruiken in downstreamtoepassingen. U kunt parameters aan de beelden en tekstlagen ook toevoegen inbegrepen in het malplaatje en [ Dynamische Media URLs ](https://experienceleague.adobe.com/nl/docs/commerce-admin/content-design/wysiwyg/storage/catalog-urls-dynamic-media) gebruiken om de waarden voor die lagen in real time bij te werken.

Enkele van de belangrijkste functies zijn:

* **Dynamische Redacteur van het Malplaatje van Media WYSIWYG:** creeer klantgerichte banners met beeld en tekstlagen.
* **Parameterization van de Laag:** bepaal dynamische sleutel-waarde paren voor lagen om updates in real time toe te laten.
* **Dynamische Steun van Media URL:** Gebruik Dynamische Media URLs voor malplaatjes, die gepersonaliseerde waarden van eerste of derdetoepassingen integreren.
* **Controle van de Zichtbaarheid van de Laag:** verberg of toon dynamisch lagen zoals nodig.
* **Slimme Tekst het Randen van de Tekst:** past automatisch tekstgrootte aan om aangewezen gebieden te passen.

Enkele belangrijke voordelen van Dynamic Media-sjablonen zijn:

* **optimaliseer 1:1 Personalization:** Inhoud van de Tailor aan klantensignalen in real time.
* **Verminder Handmatige inspanning:** Automate en versnelt inhoudsverwezenlijking en beheer.
* **verzekert Consistente Ervaringen Omnichannel:** handhaaf merkconsistentie over kanalen.
* **Reuse Inhoud effectief:** vermijd enig-gebruiksinhoud en schaal met dynamische, geparametereerde malplaatjes.
* **Mitigate Risks:** update tarifering, kortingen, en verbindingen in real time.
* **verbeter de Betrokkenheid van de Klant:** aandrijving interactieve, contextafhankelijke ervaringen.

>[!NOTE]
>
>Klanten met een abonnement op de uitgebreide beveiligingsSKU kunnen geen gebruik maken van dynamische mediamogelijkheden, waaronder Dynamic Media Templates, voor dat Cloud Services-programma.

## Voordat u begint{#prerequisites-for-dynamic-media-wysiwyg-template}

Als u een sjabloon voor dynamische media wilt maken, moet u beschikken over:

1. Toegang tot dynamische media.
1. [ synchroniseerde de beelden beschikbaar in uw instantie van AEM Assets met Dynamische Media om hen te gebruiken voor het creëren van het malplaatje ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm).
1. Controleer het volgende in de aanraakinterface:
   * Op het tabblad **[!UICONTROL Edit Dynamic Media Configuration page]** wordt **[!UICONTROL Dynamic Media sync mode]** dat is ingesteld op **[!UICONTROL Disabled by default]** , niet toegepast op alle AEM-mappen (**[!UICONTROL Sync all content]** is uitgeschakeld). Zie [ vormend Dynamische Media Cloud Service ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) voor meer informatie.
   * **[!UICONTROL Dynamic Media sync mode]** wordt ingesteld op **[!UICONTROL Enable for subfolders]** voor de doelmap of -submap waarin u de sjabloon na het maken wilt opslaan. Zie [ vormend Dynamische Media Cloud Service ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) voor meer informatie.

## Dynamische media WYSIWYG-sjabloon maken{#how-to-create-dynamic-media-wysiwyg-template}

Ga als volgt te werk om een DM-sjabloon te maken:

1. [Een leeg canvas maken](#create-a-canvas)
1. [Afbeeldingen toevoegen aan het canvas](#add-images-to-the-canvas)
1. [Tekstlagen toevoegen aan het canvas](#add-text-to-the-canvas)
1. [Een laag bewerken of verwijderen](#edit-or-delete-a-layer)
1. [Lagen parametereren](#parameterise-a-layer)

### Een leeg canvas maken{#create-a-canvas}

Voer de volgende stappen uit om een leeg canvas te maken:

1. Navigeer naar Elementen en klik op **[!UICONTROL Dynamic Media Assets]** beschikbaar in het linkerdeelvenster.

   ![ Dynamische malplaatjes van Media ](/help/using/assets/DM-Assets1.png)

1. Klik op **[!UICONTROL Create Template]** om de sjabloon op te slaan onder Dynamic Media Assets of navigeer naar een map en klik op **[!UICONTROL Create Template]** om de sjabloon in die map op te slaan. Het dialoogvenster **[!UICONTROL New Template]** wordt weergegeven.
   ![ hoe te om dynamische malplaatjes tot stand te brengen die in real time kunnen worden aangepast ](/help/using/assets/new-template.png)
Om [ tot een omslag ](/help/using/add-delete.md) onder **[!UICONTROL Dynamic Media Assets]** te leiden, creeer een omslag onder **[!UICONTROL Assets]**. De mapstructuur onder **[!UICONTROL Assets]** wordt onder **[!UICONTROL Dynamic Media Assets]** overgenomen.
1. Geef een sjabloonnaam op, definieer de canvasbreedte en -hoogte en klik op **[!UICONTROL Create]** . Er wordt een leeg canvas weergegeven met menuopties aan beide zijden voor het maken van de sjabloon. Houd de muisaanwijzer boven de menuopties om de knopinfo weer te geven.
   ![ in real time aanpasbaar malplaatje ](/help/using/assets/blank-canvas-page.png)

>[!NOTE]
>
> Het toegestane breedte- en hoogtebereik ligt tussen 50 en 5000.

**opties van het Menu op de juiste ruit:** Gebruik deze opties om de noodzakelijke beelden en tekstlagen aan het canvas toe te voegen.

* ![ DM Malplaatjes ](/help/using/assets/add-image.svg): Klik om beelden aan het canvas toe te voegen.
* ![ aanpasbare malplaatjes ](/help/using/assets/add-text.svg): Klik om teksten aan het canvas toe te voegen.
* ![ aanpasbare malplaatjes ](/help/using/assets/show-layers-list.svg): Klik om de lijst van alle lagen (beeld en tekst) op het canvas te zien. Elke afbeelding en tekst die aan het canvas wordt toegevoegd, wordt weergegeven als een afzonderlijke laag.

**opties van het Menu op de linkerruit:** Gebruik deze opties voor gemeenschappelijke redacteursacties zoals hieronder vermeld.

* ![ DM Malplaatjes ](/help/using/assets/layer-selector.svg): Selecteer een laag.
* ![ creeer een malplaatje dat onmiddellijk ](/help/using/assets/undo.svg) kan worden aangepast: klik om de laatste actie ongedaan te maken of **CTRL** + **te drukken Z** (Vensters) of **Cmd** + **Z** (Mac).
* ![ malplaatje om banners snel ](/help/using/assets/redo.svg) tot stand te brengen: Klik om de laatste actie opnieuw uit te voeren of **CTRL** + **Y** (Vensters) of **Cmd** + **Y** (Mac) te drukken.
* ![ malplaatje om snel flyers ](/help/using/assets/zoomin.svg) tot stand te brengen: Klik om binnen het canvas te zoemen of **CTRL** + **+** (Vensters) of Cmd + **+** (Mac) te drukken.
* ![ malplaatje om banners snel ](/help/using/assets/ZoomOut-1.svg) tot stand te brengen: Klik om uit het canvas te zoemen of **CTRL** + **te drukken -** (Vensters) of **Cmd** + **-** (Mac).
* Pers **Backspace** of **schrapt** om de geselecteerde laag te schrappen als geen tekst of het bezit wordt uitgegeven.

Klik ![ malplaatje om snel flyers ](/help/using/assets/show-layers-list.svg) **>** meer opties (![](/help/using/assets/three-dots.svg)) op de laag van het Canvas te creëren om de canvasdimensies op elk ogenblik uit te geven terwijl het creëren van het malplaatje.
![](/help/using/assets/edit-canvas1.png)

>[!NOTE]
>
> Sjablonen staan maximaal 20 lagen toe, waaronder het canvas.

### Afbeeldingen toevoegen aan het canvas{#add-images-to-the-canvas}

Voer de volgende stappen uit om afbeeldingen aan het canvas toe te voegen:

1. Klik ![ creeer een banner in geen tijd ](/help/using/assets/add-image.svg) om het [ paneel van de Selecteur van Activa ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/manage/asset-selector/overview-asset-selector) te tonen. In het deelvenster worden de afbeeldingen weergegeven die in uw AEM Assets-instantie zijn gesynchroniseerd met Dynamic Media.
1. Blader in het deelvenster of gebruik trefwoorden in de zoekbalk om een specifieke afbeelding te zoeken.
1. Sleep een afbeelding naar het canvas om deze te gebruiken. Zie [**[!UICONTROL Properties Panel]**](#reposition-resize-delete-a-layer) voor het wijzigen van het formaat of het verplaatsen van een laag op het canvas.
   ![ creeer een banner binnen seconden ](/help/using/assets/add-image-to-canvas.png)

### Tekstlagen toevoegen aan het canvas{#add-text-to-the-canvas}

Voer de volgende stappen uit om tekstlagen aan het canvas toe te voegen:

1. Klik ![ creërend nieuwe banners geleidelijk ](/help/using/assets/add-text.svg) om een tekstlaag aan het canvas toe te voegen en het paneel van Eigenschappen te openen.
1. Selecteer de laag en klik op de tekst om deze bij te werken.
1. Schakel **[!UICONTROL Smart Text Resize]** in het deelvenster Eigenschappen in om de tekstlengte en de tekengrootte automatisch aan te passen aan de optimale grootte in het opgegeven gebied.
   ![ best klantgerichte banners ](/help/using/assets/add-text-layer.png)

Zie [**[!UICONTROL Properties Panel]**](#reposition-resize-delete-a-layer) om de laag te verplaatsen, te vergroten of te verkleinen, te roteren of te verwijderen. Maak de tekst op in het gewenste lettertype, de gewenste grootte, kleur, stijl, uitlijning (in de laag) door de waarden van de tekst te wijzigen in de desbetreffende velden onder de sectie **[!UICONTROL Text]** van het deelvenster.

>[!NOTE]
>
> Als u een ander lettertype wilt gebruiken dan de standaard Adobe Sans F2-lettertypefamilie, moet u het lettertypebestand uploaden en publiceren naar AEM Assets en Dynamic Media. Als u sommige oude doopvonten in uw instantie hebt, verzeker [ opnieuw verwerken ](/help/using/reprocessing.md) om hen in de redacteur van het Malplaatje te bekijken.

### Een laag bewerken of verwijderen {#edit-or-delete-a-layer}

Voer de volgende stappen uit om een canvaslaag te bewerken of te verwijderen:

1. Klik ![ malplaatjes met steun aan dynamische updates ](/help/using/assets/show-layers-list.svg) en selecteer de laag of op het canvas of van de lijst van Lagen.
1. Klik **meer opties** (![ malplaatjes met steun aan updates in real time ](/help/using/assets/three-dots.svg)) om de laag uit te geven of te schrappen.
1. Klik op **[!UICONTROL Delete]** om de laag te verwijderen.
1. Klik op **[!UICONTROL Edit]** om de laag te bewerken met [**[!UICONTROL Properties Panel]**](#reposition-resize-delete-a-layer) .
   ![ snelle bannerverwezenlijking ](/help/using/assets/edit-delete-layer.png)

### Deelvenster Eigenschappen{#properties-panel}

Navigeren naar het deelvenster met laageigenschappen:

1. Klik ![ snelle inhoudsverwezenlijking ](/help/using/assets/show-layers-list.svg).
1. Selecteer de laag in de lijst.

In dit deelvenster worden de positie van het middelpunt van de laag op het canvasvlak (X- en Y-waarden) en de afmetingen van de laag (breedte en hoogte) weergegeven, samen met tekstopmaakopties.

![ snelle inhoudsverwezenlijking ](/help/using/assets/properties-panel.png)

Selecteer in het deelvenster Eigenschappen van een laag een andere laag op het canvas om naar het deelvenster met eigenschappen te navigeren.


#### Een laag verplaatsen, vergroten, verkleinen, roteren of verwijderen{#reposition-resize-delete-a-layer}

Zie de volgende algemene handelingen voor het bewerken van lagen om tekst of een afbeeldingslaag te bewerken:

* **verplaats de laag:** sleep de laag om het overal op het canvas te bewegen. Met deze actie worden de X- en Y-waarden in het deelvenster Eigenschappen bijgewerkt.
* **resize de laag:** selecteer de laag en sleep zijn randhandvatten om het te resize. Met deze handeling worden de waarden voor B (breedte) en H (hoogte) in het deelvenster Eigenschappen bijgewerkt.
* **roteer de laag:** sleep het vierkante handvat dat verticaal boven de laag wordt geplaatst om het rond zijn centrum te roteren. Met deze handeling worden de hoekwaarden in het deelvenster Eigenschappen bijgewerkt.
* **Schrap de laag:** Pers **Backspace** of **schrapt** en klikt dan **[!UICONTROL Confirm]** om een geselecteerde laag te schrappen.

#### Opties voor tekstopmaak{#text-formatting-options-on-properties-panel}

Maak de tekst op in het gewenste lettertype, de gewenste grootte, kleur, stijl, uitlijning (in de laag) door de waarden van de tekst te wijzigen in de desbetreffende velden onder de sectie **[!UICONTROL Text]** van het deelvenster.

**[!UICONTROL Smart Text Resize]** verzeker om **[!UICONTROL Smart Text Resize]** ([ te omvatten passend maken ](https://experienceleague.adobe.com/nl/docs/dynamic-media-developer-resources/image-serving-api/image-serving-api/http-protocol-reference/text-formatting/r-copy-fitting)) om het even welke tekst in het aangewezen gebied optimaal te passen door zijn doopvontgrootte en lengte slim aan te passen. Zo voorkomt u tekstoverloop of minimaliseert u extra spaties onder aan de tekst.
![ inhoudsverwezenlijking in geen tijd ](/help/using/assets/smart-text-resize.png)

### Lagen parametereren {#parameterise-a-layer}

Nadat u een sjabloon met meerdere lagen afbeeldingen en tekst hebt gemaakt, kunt u de parameters van de geselecteerde lagen bepalen. Wanneer een laag of zijn bezit wordt bepaald, krijgt het een zeer belangrijk-waardepaar (ook genoemd als parameter). Deze parameter kan in het malplaatje URL worden omvat om de positie, de grootte of de inhoud van de laag in echt bij te werken - tijd resulterend in malplaatjeaanpassing in geen tijd.

U kunt als volgt een laag bepalen:

1. klik ![ onmiddellijke inhoudsverwezenlijking ](/help/using/assets/show-layers-list.svg), selecteer een laag en klik **[!UICONTROL Parameters]**. Het deelvenster **[!UICONTROL Parameters]** wordt weergegeven.
1. Schakel **[!UICONTROL Include Parameter]** in om een eigenschap te bepalen. Zie [ dit ](#parameterisation-options-or-allowed-parameters) om het gedrag van het bezit na parameterization te kennen.
1. **Facultatief:** noem de parameternaam anders. Een parameternaam heeft een laagnaam gevolgd door een achtervoegsel. Voor een geselecteerde laag delen alle eigenschappen met parameters dezelfde laagnaam, gevolgd door een variërend achtervoegsel. Wijzig de naam van de laag door de semantische noemende overeenkomst te volgen zodat wanneer u de parameter in URL omvat, de parameternaam zelf over de inhoud van de laag of zijn doel verklaart.
1. Klik op **[!UICONTROL Save]**.
   ![ onmiddellijke inhoudsverwezenlijking ](/help/using/assets/parameterise-a-layer.png)
Als u wilt schakelen tussen het deelvenster Parameter van een afbeelding en een tekstlaag, selecteert u de laag op het canvas en klikt u op **[!UICONTROL Parameters]** .

#### Opties in het deelvenster Parameters {#parameterisation-options-or-allowed-parameters}

De parameters van eigenschappen kunnen als parameters URL in het malplaatje URL worden omvat om het malplaatje in echt uit te geven - tijd gebruikend URL.

**parameters van het Beeld:**

**X:** omvat om de laag horizontaal langs zijn middellijn, parallel aan de x-as van het malplaatjevlak te bewegen, door de waarde van de parameter in URL te veranderen.
**Y:** omvat om de laag verticaal langs zijn centrumlijn, parallel aan de y-as van het malplaatjevlak te bewegen, door de waarde van de parameter in URL te veranderen.
**Breedte:** omvat om de breedte van de laag aan te passen door de waarde van de parameter in URL te veranderen.
**Hoogte:** omvat om de hoogte van de laag aan te passen door de waarde van de parameter in URL te veranderen.
**Verbergen:** omvatten om de laag in het malplaatje te verbergen of te tonen gebruikend 0 (toon) en 1 (verberg).
**Source:** omvat om het beeld van de laag met nieuw beeld te vervangen door de beeldweg in de waarde van de parameter in URL te veranderen.

**het formatteren van de Tekst parameters:**

Neem de onderstaande parameters op om de tekst, het lettertype, de kleur en de grootte van de tekst vanuit de URL te bewerken door de parameterwaarden in de URL bij te werken.

**Tekst:** omvat om tekst van URL bij te werken.
**Familie van de Doopvont:** omvat om de doopvont van de tekst van URL bij te werken.
**Grootte van de Doopvont:** omvat om de de doopvontgrootte van de tekst van URL bij te werken.
**kleur van de Tekst:** omvat om de de doopvontkleur van de tekst van URL bij te werken.

### Lagen groeperen om de zichtbaarheid ervan tegelijk te regelen{#group-layers}

Een andere manier om uw malplaatjes flexibel te houden, is door één enkele parameternaam te gebruiken om veelvoudige lagen te controleren. Deze strategie is handig voor de zichtbaarheidsparameter (lagen verbergen of weergeven) om het ontwerp of de afbeeldingen van één sjabloon bij te werken.

Volg deze stappen om de zelfde naam aan de huidenparameters (![ toe te wijzen snelle inhoudsverwezenlijking ](/help/using/assets/Visibility-icon.svg)) van veelvoudige lagen, toestaand u om hen gelijktijdig te verbergen of te tonen.

1. Navigeer naar de [**[!UICONTROL Properties Panel]**](#parameterise-a-layer) van een laag.
1. Schakel de parameter **[!UICONTROL Hide]** in als deze niet eerder is geparametereerd.
1. **Facultatief:** noem de Parameter van de Verbergen anders.
1. Kopieer de naam Parameter verbergen.
1. Ga naar het deelvenster Parameter van andere lagen door deze op het canvas te selecteren en schakel de parameter **[!UICONTROL Hide]** ervan in of u de parameters niet wilt wijzigen.
1. Vervang de naam **[!UICONTROL Hide parameter]** ervan door de gekopieerde naam.
1. Klik op **[!UICONTROL Save]** om de lagen te groeperen.
1. Voer stap 3 en vervolgens 4 uit in de sectie [**[!UICONTROL Preview and Publish]**](#preview-and-publish-template-and-copy-template-deliver-url) om uw wijzigingen te zien.

## De sjabloon voorvertonen en publiceren om de leverings-URL te kopiëren{#preview-and-publish-template-and-copy-template-deliver-url}

Voer de volgende stappen uit om de sjabloon voor te vertonen en te publiceren en de URL van de levering te kopiëren:

1. Klik op **[!UICONTROL Preview]** op de canvaspagina. U kunt ook naar **[!UICONTROL Assets Essentials]** **>** **[!UICONTROL Dynamic Media Assets]** **>** zoeken navigeren en uw malplaatje selecteren **>** klikken **[!UICONTROL Edit Template]** **>** klikken **[!UICONTROL Preview]**. Op de voorvertoningspagina worden de sjabloon, de parameters (geparametereerde lagen en eigenschappen), de publicatiestatus en de optie **[!UICONTROL Publish]** weergegeven.
1. Selecteer parameters in het deelvenster **[!UICONTROL Template Parameters]** om de waarden van de parameters te bewerken en de inhoud, grootte, positie of tekstopmaak van de overeenkomstige sjabloonlaag in de voorvertoning direct bij te werken. Bijvoorbeeld:
   1. Selecteer een tekstlaag en bewerk de tekst of
   1. Selecteer een beeldlaag, klik ![ creërend inhoud op de vlucht ](/help/using/assets/add-image.svg), selecteer een beeld van de activaselecteur, en klik **[!UICONTROL Refresh]**.

   De sjabloon wordt onmiddellijk bijgewerkt, waarbij de bewerkte tekst wordt weergegeven en de vorige afbeelding wordt vervangen door de nieuwe. Bovendien weerspiegelt de waarde van de afbeeldingsparameter het nieuwe afbeeldingspad. Op dezelfde manier kunt u het formaat van een laag aanpassen door zijn waarden aan te passen, en de veranderingen worden toegepast op het malplaatje in echt - tijd.
1. Selecteer de huidenparameter voor [ gegroepeerde lagen ](#group-layers) van de lijst om hen samen in het malplaatje te tonen of te verbergen.
1. **Facultatief:** verander de **[!UICONTROL Hide]** parameterwaarde tussen 0 en 1 en klik **[!UICONTROL Refresh]** om de veranderingen te zien. Lagen met dezelfde parameter hide worden samen verborgen of weergegeven. Op dezelfde manier kunt u de zichtbaarheid van lagen bepalen via de URL.

   ![ creërend inhoud op de vlucht ](/help/using/assets/dm-templates-publish-status.png)
U kunt **[!UICONTROL Include all parameters]** ook schakelen om alle weergegeven parameterwaarden te bewerken en de updates in de sjabloonvoorvertoning te bekijken.
   <br>
1. Als u de sjabloon op de voorvertoningspagina wilt publiceren, klikt u op **[!UICONTROL Publish]** en bevestigt u dat u de sjabloon wilt publiceren. Bericht publiceren voltooid wordt weergegeven en de publicatiestatus wordt bijgewerkt naar Gepubliceerd.

>[!NOTE]
>
>Als u de sjabloon publiceert, moeten de sjabloonafbeeldingen eerst worden gepubliceerd.

### De leverings-URL kopiëren

De geselecteerde parameters op de pagina **[!UICONTROL Preview]** worden de URL-parameters in de sjabloon-URL.

U kunt als volgt de URL van de gepubliceerde sjabloon kopiëren die in de voorvertoning wordt weergegeven:

1. Klik op **[!UICONTROL Copy URL]**. Het dialoogvenster **[!UICONTROL Copy URL]** wordt weergegeven. Selecteer en kopieer de weergegeven URL. Merk op dat de eerste parameter in de URL begint na een vraagteken **(?)** en een zeer belangrijk-waardepaar beginnen met **$** en eindigen met **&amp;**. De sleutel en de waarde worden gescheiden door een gelijkteken **(=)**, met de sleutel op de linkerzijde en de waarde op het recht.
1. Plak deze URL in het browsertabblad en bekijk de live sjabloon. Pas het malplaatje in real time aan door de vereiste waarde van de parameter (de waarde van Sleutel) in URL direct bij te werken zoals aangetoond in [ stap 2 ](#preview-and-publish-template-and-copy-template-deliver-url) van **Voorproef en publiceer** sectie.
1. Gebruik deze URL voor snelle verkoop van uw producten of services. U kunt deze URL delen met uw klanten of deze integreren in uw website of een andere downstreamtoepassing van derden om de banner weer te geven en er realtime updates voor uit te voeren die de lopende aanbiedingen weerspiegelen.

Leer hoe u in deze video stap voor stap een sjabloon voor dynamische media maakt.
>[!VIDEO](https://video.tv.adobe.com/v/3443281)

## Updates in real time van de sjabloon maken via de URL{#update-the-template-from-the-url}

Het rechtstreeks bewerken van parameters in de URL kan vervelend zijn. Ter vereenvoudiging:

1. Kopieer de URL en plak deze in een blok.
1. Gebruik Cmd+F (Mac) of Ctrl+F (Windows) om de parameterwaarden te zoeken en te bewerken. Bijvoorbeeld:
   * Vervang afbeeldingspaden voor afbeeldingslagen.
   * Pas laagdimensies en posities (als [ geparameterized ](#parameterise-a-layer)) aan.
   * Bewerk tekst, lettertype, kleur, grootte of uitlijning voor tekstlagen.
   * Wijzig de zichtbaarheidswaarden tussen 0 en 1.

Plak deze bijgewerkte URL in uw browser om de wijzigingen weer te geven.

## De sjabloon bewerken{#edit-the-template}

Voer de volgende stappen uit om de sjabloon te bewerken:

1. Klik op **[!UICONTROL Dynamic Media Assets]** voor Elementen.
2. Navigeer naar de sjabloonlocatie.
3. Selecteer de sjabloon.
4. Klik op **[!UICONTROL Edit Template]**. Op het sjablooncanvas worden de sjabloon en de lijst met alle lagen in het deelvenster Lagen weergegeven. Begin uw sjabloon naar wens te bewerken.

## Belangrijke opmerkingen {#important-points-to-note}

* Nadat u een sjabloon hebt gemaakt met geparametriseerde afbeeldingslagen voor dynamische updates, zorgt u ervoor dat de afbeeldingen die u wilt bijwerken in de toekomst dezelfde afmetingen hebben als de geparametriseerde afbeeldingen. Zo kunt u ervoor zorgen dat de afbeeldingen perfect in de lagen passen zonder dat ze te veel stromen of lege ruimten overblijven. De sjabloon ondersteunt momenteel geen automatische dimensionering om afbeeldingen in de lagen te passen.
* Een tekstlaag biedt geen ondersteuning voor subtekenreeksen. De gebruiker kan geen verschillende doopvonteigenschappen op substring van een tekstlaag toepassen.
* De steun van veelvoudige Dynamische bedrijven van Media is momenteel niet beschikbaar met Dynamische Malplaatjes van Media.
* In het geval van kopiëren of verplaatsen worden in de doelkiezer alle mappen weergegeven (inclusief niet-dynamische met media gesynchroniseerde mappen). Momenteel worden de dynamische media-sjabloonelementen niet weergegeven (beide zijn beperkingen van de doelkiezer).
* Elke updatebewerking in een map (bijvoorbeeld Publiceren of Verwijderen) uit de Assets-sectie heeft invloed op de dynamische mediasjablonen in die map.
* Prullenbak werkt niet voor dynamische mediasjablonen. Als een element naar de prullenbak wordt verplaatst en vervolgens wordt teruggezet, wordt het element wel teruggezet in AEM, maar niet op Dynamic Media. Hetzelfde geldt voor dynamische mediasjablonen.

## Zie ook

1. Onderzoek [ Dynamische Media en zijn mogelijkheden ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media)
1. Onderzoek [ Dynamische Media met mogelijkheden OpenAPI ](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview)
