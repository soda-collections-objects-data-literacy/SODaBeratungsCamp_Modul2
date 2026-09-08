<!--
author: Canan Hastik und Gudrun Schwenk
email: soda@sammlungen.io

title: SODa BeratungsCamp - Einheit 1
version: v1.0.0
language: DE

icon:     https://raw.githubusercontent.com/chastik/Beratung_Dateityp_Bild/refs/heads/main/SODa-Logo_full.svg
link:     https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODaBeratungsCamp_Modul1/refs/heads/main/soda.css
          https://fonts.googleapis.com/css?family=Noto+Sans

comment: Dieses Modul [Text ergänzen]
-->


# SODa BeratungsCamp 

**Modul 2: Analyse und Strukturierung von Konservierungs- und Restaurierungsdaten am Beispiel medienarchäologischer Erschließung**  

Einheit 2: **Analyse und Strukturierung unstrukturierter Konservierungs- und Restaurierungsdaten**  

**Dauer:** ~ 30 Min.

---

## Lernziele

Lernende können...

2.1  unterschiedliche Formen und Quellen von Dokumentationsdaten im Kontext medienarchäologischer Erschließung benennen.

2.2  konservierungs- und restaurierungsrelevante Informationen in heterogenen und unstrukturierten Dokumentationen benennen.

2.3  Kategorien des KuR-MDS für unstrukturierte Dokumentationen anwenden.

2.4  Fehlende, mehrdeutige oder nur implizit dokumentierte Informationen benennen.

2.5  Herausforderungen bei der Überführung unstrukturierter Dokumentationen in strukturierte Forschungsdaten erläutern.

---

## Voraussetzung

Kenntnis über KuR-MDS als Werkzeug zur Strukturierung von Konservierungs- und Restaurierungsdaten aus Einheit 1 (M1E1) und Kenntnis der Inhalte aus Modul 1 ist von Vorteil.

---

## 1.1 Von der Dokumentation zu strukturierten KuR-Daten

Bei der konservierungs- und restaurierungsbezogenen Arbeit entstehen kontinuierlich Forschungsdaten. Diese können sich auf die materielle Beschaffenheit, den Erhaltungszustand eines Objekts, auf Untersuchungen, durchgeführte Maßnahmen oder auf die dabei getroffenen Entscheidungen beziehen. 

Gleichzeitig können diese Informationen in sehr unterschiedlichen Dokumentationsformaten vorliegen.

**Leitfrage:**

> Wie gelangen wir von einer bereits vorhandenen Dokumentation zu strukturierten KuR-Daten?

In bestehenden Dokumentationen sind relevante Informationen häufig nicht bereits als einzelne Datenfelder vorhanden. Sie können beispielsweise in Fließtexten, Abbildungen, technischen Beschreibungen, Projektwebseiten oder unterschiedlichen analogen und digitalen Informationsquellen enthalten sein.

Bevor Informationen strukturiert erfasst oder modelliert werden können, müssen daher zunächst die relevanten Informationseinheiten identifiziert, voneinander unterschieden und fachlich eingeordnet werden:

Insbesondere computerbasierte Medien weisen aufgrund ihrer technischen Komplexität eine große Vielfalt an Dokumentationen und damit verbundenen Informationsquellen auf. Informationen zu einem Objekt können sich beispielsweise auf Hardware, Software, technische Funktionen, Nutzung, Veränderungen, Reparaturen oder Rekonstruktionen beziehen und über unterschiedliche analoge und digitale Quellen verteilt sein.

Hinzu kommt, dass computerbasierte Medien häufig nicht allein durch ihre materielle Substanz bestimmt werden. Für ihr Verständnis und ihre Erhaltung können ebenso funktionale Zusammenhänge, Software, technische Dokumentationen sowie Wissen über Bedienung und Nutzung relevant sein. Die für eine konservierungs- und restaurierungsbezogene Erschließung benötigten Informationen müssen daher häufig aus verschiedenen Quellen zusammengeführt und in ihrem jeweiligen Zusammenhang bewertet werden.

Das Beispiel MEGA65 verdeutlicht, wie stark relevante Informationen über unterschiedliche Dokumentationsformen und Plattformen verteilt sein können:

**Beipiel:**

