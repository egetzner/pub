---
title: Wissensaustausch im Wandel
subtitle: Wiki für die Bücherei Nofels
author: Elisabeth Getzner
institute: <img src="figures/bvoe_logo.svg"/>
date: September 2024
keywords:
- Wissensmanagement
- Wiki
- Dokumentation
subject: Wiki
description: Projektbericht im Rahmen der Ausbildung für ehrenamtliche und nebenberufliche Bibliothekarinnen und Bibliothekare
category: Projektbericht
abstract: Planung und Einführung einer Wissens- und Informationsdatenbank (Wiki) für Mitarbeiter:innen der Bücherei Nofels. Es werden die Anforderungen an diese Software geklärt und die technische Umsetzung beschrieben.
progress: true
theme: moon
margin: 0.2
slideNumber: \'c/t\'
slideNumber: true
photoCredit: © 2024 | Verena Knöpfle
title-slide-attributes:
    data-background-image: figures/fotos/bib_magazines.png
    data-background-size: stretch
    data-background-opacity: 0.1
---

# Ausgangslage {background-image="figures/fotos/bib_outside.png" background-opacity=0.1 background-credit="© 2024 | Verena Knöpfle"}

## Unser Team 
- Kleine Stadtteilbücherei
- 15 ehrenamtliche Mitarbeiter:innen
- Austausch oft in kleineren Gruppen
- Zuständigkeiten stark verteilt

<!--![Altersverteilung](figures/age_distribution.png)-->

## Kommunikation & Austausch
- 🗒️ Notizen (handschriftlich)
- 💬 WhatsApp-Gruppen
- ✉️ E-Mails (Protokolle, Veranstaltungen)
- 👥 Teamsitzungen (alle 3-4 Monate)
- 🗃️ Anleitungen (gedruckt + digital)

::: notes
- Relativ großes Team (15 Personen)
- Arbeit meist getrennt in kleinen Gruppen (2-3 Personen)
- Kommunikation & Austausch in Teamsitzungen, E-Mail oder Whatsapp
- Diverse Anleitungen, von denen nicht alle wissen
:::

## Probleme {auto-animate=true}

<ol>
<li>Nicht jede:r hat den selben Wissensstand</li>
<ul>
<li>Erreichbarkeit im Team sehr unterschiedlich</li>
</ul>
<li>Informationen sind schwer zugänglich</li>
<ul>
<li>Zugang nur vor Ort</li>
<li>Suche erschwert</li>
</ul>
<li>Informationen sind nicht nachvollziehbar</li>
<ul>
<li>Datum, Autor:in oft unbekannt</li>
</ul>
</ol>

::: notes
- wenig Zeit
- kaum geschultes Personal
- keine Person die für etwas fix zuständig ist
- unklare Aufgabenverteilung
  - unklar: wer hat was schon gemacht, was muss gemacht werden
- ungleicher Wissensstand
:::


## Ziel des Projekts {auto-animate=true}

<ol>
<li><span class="fragment semi-fade-out strike" data-fragment-index="1">Nicht jede:r hat den selben Wissensstand</span></li>
<ul class="result">
<li class="fragment fade-left" data-fragment-index="1">Zentrale Anlaufstelle für Fragen & Anleitungen</li>
</ul>
<li><span class="fragment semi-fade-out strike" data-fragment-index="2">Informationen sind schwer zugänglich</span></li>
<ul class="result">
<li class="fragment fade-left" data-fragment-index="2">Ortsunabhängig & leicht zu durchsuchen</li>
</ul>
<li><span class="fragment semi-fade-out strike" data-fragment-index="3">Informationen sind nicht nachvollziehbar</span></li>
<ul class="result">
<li class="fragment fade-left" data-fragment-index="3">Änderungen stets nachvollziehbar</li>
</ul>
</ol>



::: notes
#### Zentrale Anlaufstelle für Fragen & Anleitungen
- gesammelter Ort für Dokumentation 📜 
    - Handbuch (besonders für neue Mitarbeiter:innen)
    - Anleitungen für sporadische Handlungen (z.B. 1x im Jahr Klassenlisten)
    - Projektorganisation (z.B. Sommerlesen) - wiederverwenden
    - Linksammlungen (Website, E-Mails, Kontakte, etc)
- gut durchsuchbar 🔍

#### 🤝 Kooperativ
- Sammelbecken für Ideen, offene Arbeiten
- zum Austausch zwischen den Mitarbeitern anregen
- Möglichkeit, Kommentare zu hinterlassen

#### 🏠 Ortsunabhängig
- Wiki kann von zu Hause aus bearbeitet werden

