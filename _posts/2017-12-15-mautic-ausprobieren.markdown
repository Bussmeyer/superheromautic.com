---
layout: post
title:  "Mautic ausprobieren - 3 Möglichkeiten"
date:   2017-12-14 12:50:19 +0100
categories: mautic
cover_url: /images/skyline-fog.jpg
---
Du willst Mautic ausprobieren? Es gibt drei Möglichkeiten:
* [Mautic.com](https://mautic.com)
* Lokale Installation, z.B. mit [MAMP](https://www.mamp.info/)
* Umfangreicheres Setup mit Docker

Was kommt für dich in Frage? Es kommt darauf an was du machen willst.

## Mautic.com
*Schnell reinschauen und Überblick verschaffen.*

Wenn du schnell und ohne technischen Aufwand einen Eindruck gewinnen willst,
dann melde dich auf [mautic.com](https://mautic.com) an. Mautic.com ist eine Software-as-a-Service-Lösung für Mautic.
Vergleichbar mit Wordpress.com.

### Was geht gut?
In der kleinsten Variante kostenfrei
Daten können exportiert werden
Kein technischer Aufwand, keine eigene Maintenance

### Was fehlt?
Volle technische Kontrolle
Keine Analysemöglichkeiten, da keinen Zugriff auf den Quellcode von Mautic

## Mautic auf MAMP
*Auf dem eigenen System ausprobieren. Selbst mit Mautic entwickeln. Das System erweitern.*

Wenn du nicht nur den Funktionsumfang checken sondern auch selbst Templates oder Plugins entwicklen willst, dann reicht die SAAS-Lösung nicht.

**Info:** *[Hier erkläre ich wie das Setup funktioniert.]

Wie bei allen Entwicklungsaufgaben ist es auch bei Mautic essentiell eine lokale Entwicklungsumgebung aufzubauen.
Eine gute Entwicklungsumgebung zeichnet sich dabei durch eine Anzahl an Dinge aus:

* Schnell aufzusetzen und zu starten
* Stabil
* Gekapselt und streng abgegrenzt zu anderen Projekten
* Leicht erweiter- und integrierbar.


Was geht nicht so einfach und so schnell?
Cronjobs für Segmente
Mailandling, Mails Abfangen
Kapselung zu deinen anderen Entwicklungsprojekten

### Was geht gut?
Installation mit MAMP ist nachvollziehbar und einfach
Man kann unter die Motorhaube gucken.
Cronjobs lassen sich je nach Hostsystem nicht einfach installieren und ausprobieren

### Was fehlt?
Schutz gegen unabsichtlichen Mailversand fehlt


## Mautic + Docker = <i class="icon-heart"></i>
tbd.
### Was geht gut?
Komplett gekapselt und unabhängig vom lokalen System
Interaktion und Zusammenspiel mit anderen Systemen wie einem CMS abbildetbar/nachstellbar


### Was fehlt?
Mir fehlt für die Analyse und Nachvollziehbarkeit und Entwicklung eigentlich nichts mehr.