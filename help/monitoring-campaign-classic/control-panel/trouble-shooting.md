---
title: Problemen met het Configuratiescherm oplossen
description: Met het Configuratiescherm kunt u uw SFTP-opslag per instantie controleren en beheren en IP-adressen aan de acceptatielijst toevoegen.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: fe3d8945922aa1a2b78772cf0a033976b67b85a5
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 100%

---


# Problemen oplossen [!UICONTROL Control Panel]

## Aanmelding en startpagina

### Symptoom: Aanmelden bij Experience Cloud is niet mogelijk

**Wat moet u doen:**
De gebruiker moet de IMS-organisatie-id (xxx) zoeken. De beheerder moet de gebruiker toevoegen aan het productprofiel ‘Campaign-xxx-Admins’ voor elke instantie die ze willen beheren. Als de gebruiker een beheerder van alle instanties is, dienen ze mogelijk ook zichzelf toe te voegen als gebruikers.

### Symptoom: Koppelingen in de Experience Cloud Home voor toegang tot [!UICONTROL Control Panel] worden niet weergegeven voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas wanneer ze als gebruikers zijn toegevoegd aan het productprofiel _Campaign-xxx-Administrators/Admin_.

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke instantie die ze willen beheren. Als de gebruiker een beheerder van alle instanties is, dienen ze mogelijk ook zichzelf toe te voegen als gebruikers.

### Symptoom: Een instantie wordt niet vermeld in het [!UICONTROL Control Panel]

**Oorzaak:**
Waarschijnlijk moet de gebruiker worden toegevoegd als ‘gebruiker’ voor het productprofiel _Campaign-xxx-Administrators/Admin_ voor de instantie die ontbreekt

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke instantie die ze willen beheren. Als de gebruiker een beheerder van alle instanties is, dienen ze mogelijk ook zichzelf toe te voegen als gebruikers.

### Nuttige video’s

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS-organisatie-id controleren (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Een beheerder toevoegen aan het productprofiel voor beheerders om [!UICONTROL Control panel] te kunnen gebruiken (01:03 min)*

### Nuttige documentatie

* [Het Configuratiescherm verkennen](https://helpx.adobe.com/nl/campaign/kb/control-panel-overview.html)
* [Machtigingen beheren voor het [!UICONTROL Control Panel]](https://helpx.adobe.com/nl/campaign/kb/control-panel-access.html)

## Verbinding met SFTP-server tot stand brengen (client of API)

Voor verbinding met SFTP-servers is het volgende vereist:

* [!UICONTROL Allow listing] het IP-adres waarvan u verbinding maakt met de SFTP-server
* Privé/openbaar sleutelpaar dat bij Adobe Campaign moet worden geregistreerd
* Als u rechtstreeks verbinding maakt met de SFTP-server, hebt u ook SFTP-clientsoftware nodig

### Nuttige documentatie  {#helpful-docs}

* [Aanmelden bij uw SFTP-server](https://helpx.adobe.com/nl/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

