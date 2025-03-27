---
title: Bulkmetagegevens bewerken in Elementen
description: Leer hoe u een vooraf gedefinieerde set standaardmetagegevensvelden kunt bijwerken voor meerdere elementen die tegelijkertijd beschikbaar zijn in de Elementen Essentieel.
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
source-git-commit: 461773235cb2d27d334b5ceb23f959dc9a848716
workflow-type: tm+mt
source-wordcount: '508'
ht-degree: 0%

---


<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="new">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b> Dynamische Media Prime en Ultimate </b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="new">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b> AEM Assets Ultimate </b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="new">
            <a href="http://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b> de integratie van AEM Assets met Edge Delivery Services </b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="new">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b> Uitbreidbaarheid UI </b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="new">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/custom-search-filters"><b> Filters van het Onderzoek van de Douane </b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b> Beste praktijken van het Onderzoek </b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b> Beste praktijken van Meta-gegevens </b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b> Content Hub </b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b> Dynamische Media met mogelijkheden OpenAPI </b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b> de ontwikkelaarsdocumentatie van AEM Assets </b></a>
        </td>
    </tr>
</table>

# Bulkmetagegevens bewerken in Elementen{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

De **Bulk Meta-gegevens geeft** eigenschap binnen de Hoofdzaak van Activa uit staat gebruikers toe om een vooraf bepaalde reeks standaardmeta-gegevensgebieden voor veelvoudige activadossiers gelijktijdig uit te geven. Selecteer meerdere elementen en bulksgewijs werk de vooraf gedefinieerde set standaardmetagegevens tegelijk bij in plaats van deze standaardmetagegevens voor elk element afzonderlijk bij te werken. Deze functie verbetert de efficiëntie, consistentie en nauwkeurigheid van standaardeigenschappen voor metagegevens in een grote set elementen, waardoor de zoekbaarheid en organisatie van middelen wordt verbeterd.

## Metagegevens van elementen in blokvorm bewerken {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

Voer de volgende stappen uit om de metagegevens van meerdere elementen tegelijk in bulk te bewerken:

1. Voor de Hoofdzaak van Activa, klik **Assets**.
1. Blader naar specifieke elementen of doorzoek deze met behulp van trefwoorden op de zoekbalk.
1. Selecteer de activa en klik **Bulk Meta-gegevens uitgeven** van het hoogste menu.
   ![ bulk-meta-gegeven-geef uit ](/help/using/assets/bulk-metadata-edit1.png)
1. Op de Edit meta-gegevenspagina, geef de volgende gebieden in het **paneel van Eigenschappen** uit:
   * **Status:** selecteer een status voor de geselecteerde activa.
   * **Vervaldatum:** plaats een datum waarna de activa ongeldig of nodig zijn.
   * **Auteur:** specificeer de naam van de auteur.
   * **Sleutelwoorden:** voeg specifieke termijnen of tekstkoorden toe die een informatie op hoog niveau over de activa verstrekken om hun ontdekkingsbaarheid te verbeteren. Voeg een trefwoord toe en druk op Enter of Return om nog een trefwoord aan de lijst toe te voegen.
   * **Markeringen:** klik ![ etikettenpictogram ](/help/using/assets/tags-icon.svg) om markeringen van de beschikbare opties te selecteren. Tags bieden specifiekere informatie over de elementen en verbeteren de ontdekkingsmogelijkheden ervan. De markeringen die reeds op de geselecteerde activa worden toegepast tonen in het **paneel van Eigenschappen**. Als u de relevante tags niet kunt vinden, maakt u deze en wijst u ze toe aan de geselecteerde elementen. Zie [ markeringen in de Hoofdzaak van Activa beheren ](/help/using/tagging-management.md) voor details bij het creëren van en het toewijzen van markeringen aan activa.
   * Klik **sparen** om de bovengenoemde meta-gegevensupdates op de geselecteerde activa toe te passen. Nadat trefwoorden en tags zijn opgeslagen, worden deze toegevoegd terwijl de bijgewerkte gegevens voor Status, Vervaldatum en Auteur de bestaande gegevens overschrijven.
     ![ sparen-bulk-meta-gegeven-geef-eigenschappen uit ](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >U kunt de metagegevens van 100 elementen tegelijk bewerken.

Om de toegepaste meta-gegevensupdates aan een activa te zien, navigeer aan de pagina van activadetails (uitgezochte activa, en klik **Details**) en klik ![](/help/using/assets/info-icon-solid-black.svg) om de meta-gegevens van de activa in het **paneel van de Informatie** te zien.

>[!NOTE]
>
>**Status**, **Vervaldatum**, **Auteur**, **Trefwoorden** en **Markeringen** zijn standaardmeta-gegevenseigenschappen beschikbaar voor bulkmeta-gegevens het uitgeven, ongeacht omslag-specifieke meta-gegevens. Deze eigenschappen van metagegevens worden alleen weergegeven op de pagina met elementdetails als ze zijn opgenomen in het metagegevensformulier dat is toegepast op de map van het element. Als u deze standaardeigenschappen voor metagegevens niet kunt vinden op de pagina met elementdetails, bewerkt u het metagegevensformulier van de map met middelen om deze op te nemen. Zie [ Meta-gegevens in de Hoofdzaak van Activa ](/help/using/metadata.md) leren om een meta-gegevensvorm tot stand te brengen of uit te geven en het op een omslag toe te passen.
