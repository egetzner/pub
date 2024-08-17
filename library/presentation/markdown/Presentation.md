---
title: Bücherei Wiki
subtitle: Wissensaustausch im Wandel
author: Elisabeth Getzner
institute: Bücherei Nofels
date: September 2024
keywords:
- Wissensmanagement
- Wiki
- Dokumentation
subject: Wiki
description: Projektbericht im Rahmen der Ausbildung für ehrenamtliche und nebenberufliche Bibliothekarinnen und Bibliothekare
category: Projektbericht
abstract: Planung und Einführung einer Wissens- und Informationsdatenbank (Wiki) für Mitarbeiter:innen der Bücherei Nofels. Es werden die Anforderungen an diese Software geklärt und die technische Umsetzung beschrieben.
#background-image: figures/chuttersnap-AG2Ct_DqCh0-unsplash.jpg
#parallaxBackgroundSize: 6016px 4016px
---

# Bilder {data-visibility=hidden}

![Colourful Books](figures/books-8660361.svg)

Image by <a href="https://pixabay.com/users/rui_libe-20958821/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8660361">rui line</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8660361">Pixabay</a>


# Ausgangslage

## Unser Team 
- 15 ehrenamtliche Personen
- 1-2 Personen pro Dienst (meist die selben)
- Verantwortung stark verteilt

🗃️

### Anleitungen 

- gedruckt in Ordner abgelegt
- am PC verfügbar (Word Dokumente)

<!-- ![Altersverteilung](figures/age_distribution.png)-->

---

## Kommunikation & Austausch
- 🗒️ Post-Its und Zettelwerk 
- 💬 WhatsApp-Gruppe
- ✉️ E-Mail
  - Protokolle
  - interessante Veranstaltungen
- 👥 Teamsitzungen 
  - ca. 1x im Quartal

::: notes
- Relativ großes Team (15 Personen)
- Arbeit meist getrennt in kleinen Gruppen (2-3 Personen)
- Kommunikation & Austausch in Teamsitzungen, E-Mail oder Whatsapp
- Diverse Anleitungen, von denen nicht alle wissen
:::

## Probleme

- ungleicher Wissensstand
  - schwer, alle Mitglieder zu erreichen
- Protokolle schwer zu durchsuchen
- Zettelwerk:
  - nur vor Ort zugänglich
  - Informationen nicht nachvollziehbar 
    - von wem, seit wann?

::: notes
- wenig Zeit
- kaum geschultes Personal
- keine Person die für etwas fix zuständig ist
- unklare Aufgabenverteilung
  - unklar: wer hat was schon gemacht, was muss gemacht werden
- ungleicher Wissensstand

:::

# Ich hab's! {background-image="figures/wickie-stars.gif"}

::: {.fragment}
Ein Wi(c)ki(e) für die Bücherei Nofels
:::

---

## Was ist ein Wiki?  {background-image="figures/Wikipedia-logo-v2.svg" background-opacity=0.1}

> Website, deren Inhalt von Besuchern nicht nur _gelesen_ sondern auch _verändert_ werden kann \todo{CITATION}

