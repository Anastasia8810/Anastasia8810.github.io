---
layout: doc
lang: sv
title: Integritetspolicy
permalink: /sv/privacy/
slug: "privacy/"
show_updated: true
description: Hur appen Baller hanterar dina uppgifter.
---

Den här policyn förklarar vilka uppgifter iOS-appen **Baller** (”appen”) använder, varför och var de lagras. Appen utvecklas av {{ site.author }} (”vi”). Frågor: [{{ site.email }}](mailto:{{ site.email }}).

<div class="note"><p>Kortfattat: träningspass, inspelningar och din profil stannar på din iPhone. Lagfunktionerna (chatt, laguppställning, profilbilder, samtal) går via vår server enbart för att nå dina lagkamrater. Vi använder AppsFlyer för användningsanalys. Vi säljer inte dina uppgifter.</p></div>

## Uppgifter som lagras på din enhet

- **Träningshistorik** – program du har startat och avslutat, antal genomförda övningar, längd.
- **Inspelningar** – videor du spelar in i appen. De sparas i appens mapp Dokument och, om du vill, i Bilder. Vi laddar aldrig upp dem.
- **Profil** – ditt namn, din roll (spelare eller tränare), tröjnummer, position och profilbild.
- **Lag och chatt** – laguppställningen och chatthistoriken.

Uppgifterna raderas när du tar bort appen.

## Uppgifter som skickas till vår server

Lagfunktionerna behöver en server för att leverera meddelanden mellan telefoner. Vår server (hos Render) tar emot:

| Uppgift | Varför | Hur länge |
|---|---|---|
| Slumpmässigt användar-ID och ditt namn | För att skicka meddelanden och samtal till dig | Så länge du använder lagfunktionerna |
| Laguppställning (namn, roller, nummer, positioner) | För att dela den med laget | Senaste versionen sparas |
| Profilbild (liten JPEG) | För att visa den för laget | Senaste versionen sparas; tar du bort den i appen tas den bort från servern |
| Chattmeddelanden | För att leverera dem till lagkamrater som inte är uppkopplade | Upp till 7 dagar, sedan raderas de |
| VoIP-pushtoken | För att ringa på din telefon vid inkommande lagsamtal | Så länge du använder lagfunktionerna |

Röst och video i samtal går direkt mellan telefonerna (WebRTC, krypterat). När en direkt anslutning inte är möjlig vidarebefordras de via en TURN-server utan att spelas in. En offentlig STUN-server från Google används för att upprätta anslutningen och ser bara din nätverksadress.

## Behörigheter

Appen ber bara om behörigheter när du använder respektive funktion. Du kan stänga av dem när som helst under **Inställningar → Baller**.

- **Mikrofon** – så att spottern hör röstkommandon under träningen, och för lagsamtal.
- **Taligenkänning** – gör fraser som ”start workout” eller ”next exercise” till handlingar. Talet behandlas av Apples taligenkänningstjänst enligt [Apples integritetspolicy](https://www.apple.com/se/legal/privacy/). Vi lagrar eller tar inte emot ditt ljud.
- **Kamera** – för att spela in träningen och skanna lagkamraters QR-koder.
- **Bilder** – för att välja en skottvideo att granska och spara inspelningar i biblioteket.

## Analys

Vi använder [AppsFlyer](https://www.appsflyer.com/legal/privacy-policy/) för att förstå om appen är användbar: till exempel att ett pass startades eller avslutades, att ett röstkommando användes, att en video spelades in, att en lagkamrat lades till, att ett meddelande skickades eller att ett samtal startades. Händelserna innehåller inte innehållet i dina meddelanden, dina inspelningar eller ditt namn.

AppsFlyer kan använda en enhetsidentifierare för attribuering av installationer. Om du inte har tillåtit spårning delas inte annonsidentifieraren (IDFA). Du styr detta under **Inställningar → Integritet och säkerhet → Spårning**.

## Det här gör vi inte

- Vi säljer inte dina personuppgifter.
- Vi visar inga annonser i appen.
- Vi laddar inte upp dina inspelningar.

## Barn

Appen riktar sig inte till barn under 13 år, och vi samlar inte medvetet in uppgifter från dem. Om du tror att ett barn har skickat oss uppgifter, kontakta oss så raderar vi dem.

## Dina rättigheter

Enligt GDPR kan du begära tillgång till eller radering av uppgifter på vår server, som ditt namn, laguppställning, profilbild och olevererade meddelanden. Skriv till [{{ site.email }}](mailto:{{ site.email }}). Du har också rätt att lämna klagomål till Integritetsskyddsmyndigheten (IMY). Uppgifter på enheten raderas när du tar bort appen.

## Ändringar

Vi kan uppdatera den här policyn. Datumet högst upp visar den senaste versionen. Väsentliga ändringar meddelas i appen eller på den här sidan.

## Kontakt

{{ site.author }} – [{{ site.email }}](mailto:{{ site.email }})
