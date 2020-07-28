---
title: Problemen met het configuratiescherm oplossen
description: Met het Configuratiescherm kunt u uw SFTP-opslag op instantie en IP-adressen van lijsten van gewenste personen controleren en beheren.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 1%

---


# Problemen oplossen [!UICONTROL Control Panel]

## Aanmelding en startpagina

### Symptoom: Kan niet aanmelden bij Experience Cloud

**Wat moet u doen:**
De gebruiker moet de IMS Org-id (xxx) zoeken. De beheerder moet de gebruiker aan het Profiel van het Product &quot;Campagne-xxx-Admins&quot;voor elke instantie toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is zouden zij nog kunnen moeten toevoegen als gebruikers.

### Symptoom: Koppelingen in de Experience Cloud Home voor toegang worden [!UICONTROL Control Panel] niet weergegeven voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas als ze als gebruikers zijn toegevoegd aan het productprofiel &quot;Campagne-xxx-beheerders/Admin&quot;

**Wat moet u doen:**
De beheerder moet de gebruiker aan het Profiel van het Product &quot;Campagne-xxx-Admins&quot;voor elke instantie toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is zouden zij nog kunnen moeten toevoegen als &quot;gebruikers.

### Symptoom: Een instantie wordt niet vermeld in het dialoogvenster [!UICONTROL Control Panel]

**Oorzaak:**
De meest waarschijnlijke gebruiker moet als &quot;gebruiker&quot;Profiel van het Product &quot;Campaign-xxx-Beheerders/Admin&quot;voor de instantie worden toegevoegd die mist

**Wat moet u doen:**
De beheerder moet de gebruiker aan het Profiel van het Product &quot;Campagne-xxx-Admins&quot;voor elke instantie toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is zouden zij nog kunnen moeten toevoegen als &quot;gebruikers&quot;.

### Nuttige video&#39;s

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*IMS-organisatie-id controleren (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Hoe te om een beheerder aan de beheerders van het productprofiel toe te voegen om te kunnen gebruiken[!UICONTROL Control panel](01:03 min)*

### Nuttige documentatie

* [Het Configuratiescherm detecteren](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [Machtigingen beheren voor de [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Verbinding met SFTP-server tot stand brengen (client of API)

Voor verbinding met SFTP-servers is het volgende vereist:

* [!UICONTROL Allow listing] het IP-adres waarvan u verbinding maakt met de SFTP-server
* Persoonlijk/openbaar sleutelpaar dat bij Adobe Campaign moet worden geregistreerd
* Als u rechtstreeks verbinding maakt met de SFTP-server, hebt u ook SFTP-clientsoftware nodig

### Nuttige documentatie

* [Aanmelden bij uw SFTP-server](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