#### 🕰️ Nachvollziehbarkeit
- Wann wurden zuletzt Änderungen gemacht und von wem?
- Wie aktuell ist die Dokumentation?
- Können Inhalte "verloren" gehen?
:::

# Ich hab's! {background-image="figures/wickie-stars.gif" background-credit="© 1974 | Wickie und die starken Männer"}

<span class="highlight">
Ein Wi(c)ki(e) für die Bücherei Nofels
</span>

## Was ist ein Wiki?  {background-image="figures/Wikipedia-logo-v2.svg" background-opacity=0.1 background-credit="🅭 BY-SA 3.0 2022 | Wikimedia Commons"}

> Website, deren Inhalt von Besucher:innen nicht nur _gelesen_ sondern auch _verändert_ werden kann

Beispiele
: 
- Enzyklopädie: [Wikipedia](https://wikipedia.org "Wikipedia")
- Sachbücher: [WikiBooks](https://de.wikibooks.org/wiki/Hauptseite)
- Anleitungen: [WikiHow](https://www.wikihow.com/Main-Page)
- Pop Kultur: [Fandom](https://www.fandom.com/), [TV Tropes](https://tvtropes.org/)

## Wiki in Organisationen

- Erfahrung & Wissen dokumentieren
  - Zugriff auf bereits existierenden Lösungen
- Kollaboratives Arbeiten
  - _Autor:in_ 👤 und _Zeitpunkt_ ⏲ ersichtlich

![Unternehmenswiki [Confluence](https://www.atlassian.com/de/software/confluence)](figures/confluence-review.png){width=50%}

# Projektplanung {background-image="figures/fotos/bib_wall_of_books.png" background-opacity=0.1 background-credit="© 2024 | Verena Knöpfle"}

## Leitfragen

::: incremental
1. 👓 __Lesen__: 
   Wie können wir Wissen zugänglich machen?
2. ✍️ __Bearbeiten__: 
   Wie können Inhalte vom Team selbst geschrieben werden?
3. 🫰 __Nutzen__: 
   Stehen die Kosten und der Wartungsaufwand in Relation zum Nutzen?
:::

::: notes

1. 👓 Lesen: 
  - Wie können wir unser gesammeltes Wissen möglichst zugänglich machen? 
  - Welche Anforderungen stellen wir an diese Software?

2. Bearbeiten ✍️
  - Welche Voraussetzungen müssen gegeben sein, damit Inhalte auch abgeändert und beschrieben werden können?

3. Nutzen 🫰 💰 💶 💵
  - Ist diese Form der Organisation hilfreich für unsere Bücherei?
  - Stehen der Wartungsaufwand und die Kosten in Relation zum Nutzen?

:::

## Anforderungen und Erwartungen
- Einfache Bedienung
  - Übersichtliche Darstellung
  - Benutzerfreundliche Eingabe
- Arbeit von zu Hause aus
- Benutzerrollen (Schreib- & Leserechte)
- Kosten & Wartungsaufwand möglichst gering


## Ideen für Inhalte {visibility=visible}

![Ideen für Wiki-Inhalte](figures/mindmap_content_white_background.png){width=80%}

# Technische Umsetzung {background-image=figures/fotos/bib_computer.png background-opacity=0.2 background-credit="© 2024 | Verena Knöpfle"}

## Technische Landschaft

- Existierende Lösungen erwägen (z.B. Träger)
- Einschränkungen beachten:
  - Hosting (Bereitstellung der Software)
  - Wartung (Updates, Sicherheitskopien, etc.)
  - Budget

## Entscheidung für ein Wiki {auto-animate=true}
- Wiki-Systeme mit Anforderungen vergleichen
- [WikiMatrix](https://www.wikimatrix.org/) vergleicht __82__ Wiki-Lösungen
  - 2 einfache, freie Wikis:

:::::::::::::: {.columns}
::: {.column width="50%"}
![[BookStack](https://www.bookstackapp.com/)](figures/bookstack.png)
:::
::: {.column width="50%"}
![[DokuWiki](https://www.dokuwiki.org/dokuwiki)](figures/dokuwiki_detail.png)
:::
::::::::::::::

## Unsere Entscheidung {auto-animate=true}
![Moderne Oberfläche, einfache Handhabe, Organisation in Bücher und Regale](figures/bookstack.png){width=85%}

## Installation

1. Hosting beantragen bzw. installieren
    - Kosten: €5/Monat
3. Inhalte importieren, sortieren und strukturieren
2. Benutzer anlegen
    - Individuelle Schreib- & Leserechte

# Ergebnisse {background-image="figures/wiki_screenshots/bookstack_willkommen.png" background-opacity=0.1 background-size=auto }

## {background-image="figures/wiki_screenshots/bookstack_willkommen.png" background-size=auto}

::: {.box .right}
__Startseite__:
die wichtigsten Inhalte und Links
:::

## {background-image="figures/wiki_screenshots/books_important.png" background-size=auto data-transition=fade}
<img class="border bottom right" src="figures/mindmap_compact.png" width=40% />

## {background-image="figures/wiki_screenshots/handbuch_1.png" background-size=auto}

::: {.box .left}
Inhaltsangabe und Navigation
:::

## {background-image="figures/wiki_screenshots/bookstack_2024.png" background-size=auto  visibility=hidden}

::: {.box .right}
Jahresübersicht 2024: Seiten zur Organisation der Bücherei,
Sammelbecken für Arbeiten und Ideen, Sitzungsprotokolle dieses Jahres.
:::

## {background-image="figures/wiki_screenshots/suche.png" background-size=auto}

::: {.box .right}
Volltextsuche über alle Inhalte
:::

## {background-image="figures/wiki_screenshots/edit_protokoll.png" background-size=auto}

::: {.box .right}
Bearbeiten mit Vorlagen
:::

## Nachbereitung

- Mitarbeiter:innen __schulen__! 
   - Einstiegshürde reduzieren
   - Sichtbarkeit erhöhen
- Rechte und Benutzer pflegen
- Fortlaufende Nutzung

::: notes

1. Schulungen
   - wichtig um die Mitarbeiter:innen vertraut mit dem Tool zu machen

2. bei Änderungen im Team oder der Verantwortlichkeiten muss der Administrator 
   - die Schreib- und Leserechte anpassen, 
   - ggf. Benutzer hinzufügen / löschen

3. Wiki muss beworben und benutzt werden
  - veraltete Informationen nützen niemandem etwas

:::

# Reflexion {background-image="figures/fotos/bib_doors.jpg" background-opacity=0.1 background-credit="© 2024 | Verena Knöpfle"}

## Beantwortung der Leitfragen

## 1. 👓 __Lesen__
- Inhalte von überall zugänglich und durchsuchbar
- Wertschätzung der Dokumentation gesteigert
- Offene Arbeiten identifiziert

## 2. ✍️ __Bearbeiten__
- Schulungen als erster Einstiegspunkt
- Einfaches, Word-ähnliches Bearbeiten
- "Spielwiese" zum Testen der Eingabe
- Versionierung: Inhalte wiederherstellbar

## 3. 🫰 __Nutzen__
 - Nutzung derzeit als Nachschlagewerk
 - Evaluierung nach 1 Jahr
 - Alternativen: 
   - Bibliothekssoftware
   - Office Suite
   
::: notes
### 👓 Lesen
- zentrale Ablage z.B. für Protokolle, Anleitungen und 
- Information durch Volltextsuche leicht auffindbar
- gesteigerte Wertschätzung existierender Dokumente
- offene Arbeiten identifiziert

### ✍️ __Bearbeiten__
  - einfache Eingabe
  - Schulungen essentiell
  - Historie: alte Versionen wieder herstellbar
    - Angst vor Fehlern nehmen

### 🫰 __Nutzen__
  - derzeit: Nutzen übersteigt Kosten
    - Struktur & zentraler Ort sehr hilfreich
  - Evaluierung ausständig (06/2025)
  - Alternative Möglichkeiten:
    - neue Bibliothekssoftware
    - Online Office Suite

:::


## Das habe ich gelernt
- Inhalte & Anforderungen kommen vom Team
- Nutzen muss erklärt und beworben werden
- Es gibt keine perfekten Lösungen!

## Es muss kein Wiki sein:

Wichtig ist, sich mit der Dokumentation auseinanderzusetzen!

<!--
- fehlende Dokumente ergänzen
- vorhandene Dokumente aktualisieren
- Wissenslücken schließen
-->

::: notes

wichtig ist, sich über die vorhandene und fehlende Dokumentation Gedanken zu machen und mit dem Team gemeinsam an einem möglichst aktuellen Wissensstand zu arbeiten.

:::

# Vielen Dank! {background-image="figures/thats-all.gif" background-opacity=0.5 background-credit="© Looney Tunes"}


## Quellen
- Definition Wiki auf [Wikipedia](https://de.wikipedia.org/wiki/Wiki)

### Fotos
- Hintergrundfotos:
    - [Verena Knöpfle](https://frauknoepfle.com/) für die Bücherei Nofels, 2024
    - Wikipedia Logo von [Nohat](https://meta.wikimedia.org/wiki/User:Nohat); Wikimedia, 2010
- GIFs:
    - Wiki Stars GIF über [tenor](https://tenor.com/view/wickie-stars-vicky-the-viking-pinch-nose-ah-i-know-gif-14995956), 2024
    - That's all Folks GIF über [tenor](https://tenor.com/view/hahaha-thats-all-folks-looney-tunes-the-end-gif-5945155), 2024

## Tipps {visibility=uncounted}
- technischer Hintergrund ist hilfreich, aber nicht zwingend notwendig
- kostengünstige Möglichkeiten evtl. bereits verfügbar
    - [Microsoft 365](https://www.office.com/) bzw. [Google Docs](https://docs.google.com)
- Self-Hosted vs. Hosted:
  - evtl. kann Wiki mit Website verbunden werden
  - Self-Hosted nur bei hoher technischer Kompetenz


## BookStack {auto-animate=true visibility=uncounted}

:::::::::::::: {.columns}
::: {.column width="50%"}
### Vorteile
+ Moderne Oberfläche
+ WYSIWYG Editor
+ Einfache Struktur 
    + Seiten
    + Bücher
    + Regale
:::
::: {.column width="50%"}
### Nachteile
- schwerer aufzusetzen / mit existierender Website kombinierbar
- wenig erweiter-/anpassbar
- anfangs etwas unübersichtlich

:::
::::::::::::::


## {visibility=uncounted background-iframe="https://viewer.diagrams.net/?lightbox=1&highlight=0000ff&layers=1&title=#R%3Cmxfile%3E%3Cdiagram%20id%3D%22V71sIDP0t6J8WiogdwQq%22%20name%3D%22MindMapIdeenInhalte%22%3E7V1Xk6O6tv41XXXvw0yRw6OxjbONc3i5RZABgwETnH79lbBxADqM2%2B7ZZx927Zo2kpBAWuv7lpaWxBtZXu9rvuwZHVcD9huBafs3svJGEDhDs%2FAPSjmcU3CaPKXovqmd064JQ%2FMIzonYOTUyNRDcFQxd1w5N75x4Lqe6jgPU8K6g7Pvu7v7epWtrd%2Fd5sg7uSqCEoSrb2dSpqYVG8hoMf82oA1M3zk1zxPmN13JS%2BNxSYMiau7tJIqtvZNl33fD0a70vAxv1nnn3hOI7uZcH84ETfuUG4nTDVraj87udnys8JC8b7My1LTvwSghC2Q%2FPwwErJgXD9c2j64SyDVNwmKCiC9MB%2FujgoVKhD9CNS5gsymvTRiNeB%2FYWhKYqnzPOFeIsvLZlBdiCrFq670aOVnZt14d5jhu3f8p1fQ34qZzkIdsmuqygZ4srANr56tLR6EK35SBIMkLftS7DiN%2FUJZq2nTSjgaUc2bBLhbW7lZW4b1BZHwTm8fbaDeXw5hqKPri9Bpp5e2m7qnV5xLO03mSrrm3LXmCeUlCZ7Pieh3wL%2FBDsb5LO410D7hqE%2FgEWOeeeZfSse4kg7u7k%2BJxo3MgwS58T5bPy6JeaL40N0OM7Onzaa2vYXXNUTnNETmtkqjHZDoHvyCEQ0KgGtzINf9y85jUplvR8qSc%2Fl3qgQY0%2FX8K%2BNsPDANhyaLpO9ZpzUogSQpSrKAJHS6UEQF%2BfxguPxznyt%2FGgx8LmRr4KJOCb8PmBP%2FRk1XT082jD2nUQvpN5le9YsPZmOEM5v1mSPV%2FP42ueSvIr%2B%2FOt8cXhfLG03V3JMdfxyyUFHNiXp%2Bro5HJ%2Bm3etKr463FR8edxEwSwQqoluxe8ummF4eg%2BUtDJ1Pe5mIle%2Bk6GJ%2B%2BksimfIj3vnjLCnJDRqH%2BqAHw%2Fi9h7HP5BoyTXhg1ykmcb53%2FzNf1xKl1JSex7cUx1XiYXiIR9uinmoQPB%2Bq2xaie5BHf441fioOlD%2FPnX4I6G7SvutrOOfyPqXRJXLiir%2FElH9U5niSPpepsjnyhT975OpC8TewOvH0PoojP4IZCbG9F8WRIq%2FF0SSTVms6fLEPRgm7%2FEswWX%2BfYL7fHHCc3ANx58tT3cW3gdDhrMPDtF9N7l%2BaLi668h223W9pG9AGB7OMxQ5Cl006QnXyXTnb45xHhxdEOhjOLpQ2%2Fwem%2F4qHP2QCYfj9%2FhxmewkVZw7%2FbtGG5HCKfa5MMVmYGpqWiZMaTgGmixlNcK2TS9A4ijbpo4MfRWOELLSBTRJF11bu44oSum422uCA3Y3ilN5Y%2BE4M5sIuSmEq65dkt7I0k3%2BO%2Fp3LU2Urxc3KpVfXaxU%2BfdeVO%2BP70xU9PZGJCg3Rc5qe1fivo58Vb694b7Gd9T7%2Fga2guZoN66IN4JUcE1bXp0XNzk4xpI8yLg1kGJ6%2BTBy5xi5dcdwbx%2F4bR7104RgHw5vW9wZZgjQE6E2d77s3QNs%2FEBnocNfRGxfd51QXMr24M62y407g8DOabfujKTcH7DcOAB%2BT1kh9yWBxR16urXk2MAMI0cHzqlO23SsU5YRhsgBWkJVEqISAdUAPjB%2FOe4S2MFvOUSprmtB1BIN2dGUCHbepY7RDRj%2Fn2LLsNY4L0Ec7qZrzmB0Ay%2BfjOP9uMm%2BepYyGssDJDQiUM7s0jljbWqanZXquCrIycFZYlGBi2xTBbD95wGbqgGFU%2FKAjWRIntRSEEX9BQxgiNTEGaMyGIBTORhAfeA%2FfQcD4OUNDHwIC7BzY%2Fe0Zm7hTx39rF9U%2FJQFa7vJfQ54iPFSCSHKCSr9Wkb%2BL8VUbNMNDWAFv4DpBHJ4vMcS%2FjtYAhkrXluAwxiasn11OkPBi%2B12hCk2WIbnn4obhu46AaLzgKCMswkH26QF%2BD%2BSYfyNriBRpgU8uaIrX4GopBGEdEj6ynHBq30dOLI3ck82Yi5yFVj1T8eqb9geTzOXbvHyXObWRMKeAHAclQI4NgfgsC%2Bs2TwGcFnvNP7fOLt%2Fgc8Gy066SeqHfDbv0VbP12XHDE5rT99gJDe3ns9MWhx7%2BwYPFTZtwRPPsWnv4hHem4%2F%2FDWOXTE14KTxn%2FZ7M4YLnGLtZT28S7XDrnc8YvkN3vQa%2BDQI0RX7f9v1nW5w5TF8YoQW4%2FF0HGJ4oYOI8Z7MOsIuD%2FZu2YXZJ%2Bb%2FSELwG9tBvX13oeYHxyGSNxyQg7NUrNjxH3AkdTVP3VbwTZvPAqgr%2F6EpiwhDnGD6E2vcC8Hdk8Bvzjztj5Rr%2B%2BHW79ksxn4mPP9vQO1Pma4EfEnL6L8%2BQ7uybG8FMqAH13q8ThUOCw3DK28fveyW3k81zBGZom8hnhylAh%2F1wRIuE2MgA66uZpPjfauP5nkYCS6LTLiYgU8zZCrPq78%2FZ%2FvbUjKFTa5EYnjHFiLzQaor6Y2z6g3WICfBlB4qY%2FfgSZWAgskDav32vsk8dO8ViZQESBUhcAw8uIMFn52v0yxYrs9uNsBz%2FTRFd%2BfZp0Djx9ODKd8LCsXtWYdKC8Ly5FvElX17Fj1QL%2BLHVqpnAKVx6hUvvX0Yrf9elx6XiWS4u%2F7t4lhe59Ipo%2B0f5gP0ZPmBTswya%2BxoffHs7Ev%2FxLhAOT0dhPTe8Oie%2Beqgake0DHdhOQTYF2RRk84zYorzt50%2BKLcrqNFeQzRec4Hls85o9qxlUJ1MsQKTPHHji7IPPCENNdo4wpWf4Bb4X%2BF7g%2ByPxAeR9fACBZ%2BMD%2BBfBO1n4lh6Ed%2FKHnEs%2FCO9k1rnUMmHH%2BoYcBQW8F%2FBewPsj8E6k4J3OCf96lfmexKrfqPQiCsK3MvlWohzN1C0AtbiYmxfKXSj3I8pN0vkuuE%2FPavvoYLivKjf1qK32Hx3b%2BTObfCjyZ8w7Iu2TZflXmXdU9gS%2F4SEIATrEzioYoGCAggEeYQA2pcB5S4GvMu%2BSsLSCAV7AAE8PYv77DJB3wGAmeqSFjiO2UKBzETNSEEVBFM%2FyA%2FB4Ss%2BzRwS8ys1LMQVPvIwnfiiqBE8bGtTreCIbyDEAwan%2BwldUEEBBAI8QQPpwSzLPV%2FSkmcJ7O02GZniMHD3wfDd0Lde2z2defmejmahCDUc6RYjpai%2B7kL91ZkiBIAWCFAiC1Agnft8bAZezBV4QePyVvSl0dkbZNoN4RQlbolUmoQxxAWvKhg8CBXawaoSFAVGof6H%2BD6g%2FT90bEJdDhG6VP%2B8zRE85SKSYQr7uvIQfmkJybHr789cOBfnTjQk8yd61Q5%2FDEN7bmPDH5YlUeeqT8lSqPHtX%2FvvfbcnOl6vQoJajZWAjNiwYr2C8gvEeYbzUPjs6h%2FBedXJWQqQF4T2f8JgfCp7l0zvxvugz%2FWPCw1MEQ3xCSH9aHvsmQTLPJbxk%2FG4Ir%2BRAojOgmMYHJAF%2FjT4qWvBewXsF7%2F0577GpsEKCzXHz0K8iPiKjtwXxPUB8yRjeEd8PhRWydOorq3zqYzrP%2Bspqam8qwX28Bf2Py6d3v3yyxT2tOOSTv%2FrKZGMocw%2FvKjiv4LyC8%2F5srpd2ThE5%2B2Tyjk1%2FCucVgZSv47wfCqQsOO9FnJdd4xOhoCumrRWMVzBewXgPMx5%2Fz3h4zpcxX%2Bfe5ArGe5l784eOfmETs%2BVyyH%2BqiueFhCavdOvx8xVghsUKV8EBBQc87ulLfVk9b4XrVbvH2KwXvxOfF4ugC74yUArjrlDsQrEfU2w%2BtXRN5Wj2q9wZiSulONbpI9ONz1pu7E8tTGPpzTwvO9WJ%2Fa90bT3yBTD4FP5hdm46vpjfXlxviq9%2B9rth7E850d4JrXu6E41OtcN%2FHNGQLs%2Fgn5RPncmfzKNznWLZu1Mz8%2FQBzmfR%2B3PtfG9fTkMD6Zh5aIjBf53TUU2qEU%2BysPP%2BndPTfGvTzvkb9I4bQvV14i%2FQwxZ%2FOXLc1K%2FgtqELlNA3A1ps4ylMw8I0fMQ0pFLowmYtQ%2BIHvxXPFp7Ap9A2lbP2xf6QJzB9SihFv2xzOJv1BHZM%2BM7IGYjwtGQ6TuE3KMihIIeHyCF9XCiTfMvzJ%2FwGiZ1bUMHzqYD7IdcCey8%2FX53APcAEXNZ%2F3HACKCIREo%2BCAwoOKDjgQQ5ILQpxORzwqlWh5MPxBQe8gAN%2BKvz75zggGxBdA8rJaRVpRVxAQQEFBTxGAZ8vH77qtECuOOrhOQzA5jDADx31QKQdQsTXgqEfoYDs6QfCBDEAn5WjAv4L%2BC%2Fg%2Fwvwn4oPIJks%2FL%2FqpB%2BuWA94Hfz%2F0HrAT8J%2Fdj1AmEwK5C%2BQv0D%2BZyB%2Fzimxr0J%2BvnD%2Fvwz5%2BR9y%2F2eOCU8LxvOQn8%2F6%2FytmHMDEHEFQ%2BH4KCigo4BkUkPfBd%2B5VFJD3iZg0J2SA%2BUaLU10X%2Bq4FEg3TwFKO4m%2FKfKpka1PTYtVfuk4oymvTRp1RB%2FYWoHLnjDOf4Pj5OttQHGMpyKqlxw%2BWLXBLcFfiuguBfzwIOQkovlxcUeKjkOJ7Yns6PeWwUxJy%2FCk73Yhg3vlDSdo3SYzmUkbQF8PjMxUx7%2Byl%2F34kb0ZzLgty%2F7WbLh6Ln%2F%2BSyOZs1cAx4mcsqswhgsTXYuuyx%2B9y9xUx6dMInymMREYYL3v71rIV2SbwiwiNwkQrTLSHTDQ2vcLO50RoPOk7DFnlxrPKPQC6bIPsmyWcZAamkih56jiZTO1fMAETIECfelBN%2B3%2FsyaqtGp5QkXayv9ksMGWPaV4bfRymOdmPOuN9Ozpw8HLFypa47s%2Fr230FSFO3WWOmvK9xXVKBjyWSvuZJZfR0sBcJkSBZGf5ZQvEV%2FZExoqOxZvISwUnRbMRD2RSkXo3dsyQsLJAzVIytHzhpz%2FJLtjyyIb4KPjR3xN6ChJnC3pgZlaY0Hjpcb8aMWr0FzJuRO5ryeBI%2BrbCkRkajK9ntbRWKibDZsWqZa05aat2MSk3OE%2BcdCRehAgnW1MNAc2EvhXnrCMRKSTJaR%2FStRCFADW6HK0aYOxolqyHlh8P2hgFoe86qyUqriliWykIQoDce7xTaqyoi7neHpWjpq9psjR2ssmTBHpR2TbsqCHNGi6rUpinrDWHtV7otQW7p3dbAwNprvTpfqJXBxuR320OtEvL9km0oZMUMNkyTJqa9eblTcycBtxgfhq0V1TSBUdqWF0RPqZgj3y0NOo554Cz4di7q9%2F1i0%2BqVx35vrS3aXilkJzMCL5V6VnmiRo2qPm%2BjLUZQBsTW6Ljq7Kd6KZpWfLBsGsZytwNNv7ZaxPJlTTbkiggb4pbbWahza4qPsSP4Y9gZVVRiwRlLyIFVqVKKJMEO19XqalZCg9o%2BMgpUekF2%2FR5d66NhLXsAn478xtGfWqWxPbTnu53X77vzaGu1jFppLE1cpaV18HbNW8gdSfGWm%2B6gf6SGZnvR1Md%2Bl1n7EVZxev0qlHYx6LpNz1qOZ%2B0Wv5oKDkkFYD%2FbtCpOdUMfqpbT84TyatpZRm3xGM4JkarOD6OJh8mRsZqLmMQ0B%2BF6olidloPezdrWp5yBOWsSNzclfI5kaccYeqfk99cHWbYWfd3VO5BDnMiySsJGbkbydt6DOaqwGAhGJRBGQ89Z7S1WPDAy1pnO1r15k5%2BoTse2Ans1Iw%2FAFajVVLYb%2Bwo%2BXIiOu7cHfdRPmyPbWRKcvDB6oGFP5u3uIhzt3HZfrxlbf9BZlTq21%2BBG8j7YlD2G7CnRMph06uijTcLOF%2FEw7JNaAw1a1aK8mmk53cp4uVRLjX1zJpcYkSnV%2FLB8IFlpb6385oHAaa4rinvQ7BgBnEutRxo%2Bm9BAsvGl1FREdeEsB63hCtYvOCIa1BqEFWFB6sKE41ymzik%2BjiONMLhDxVJQh62Bd1COPr2Ev6M6NosGex5JJLds4Qe0V%2B20va1uTZFG%2B0yFUlF%2BqY8wiaz8b76xcD8FfSPIEk%2BxFJsmDUNWjcgHNWTyVKg0ZeRQyt3EtOSryHJS0ZZHrCJHEO9jwySepCZ27GmXHkEjAqbRq8B%2FUIHgt%2B66sC3ZM4PfKrRbUIYaxEXF5akJ%2BPOuEZoQbprJ4v6VI77%2BfTKSv58r4djvnDP4CJr%2BnfgYb5kNJ7hL%2BvfYjXmEf3zIPwFZhfwzs0VK4pget0dyFBiHvWvp0XTMmltS205L4b62HmyXrZ67nmClDi9pHViw5C2XK9iK0HP83cFhFPR72yYhaSFUr0unv9KCGiKl0eYrBEvSkeGQjSTumAXSRCds1dsHdGeFhP9yW2d%2FElrnSMcVCJFznLVZvrtsk3wwQrxGUgLgOYI9mIgA67Rn9ckDkvUlapfeg4qLFBPr7SqBIy67vBH1%2FMXW0myW7eFHhumdHk3R9tNRCCsRQrPEYfbUgj9HDIMaxaQeix4LvZSk0b3jnj9I6kSUoUgIlVmJ77n4im11OCfiy6GkUAMGW0fEcjUNPKRi9WXYODJ8ZEhbYljmFJJyG6ZzaBxIpj6r8pg8WLE0hGxxWiX23JQcDJyatiMBQ3ojssLyqxFQlCByja3amYLRIYxMCavZBJR18TifMS2Or0vBFkrtKhxrItJ2jQCInTV2oO3oJRETNSVVDdaYkeygPnCmCwUmjji22aAcbuRgeH0Q%2BWyjrusrRt%2FiyHLoGRq%2BrMJ3dLdHrUlRSwp2ihgNfJYajmHypLdsSpbJbTYsagx1YxMMalva87sOLZIGwvYKzZE1GclItVuu2kCvEZ7QYNjtZE9rFdHsy9VjY6F3RfKwGtmrUk%2Bq1s1my2s3K1XMkpvUQjLY%2BvFQI%2BrH1U4ymHar1FLHhFxrSlVyQqv9XssTD2p5fdSxFjOrL3Q4UmX%2B2B7vld68V9fFsLSug%2BhIgTAQ6GkFjolwEA7jkiTiCGKHLTlkSkx9YK36ht7iKu2pvdG7Qa8liq2mWw5aYnXXglUYq2oLWS%2FNXmcCdJzrg12zJo7bdEusRZN5v7Ob7UZhPJC1kTwHTSTUZXu1o0HZVrnKviz5u6NZnhh7rWaW6ootjMrCerFiA5KCubuwBVwesk1ACRW2WWrVo5o81HFy2NbMWM18Zjyt2mMXH5ao5lTvVyi%2F2xrq60F%2FUeFhfyBLrjmqEoNNB7jjTXfV3%2FS6OutGdp%2FXWzV3yK0qTWVqRWupqrX0g1qTDL%2B5s1iuaUy7o0bN3QmrjgVkvsWVKS1yRw0tbG4q05FIm7P9blhR6IaojldzVvB2%2FfXELjUFui1NuY4xdAar6WDruTUbU9mSXpIso4a6eo%2FU0cMwgTzuPYewq62htTVb9kar21WT2KqtWs1vRbBQtxXtebpOlgiVnA1HzbbfbA1C9zjiFAbvikNcrkuq5ZOLqU5smtqSbzV7lojRHhEZnT1Wk0ZMlQpIf1cNAqilA3ZQcnuY7botV%2B4dzF3f6DB1i8dW7JHorUrSqj2vawYrOPrW25fDYKBMZ7O5L%2FWUfr1rrkvOUaofp%2Fim0cEXzblY4bCFImFTe9cP9Kjjbe1Jjxopk6M0jTxDmQR0n2E6Pjsz2C188VZX3vmtTnXejQ5YCNYepmu7ktgf4RbWlNSqMzfXOr1omXxj5et9NHauoRKdvjAae3aHOpblRcU%2BDvvi3mzNorm2tii5vsfGfcNje0dV60qt9TEwy2O77IUVpbdpTNdNf9QellcbaxhaVbpud3W6Dygzsjq9fp8bj6NOrcLZbTzqW0fA7CkDKve8M66WSlDEOtSerI8aYCOXxwfQ8getCn4QO1jgtmtV12x2iGEUYX0xdLY8WacUMBbr09lSb%2FSXsuFyPXqLLNvl1qj29G60xcuHQe%2Bws2o94uAvYRPTScMp64q%2B2M7pckUVpqG6nq3p42HXECHSivzBZruwG%2Fp2Zc57Tabsbhb%2BatNol0s0Bw0WWexYswYCaY8pW4hUWsp8fPCapH8oYX1jbW4YaqfYM769X3H1g9UtW3Jvq4HBhMc1gRFFnACr0STEBz3jYJG93WSyXCg07%2BxmoLbERnKoWtjROwo4h48JaCkJ003EdARJGk83E2SClafjSWXUINRppz1pa%2BJuXLWH%2FsHjlQnFtUblzghoHRnN3RrjTWnqebs2KVdxaaXJfo8k8fpWX3vTMc3j7trVl8eYD6WazAYTTTKjvhYAG8HGYLeY8aYHlu56tg198ljphsMWVa3pQ2KybwMVHUMwDRcr%2FMBPPWWzmRH7ynxDektvpdcn7NpfLoSZzi4DfFI52j42PGwCvoLVd9SSmHUmCN5HcAolzOr8QoVXaM%2BrOJz3tm0fzRiGg9g61Avr8BnWIUncn66L53g86CRy%2BM7jQZFPsguzcaZT9D1JUz%2BdjdFwDNnOOYoQvmB478b8%2BupTnj%2F06nnC%2FmEDnSPfccvnvkjkMlk1458lGzSZ8pBj2QXLlx1ketksdTdfYOLFPQO%2FE4XEi7iWfd10fsUuazgIGObt4664%2BkEZHf1NnGqnytBcFU%2BykkQvnYA6GFa5lNX7Nq9LlzfN5Dwbuv%2FXyRONHg1n33m2OMC6rADfkkOgu37s2oeddT43Bg5eAMUEaMCJP8hjgHXs%2Bz9GgbyGP5dyEKCEy6udnvv%2BXZDRc037VK3ylMWFD7K042UrAyoVbPKfrEBP0YbLJziTxUs6xzect35%2FkeTvqUM2Kud9mPymq5jI7v7KyAm8xfSC98D0dnHpX0O490bFGYlzZOsyVA9%2FQ57ICQ0h83aG4um1xsdkK29p4ClQK5wOvkLnVn2Gt18ATe490LwH6Ucq%2BiKyn9pLUBZbA8MHfnyCFzom5RaJk2dS%2FBz4LVD5PXXKsXWeomHkFzTsaeiN3H8ukpjrMj8cIKPjauhguOr%2FAw%3D%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E" background-interactive=true}

