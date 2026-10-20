---
layout: doc
lang: en
title: Privacy Policy
permalink: /privacy/
slug: "privacy/"
show_updated: true
description: How the Baller app handles your data.
---

This policy explains what data the **Baller** iOS app (“the app”) uses, why, and where it is kept. The app is developed by {{ site.author }} (“we”). Questions: [{{ site.email }}](mailto:{{ site.email }}).

<div class="note"><p>In short: workouts, recordings and your profile stay on your iPhone. Team features (chat, team roster, avatars, calls) go through our server only to reach your teammates. We use AppsFlyer for usage analytics. We do not sell your data.</p></div>

## Data stored on your device

- **Workout history** — programs you started and finished, number of completed exercises, duration.
- **Workout recordings** — videos you record in the app. They are saved in the app’s Documents folder and, if you choose, in Photos. They are never uploaded by us.
- **Profile** — your name, role (player or coach), jersey number, position and avatar.
- **Team and chat** — your team roster and chat history.

This data is deleted when you delete the app.

## Data sent to our server

Team features need a server to deliver messages between phones. Our server (hosted on Render) receives:

| Data | Why | How long |
|---|---|---|
| Random user ID and your name | To route messages and calls to you | While you use team features |
| Team roster (names, roles, numbers, positions) | To share the roster with teammates | Latest version is kept |
| Avatar (small JPEG) | To show it to teammates | Latest version is kept; removing it in the app removes it on the server |
| Chat messages | To deliver them to teammates who are offline | Up to 7 days, then deleted |
| VoIP push token | To ring your phone for an incoming team call | While you use team features |

Voice and video in calls go directly between phones (WebRTC, encrypted). When a direct connection is not possible, they are relayed through a TURN server without being recorded. A public Google STUN server is used to set up the connection and only sees your network address.

## Device permissions

The app asks for these permissions only when you use the related feature. You can turn them off at any time in **Settings → Baller**.

- **Microphone** — so the spotter can hear voice commands during a workout, and for team calls.
- **Speech Recognition** — turns phrases like “start workout” or “next exercise” into actions. Speech is processed by Apple’s speech recognition service under [Apple’s privacy policy](https://www.apple.com/legal/privacy/). We do not store or receive your audio.
- **Camera** — to record workouts and scan teammates’ QR codes.
- **Photos** — to pick a shooting video for review and to save recordings to your library.

## Analytics

We use [AppsFlyer](https://www.appsflyer.com/legal/privacy-policy/) to understand whether the app is useful: for example, that a workout was started or finished, a voice command was used, a video was recorded, a teammate was added, a message was sent or a call was started. Event data does not include the content of your messages, your recordings or your name.

AppsFlyer may use a device identifier for app install attribution. If you have not allowed tracking, the advertising identifier (IDFA) is not shared. You can control this in **Settings → Privacy & Security → Tracking**.

## What we don’t do

- We don’t sell your personal data.
- We don’t show ads in the app.
- We don’t upload your workout recordings.

## Children

The app is not directed at children under 13, and we do not knowingly collect personal data from them. If you believe a child has sent us data, contact us and we will delete it.

## Your rights

You can ask us to access or delete data kept on our server, such as your name, roster, avatar and undelivered messages. Write to [{{ site.email }}](mailto:{{ site.email }}). Data on your device is removed when you delete the app.

## Changes

We may update this policy. The date at the top shows the latest version. Significant changes will be announced in the app or on this page.

## Contact

{{ site.author }} — [{{ site.email }}](mailto:{{ site.email }})
