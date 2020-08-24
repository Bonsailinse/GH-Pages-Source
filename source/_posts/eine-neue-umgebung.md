---
title: Eine neue Umgebung
description: Die Einrichtung einer Entwicklungsumgebung, die Grundlage einer guten Programmierung.
categories:
  - Development
tags:
  - CMDer
  - CSS
  - Environment
  - GitHub
  - IDE
  - JavaScript
  - NodeJs
  - PHP
  - SQL
sidebar: false
toc:
  enable: false
date: 2020-08-24 10:03:03
---


Seit einiger Zeit wünscht sich mein Informatikerherz einen sauberen und übersichtlichen Workflow, wenn es um Softwareentwicklung geht. Bisher habe ich auf Projektbasis die entsprechenden Voraussetzungen geschaffen um dann beim nächsten Projekt die gleichen Vorbereitungen wieder treffen zu müssen.
Ich möchte endlich eine vernünftig eingerichtete Entwicklungsumgebung schaffen, bei der ich nach Bedarf zusätzliche Module einfügen kann, aber grundsätzlich für jedes meiner zukünftigen Projekte vorbereitet bin.

Meine Anforderungen sind folgende:
- Minimaler Reproduktionsaufwand. Bei einem Umzug auf ein anderes System muss meine Umgebung ohne eine erneute, aufwendige Konfiguration einsatzbereit gemacht werden können.
- Zu 100 % nutzbar unter Windows 10, wobei ich, gerne mit Einschränkungen, hin und wieder am MacBook arbeiten möchte. Das Produktivsystem wird dann mit großer Wahrscheinlichkeit ein Unix-basiertes sein.
- Als IDE sollen hauptsächlich die Programme aus dem Hause JetBrains genutzt werden. PHPStorm, DataGrip, PyCharm und IntelliJ sind meine vertrauten Umgebungen und sollen nicht ersetzt werden.
- Momentan liegt der primäre Fokus meiner Projekte auf PHP und NodeJS, andere Systeme können gerne erst einmal ausgelassen werden.
- Die Dokumentation aller Projekte soll möglichst simpel und übersichtlich geschehen, die Versionskontrolle via GitHub zähle ich dazu. 

Nachdem ich zwischen verschiedenen Lösungen hin- und hergewechselt habe, habe ich nun ein für mich recht ordentliches Konzept niedergeschrieben.

<!-- more -->

{% asset_img mindmap.svg %}

Ich wollte hier ursprünglich meinen Workflow für neue Projekte visualisieren, am Ende ist es dann eher eine Übersicht über meine Tools geworden.
Ich denke, ich werde in einem der nächsten Beiträge mal auf ein paar Details eingehen, würde mich nicht wundern, wenn die Graphik nicht so eindeutig ist, wie sie mir vorkommt. Vermutlich habe ich auch einige Dinge durcheinandergewürfelt, seht es mir nach, es ist erstmal nur ein Konzept.