---
title: Zelfstudie Aan de slag met pushmeldingen voor Android - Inleiding
description: Deze zelfstudie begeleidt u door de stappen die nodig zijn voor het verzenden van pushberichten van Adobe Campaign en het ontvangen van deze meldingen in uw Android-app.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 217b0ec1b6f5c5e17009f1103d69726aa57dcaa4
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 0%

---


# Zelfstudie Aan de slag met pushmeldingen voor Android - Inleiding

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

Deze zelfstudie begeleidt u door de stappen die nodig zijn voor het verzenden van [!DNL push] berichten van Adobe Campaign naar een [!DNL Android] app.

## Vereisten

Voordat u kunt beginnen, moet u aan de volgende voorwaarden voldoen

1) Mobiele toepassingDeze zelfstudie behandelt niet de gedetailleerde stappen die nodig zijn om de mobiele toepassing in te stellen. U moet beschikken over een **[!DNL Android]mobiele toepassing met de[!DNL Campaign SDK]** geïntegreerde.

   * U vindt een gedetailleerde beschrijving van de vereiste stappen in de [integrating Campagne SDK in de mobiele toepassing](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html).

   * U kunt ook de Experience Platform Mobile SDK gebruiken. Voor meer informatie bekijk de [Configure het Kanaal van de Duw gebruikend de Experience Platform Mobiele SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) zelfstudie video.

2) Mobiel App Channel-pakket geïnstalleerd

   U moet het pakket met het kanaal van de mobiele app op uw exemplaar installeren. In de volgende video wordt uitgelegd hoe u kunt controleren of het mobiele App-kanaal op uw instantie is geïnstalleerd en, als dat niet het geval is, hoe u het kanaal kunt installeren.

   [!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Zelfstudie

We willen een persoonlijke pushmelding sturen naar de abonnees van de [!DNL Android] mobiele app Neotrip. De Neotrip-app is geconfigureerd met de Campagne SDK en we hebben ervoor gezorgd dat het Mobile App-kanaal is geactiveerd op onze Campagne-instantie.

De volgende configuratiestappen worden vereist:

### Stap 1: Het schema voor app-abonnementen uitbreiden om pushmeldingen aan te passen

Aangezien wij de pushmelding willen personaliseren, zullen wij eerst het schema [van het toepassingsabonnement](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) uitbreiden om de verpersoonlijkingswaarden op te slaan die wij van app ontvangen wanneer de gebruiker zich op de dienst abonneert.

### Stap 2: De Android-service configureren en de mobiele app-toepassing maken in Campagne

Vervolgens moeten we de Android-service [configureren en de mobiele app-toepassing maken in Campagne](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). In deze stap definiëren we de Neotrip-app als het doel voor de pushmelding.

### Stap 3: De pushmelding configureren en verzenden

Dan zijn wij bereid om het dupbericht [te](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)vormen en te verzenden.

## Zelfstudie starten

**[Stap 1: Het schema voor app-abonnementen uitbreiden](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
