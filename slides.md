---
title: Referat Privacy
theme: dracula
description: Social Media Referat Jakob Hofer
class: invert
footer: 5.10.2023 | Jakob Hofer | MEDTSM Referat
"_footer": ""
paginate: true
"_paginate": false
style: |
    section:is(.lead) h1 {
        text-align: center;
    }

    section:is(.smol-list) h3 {
        margin-top: 10%;
        margin-bottom: 0;
    }

    section:is(.smol-list) {
        padding-top: 20%;
        padding-right: 0;
    }

    section:is(.smol-list) blockquote {
        width: fit-content;
    }

    section:is(.smol-list) blockquote::before {
        margin-left: 1%;
    }

    section:is(.smol-list) li {
        font-size: 40%;
    }

    section:is(.smol-list) > *:last-child {
        font-size: 60%;
    }
marp: true
---

# Referat Privacy
Jakob Hofer

---

### Einführung
- Internet ist überall
- vieles gratis
- => Datensammlung
- User werden zum Produkt

---

<!-- _class: lead -->

# Daten sind wertvoll!

---

### Datenspionage - Firmen
- Trend: steigend
- 5-10% aller requests sind Tracker
- Nutzer monetarisieren
- 80% der Internetseiten haben Google-Tracker

---

### Datensammlung
![bg right](https://images.prismic.io/coresignal-website/a86edea5-e24e-40a4-83c7-b6cc1d16ce11_Data+Broker.png?auto=compress%2Cformat&fit=max&q=75)
- von Data Brokern zusammengefasst
- Beispiel: Werbungen auf Facebook aufgrund einer Aktion in einer anderen App

---

<!-- _class: table -->
<!-- _footer: "" -->

![](data-collection1.png)
![](data-collection2.png)

![](data-collection4.png)
![](data-collection3.png)

---

# Datenspionage - Staat
![bg right](https://pbs.twimg.com/tweet_video_thumb/Er7iTVCVoAENykr.jpg)

---

### China
![bg right](https://media.npr.org/assets/img/2013/01/28/china3_custom-ef0a511cd17bdc22f2869b582014f9702bcfd7d3.jpg)
- autokratischer Staat => Überwachung interessant
- eigene Systeme
- WeChat als Alleskönner

---

### China - WeChat
![bg right 90%](https://i0.wp.com/blog.viral-launch.com/wp-content/uploads/2020/09/WeChat.png)
- Chat, Spiele, Bezahlungen, ...
- speichert Daten in China
- Nutzung wird analysiert und weitergegeben
- detailierte Bevölkerungsprofile

---

##### Identitätsdiebstahl
![bg right:58%](https://i.kym-cdn.com/entries/icons/original/000/021/807/ig9OoyenpxqdCQyABmOQBZDI0duHk2QZZmWg2Hxd4ro.jpg)
- Identität wird übernommen
- Motive:
    - Bestellen von Waren
    - Namensmiss-brauch
    - Rufschädigung

---

<!-- _class: lead -->
# Zensur & Meinungsfreiheit

---
## Zensur - Allgemein
![bg right](https://www.hanisauland.de/sites/default/files/styles/article_1180/public/786522-161311-134285.jpg.jpeg)
- Informationen unterdrücken
- China und Nordkorea auf letzten Plätzen
- Thema Zensur wird zensiert

---

## Zensur - Nordkorea
![bg right](https://pbs.twimg.com/media/CWWHjXKWsAAnL97.jpg:large)
- komplett abgeschottet
  - keine ausländischen Medien
- Intranet mit 28 Domains

---
## Zensur - China
![bg right](https://media.tenor.com/Anhf93tvmL0AAAAd/john-xina-xina.gif)
- Regime blockiert alles Ungewollte
- kontrolliert gesammten Nachrichtenaustausch
- siehe WeChat

---
<!-- _class: lead -->
# Lösungen

---
### Lösungen - Internet
- AdBlocker verwenden
    - 👎 ACHTUNG: kein "Adblock Plus" usw.
    - 👍 uBlock Origin
- eigener DNS Server
    - Pi-Hole oder AdGuard Home
    - technisch limitiert
    - alternative: modden
---

### Lösungen - Browser
🤮 kein Google Chrome!
<br>
1. ❤ Firefox on top
    - eigene Engine
        - verhindert Monopolstellung von Google
    - am Handy: Extensions

---

### Lösungen - Browser
1. ❤ Firefox
2. 🛡 Hardened Firefox
    - eigene Engine
        - verhindert Monopolstellung von Google
    - am Handy: Extensions
---

<!-- _footer: "100% not biased trust me" -->
### Lösungen - Browser
1. ❤ Firefox
2. 🛡 Hardened Firefox
3. 😐 Brave
    - integrierter Ad- und Tracking-Blocker
        - vergleichsweise schwach
        - wird leicht erkannt
    - basiert auf Chromium
        - siehe https://tiny.cc/CommonGoogleL
        - gibt Google ungesunde Macht

---
### Lösungen - OS
- kein Windows
- kein macOS
- Linux = ❤️‍🔥
    - für paranoide: Tails, Qubes, ...
    - i use arch btw
- nein, auch kein Deepin oder RedstarOS
- am besten: TempleOS 🛕

---
# Apple....
- apple nix gut
- kein unbeschriebenes Blatt
- unerlaubtes Scannen von lokalen Dateien
- Closed Source & nonfree & unethisch
- wesentlich eingeschränkte Freiheit
- siehe https://stallman.org/apple.html

![bg right:34% 95%](https://preview.redd.it/ignfnvvnlqn91.jpg?auto=webp&s=bf4e42bf1e10e4c38aaf459eac0764c9bb56042c)

---
# Schlusswort
- Privatsphäre ist ein Grundrecht
- der Eisberg an unethischen Machenschaften ist tief
- selbst "kleine" Aktionen helfen
- selbst Balance finden zwischen Bequemlichkeit und Freiheit
- Macht und Abhängigkeit ist schädlich!!!
    - siehe Microsoft, Google, etc.

---
<!-- _footer: "" -->
<!-- _paginate: false -->
<!-- _class: smol-list -->
![bg right:35% 45%](https://blog.internxt.com/content/images/2022/02/Security-meme-6.png)
![bg vertical 70%](https://i.redd.it/f1trcr2utf051.jpg)
> Der Feind hört immer mit.

~ ich

### Quellen
- https://www.ghostery.com/blog/tracking-the-trackers-2020
- https://www.verivox.de/rechtsschutzversicherung/themen/identitaetsdiebstahl/
- https://www.reporter-ohne-grenzen.de/china
- https://www.reporter-ohne-grenzen.de/nordkorea
- https://www.ionos.de/digitalguide/domains/domainverwaltung/internet-im-kleinformat-nordkoreas-28-domains/
- https://github.com/mandatoryprogrammer/NorthKoreaDNSLeak
- https://weixin.qq.com/cgi-bin/readtemplate?lang=en_US&t=weixin_agreement&s=default&cc=CN
- https://en.wikipedia.org/wiki/WeChat#cite_note-17
- https://qz.com/960948/what-happens-when-you-try-to-send-politically-sensitive-messages-on-wechat
- https://youtu.be/_YQEE9Jl7fs?feature=shared&t=351

https://github.com/SIMULATAN/2324_MEDTSM_ReferatPrivacy