Beispiele
: 
- Enzyklopädie: [Wikipedia](https://wikipedia.org "Wikipedia")
- Sachbücher: [WikiBooks](https://de.wikibooks.org/wiki/Hauptseite)
- Anleitungen: [WikiHow](https://www.wikihow.com/Main-Page)
- Pop Kultur: [Fandom](https://www.fandom.com/), [TV Tropes](https://tvtropes.org/)

## Wiki in Organisationen {background-image="" background-opacity=0.2}

- Erfahrung & Wissen dokumentieren
- Zugriff auf bereits existierenden Lösungen
- gemeinschaftliches Arbeiten (Kollaboration)
  - _Author_ 👤 und _Zeitpunkt_ ⏲ ersichtlich

![Unternehmenswiki [Confluence](https://www.atlassian.com/de/software/confluence)](figures/confluence-review.png){width=40%}

::: notes

TODO: opacity / background - Confluence?

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

# Planung

## Leitfragen

::: incremental
1. 👓 __Lesen__: Wissen zugänglich machen
2. ✍️ __Bearbeiten__: Inhalte abändern und schreiben
3. 🫰 __Nutzen__: Kosten und Wartungsaufwand

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

---

### Mit dem Team
1. Anforderungen und Erwartungen klären
2. Ideen für Inhalte sammeln

![Ideen für Wiki-Inhalte](figures/mindmap_content.png){ width=70% }

---

### Technische Analyse

- existierende Lösungen finden (z.B. Träger)
- technische Einschränkungen und Anforderungen beachten
  - Hosting
  - Wartung
  - zusätzliche Kosten
- Wiki-Systeme mit Anforderungen vergleichen [^1]

# Umsetzung

## Unsere Anforderungen
- Einfache Bedienung
  - benutzerfreundliche Texteingabe (WYSIWYG[^2])
  - übersichtliche Darstellung
- Arbeit von zu Hause aus
- Benutzerrollen
- geringe Kosten
- wenig Wartungsaufwand

[^2]: _What You See Is What You Get_
:
Aussehen entspricht dem Ergebnis (wie z.B. bei Microsoft Word)

## Entscheidung für ein Wiki {auto-animate=true}
- 82 Wikis zur Auswahl bei [WikiMatrix](https://www.wikimatrix.org/)
- Nach Anforderungen und technische Limitationen
    - 2 freie Lösungen: [DokuWiki](https://www.dokuwiki.org/dokuwiki) vs. [BookStack](https://www.bookstackapp.com/)

:::::::::::::: {.columns}
::: {.column width="50%"}

![DokuWiki](figures/dokuwiki_2.png)
   
:::
::: {.column width="50%"}

![BookStack](figures/bookstack.png)

:::
::::::::::::::

## BookStack {auto-animate=true}

![BookStack](figures/bookstack.png)

## BookStack {auto-animate=true}

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
- schwerer aufzusetzen
- kaum anpassbar
- unübersichtlich

:::
::::::::::::::

## Wiki aufsetzen

1. Hosting beantragen bzw. installieren
    - monatl. Kosten: ca. 5 EUR/Monat
2. Benutzer importieren
    - jedes Teammitglied hat eigenen Benutzer
3. Inhalte importieren
4. Rechte verwalten
    - wer darf was?

## Nachbereitung

1. __Schulungen__❗
    - Suche & Navigation
    - Bearbeiten
1. Benutzerrechte pflegen
    - Benutzer hinzufügen/löschen
    - Schreibzugriff limitieren
5. Kosten- & Nutzen analysieren
    - Benutzerfeedback

[^1]: link to wiki comparison site

# Ergebnisse {background-image="figures/bookstack_willkommen.png" background-opacity=0.2 }

## Willkommensseite {background-image="figures/bookstack_willkommen.png" background-size=auto}
## Regale {background-image="figures/bookstack_regale.png" background-size=auto}
## Bücher {background-image="figures/bookstack_books.png" background-size=auto}
## Jahresübersicht {background-image="figures/bookstack_2024.png" background-size=auto}

## Beantwortung der Leitfragen {auto-animate=true}

---  

## Beantwortung der Leitfragen {auto-animate=true}

### 👓 Lesen
- zentrale Ablage z.B. für Protokolle, Anleitungen und 
- Information durch Volltextsuche leicht auffindbar
- gesteigerte Wertschätzung existierender Dokumente
- offene Arbeiten identifiziert

---

## Beantwortung der Leitfragen {auto-animate=true}

### ✍️ __Bearbeiten__
  - einfache Eingabe
  - Schulungen essentiell
  - Historie: alte Versionen wieder herstellbar
    - Angst vor Fehlern nehmen

---

## Beantwortung der Leitfragen {auto-animate=true}

### 🫰 __Nutzen__
  - Derzeit: Kosten übersteigt Nutzen
    - Struktur & zentraler Ort sehr hilfreich
  - Evaluierung ausständig (06/2025)
  - Alternative Möglichkeiten:
    - neue Bibliothekssoftware
    - Online Office Suite


## Das habe ich gelernt
- Es gibt keine perfekten Lösungen!
- Team ins Boot holen:
  - Nutzen muss erklärt und beworben werden
  - Inhalte & Anforderungen kommen vom Team
  
- Langzeit-Projekt:
  - Längere Verwendung für Evaluierung notwendig

## Fazit
Wichtig ist, sich über die vorhandene und fehlende Dokumentation Gedanken zu machen und mit dem Team gemeinsam an einem möglichst aktuellen Wissensstand zu arbeiten.

# Vielen Dank! {background-image="figures/thats-all.gif" background-opacity=0.5}

## Tipps {visibility=uncounted}
- technischer Hintergrund ist hilfreich, aber nicht zwingend notwendig
- kostengünstige Möglichkeiten evtl. bereits verfügbar
    - [Microsoft 365](https://www.office.com/) bzw. [Google Docs](https://docs.google.com)
- Self-Hosted vs. Hosted:
  - evtl. kann Wiki mit Website verbunden werden
  - Self-Hosted nur bei hoher technischer Kompetenz

## Vergleich zw. DokuWiki & BookStack

## Content-Ideen {background-color=white visibility=uncounted}

![Ideen für Wiki-Inhalte](figures/mindmap_content.png)

---