??[MEGA65](https://mega65.org/)

![MEGA65](https://mega65.org/)

[preview-lia](https://mega65.org/)

>
> - Projektwebseite: [MEGA65 - 8-Bit Computer](https://mega65.org)
>
> - Projektwiki: [MEGA65 Wiki](https://mega65.atlassian.net/wiki/spaces/MEGA65/overview) mit Einführungen in die Grundlagen, Anleitungen, Tutorials, Hilfsprogrammen, Beschreibung der Hardware, Systementwicklung und Archivseiten.
>
> - File Server: [File Host](https://files.mega65.org) für Software Releases aber auch dem [Kompendium](https://files.mega65.org/?id=d668168c-1fef-4560-a530-77e9e237536d)
>
> - Youtube Kanal: [@MEGA65retro](https://www.youtube.com/@MEGA65retro) für Community Videos uvm.
>
> - Discord Server [MEGA65@Discord](https://mega65.org/chat) für Alpha Releases, Diskussionen und Kollaboration
>
> - Forum: [Official MEGA65 support forum @ Forum64](https://mega65.net) das deutschsprachige Community Forum
>
> - GitHub Repo's: [MEGA65 Open-Source](https://github.com/MEGA65) und [XEMU](https://github.lgb.hu/xemu) für VHDL des MEGA65 cores, Tools, Emulator, usw.
>
> - Aternative Computer / Arcade / Konsolen-Cores kostenlos auf https://cores.mega65.org
>   


**Fazit:**

Eine Dokumentation ist nicht automatisch ein strukturierter Datensatz.

Relevante Informationen können:

- an unterschiedlichen Orten liegen,
- in unterschiedlichen Formaten vorliegen,
- unterschiedlich detailliert beschrieben sein,
- mehrfach vorkommen,
- nur indirekt aus dem Kontext hervorgehen oder vollständig fehlen.

Die strukturierte Erschließung beginnt deshalb mit der Analyse vorhandener Informationen.


## 1.2 Medienarchäologische Beispiele

Für die folgende Analyse werden zwei Beispiele aus dem Bereich medienarchäologischer Erschließung betrachtet:

- CurcuitLab Rave Racer
- MEGA e.V. T42

Beide Beispiele verdeutlichen, wie unterschiedlich eine medienarchäologische Arbeit zur Wiederherstellung eines Objektes sein kann.

**Beispiel: Rave Racer**

Das Rave Racer Projekt dokumentiert die historische Aufarbeitung (sog. Restauration) eines zweisitzigen Arcade-Fahrsimulators des japanischen Herstellers Namco aus dem Jahr 1995. Das Gerät wurde dem Circuit Lab 2025 vom Computerspielemuseum als Leihgabe zur Verfügung gestellt und wird im Zusammenhang mit einer technischen Restaurierung an der Burg Giebichenstein Kunsthochschule Halle untersucht und bearbeitet.

Das Beispiel enthält damit Informationen zu unterschiedlichen Bereichen:

- zum Objekt selbst,
- zu seiner Geschichte,
- zu beteiligten Personen und Institutionen,
- zu technischen Eigenschaften,
- zu Untersuchungen,
- zum Restaurierungsprozess,
- sowie zu verschiedenen Formen der Dokumentation.

**Beispiel: T42 / Tennis for Two**

Beim Projekt T42 / Tennis for Two ging es darum eine Rekonstruktion (re-creation) aus fragmentarischer Quellenlage herzuleiten. Es lag keine umfassende technische Dokumentation vor noch war das Original vorhanden. Aus wenigen heterogenen Informationen mussten technische Funktion, Spiellogik und konkrete Umsetzung erschlossen werden.

Zur Verfügung standen unter anderem:

- Informationen zur Spiellogik,
- ein Schaltplan des an einem Analogcomputer „gesteckten“ Spiels,
- das Handbuch des verwendeten Analogcomputers sowie
- eine Darstellung beziehungsweise Dokumentation des damaligen Aufbaus am Tag der offenen Tür.

Eine Rekonstruktion (re-creation) schließt Dokumentationslücken nicht dadurch, dass fehlende Informationen einfach ergänzt werden. Sie erzeugt neue Aussagen auf Grundlage vorhandener Quellen, technischer Zusammenhänge und fachspezifischer Interpretation. 

Für eine nachvollziehbare Dokumentation muss deshalb erkennbar bleiben, was überliefert und was rekonstruiert wurde – und worauf die Rekonstruktion beruht.

**Fazit:**

Die beiden Beispiele zeigen unterschiedliche Ausgangssituationen medienarchäologischer Erschließung:

- Bei Rave Racer ist ein materielles Objekt vorhanden, das untersucht und bearbeitet werden kann. Im Verlauf der Arbeit entstehen und verändern sich Informationen zum Objekt, seinem Zustand, seiner technischen Funktionsweise und zu den durchgeführten Maßnahmen.

- Bei T42 / Tennis for Two ist das ursprüngliche Objekt beziehungsweise der historische Aufbau nicht mehr vorhanden. Die Rekonstruktion basiert deshalb auf fragmentarisch überlieferten Quellen, aus denen technische und funktionale Zusammenhänge erschlossen und fehlende Informationen teilweise hergeleitet werden müssen.

Damit unterscheiden sich nicht nur die vorhandenen Informationen, sondern auch deren Entstehungs- und Erkenntniskontexte.

Eine Information kann beispielsweise am vorhandenen Objekt beobachtet, einer historischen Quelle entnommen, während einer Untersuchung erzeugt oder im Zuge einer Rekonstruktion aus anderen Informationen hergeleitet worden sein.

Für eine strukturierte Konservierungs- und Restaurierungsdokumentation reicht es daher nicht aus, lediglich festzuhalten, welche Information vorliegt. Ebenso relevant ist, woher sie stammt, in welchem Zusammenhang sie entstanden ist und wie sie erschlossen wurde.



> Strukturierung bedeutet deshalb nicht nur, vorhandene Informationen zu ordnen, sondern auch ihre Zusammenhänge und Entstehungskontexte nachvollziehbar zu machen.



## 1.3 Übung: Dokumentation lesen und annotieren 

Übung: Gruppenarbeit

> Gruppe 1 und 2: CircuitLab – Rave Racer
>   
> Gruppe 3 und 4: MEGA e. V. – T42 / Tennis for Two
> 
> In den beiden vorgestellten Beispielen liegen Informationen zur medienarchäologischen Erschließung in Form von Projektdokumentationen vor.
> 
> In der folgenden Übung wird untersucht, welche konservierungs- und restaurierungsrelevanten Informationen in diesen Dokumentationen enthalten sind und wie sie mithilfe des KuR-MDS strukturiert erschlossen werden können.
>
> Jede Gruppe erhält die jeweilige Projektdokumentation als Präsentation (.ppt/.pptx) sowie das KuR-MDS als Referenz.
>
> **Leifragen:**
>
> - Welche Aussagen stammen unmittelbar aus einer Quelle – und welche Aussagen entstehen erst durch fachliche Interpretation und Rekonstruktion?
>
> - Welche Informationen sind vorhanden und wie können wir sie mithilfe des KuR-MDS strukturieren?
>
> Dauer: ca. xx Min.


## 1.4 Vergleich und gemeinsame Auswertung

Nach der Annotation werden die Ergebnisse der vier Gruppen gemeinsam betrachtet. Dabei geht es nicht darum, eine „richtige“ Annotation festzulegen, sondern unterschiedliche Zuordnungen, Informationslagen und Interpretationen sichtbar zu machen.

Zunächst vergleichen jeweils die beiden Gruppen, die dasselbe Beispiel bearbeitet haben, ihre Ergebnisse.

>
> Gemeinsame Auswertung
>
> - Welche Informationen habt ihr identifiziert und welchen Elementen des KuR-MDS habt ihr sie zugeordnet?
> 
> - Wo unterscheiden sich die Annotationen der beiden Gruppen?
> 
> Dauer: ca. 4 Min.
> 


> Anschließend werden die beiden Beispiele miteinander verglichen.
>
> Diskussion und Vergleich im Plenum
>
> Welche Informationen ließen sich unmittelbar aus der Dokumentation entnehmen?
>
> Wo war fachliche Interpretation notwendig?
>
> Wo wurden Informationen aus anderen Informationen oder Quellen hergeleitet bzw. rekonstruiert?
>
> Welche Informationen ließen sich mit dem KuR-MDS eindeutig strukturieren und wo entstanden Schwierigkeiten?
>
> Welche für eine strukturierte Dokumentation relevanten Informationen fehlten?
> 
> Dauer: ca. 3 Min.



**Fazit:**

> Strukturierung bedeutet nicht nur, Informationen Kategorien zuzuordnen. Sie erfordert auch, ihren Kontext, ihre Herkunft und die Beziehungen zwischen den Informationen nachvollziehbar zu machen.

 
---

## Quellenangaben

[1]

---

### Metadaten

author: Canan Hastik

orcid: https://orcid.org/0000-0003-1729-4642

email: c.hastik@igsd-ev.de

author: Gudrun Schwenk

orcid: https://orcid.org/0009-0002-3156-8339

email: g.schwenk@igsd-ev.de

sessiontitle: 

sessionnumber: 2

unittitle: 

unitnumber: 1  

duration unit: 15 Minuten (PT0H15M)

rights: CC-BY 4.0

rights description: Dieses Material steht unter der Lizenz Creative Commons Attribution 4.0 International.

rights link: https://creativecommons.org/licenses/by/4.0/

SODaformat: SODa Workshop, SODa Train-the-Trainer

SODagestaltungsprinzip: Forschendes Lernen

classification: Forschende, Sammlungsleitende und -betreuende. Technisches admin Personal, Hilfskräfte, Interessierte

classification description: basierend auf SODaPersonas-Beschreibungen, Reichert R., Hastik, C., Gnyp, A., Markert, M., & Tharandt, L. (2025). SODa Personas. Zenodo. https://doi.org/10.5281/zenodo.15574575

mediatype: Text

technical format: Markdown mit LiaScript-Erweiterungen

file format: .md | MIME: text/markdown

software: LiaScript

runtime environment: https://liascript.github.io

keywords: sammlungsbezogenes Forschungsdatenmanagement; Konservierung; Restaurierung; Dokumentation

references:

