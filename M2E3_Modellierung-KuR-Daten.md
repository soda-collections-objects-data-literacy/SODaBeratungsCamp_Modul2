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

Einheit 3: **Modellierung und Erfassung in WissKI/SCS als graphbasierte Datenstruktur**  

**Dauer:** ~ 40 Min.

---

## Lernziele

Lernende können...

---

## Voraussetzung

*Die Kenntnis über KuR-MDS als Werkzeug zur Strukturierung von Konservierungs- und Restaurierungsdaten aus Einheit 1 (M2E1) und Kenntnis der Inhalte aus BeratungsCamp Modul 1: Arbeiten mit strukturierten Daten in der Konservierungs- und Restaurierungsdokumentation - Von der Theorie in die Praxis - erläutern und analysieren, Einheit 2: Einführung in die Grundlagen der Dokumentation von Konservierungs- und Restaurierungsprozessen in wissenschaftlichen Sammlungen sind von Vorteil.*

---

## 3.1 Ereignisorientierte Erfassung von KuR-Maßnahmen im WissKI/SCS

**Ereignisorientierte Datenerfassung im SCS**

Für die Erfassung von Konservierungs- und Restaurierungsdaten wird der [**Semantic Coworking Space (SCS)**](https://manager.scs.sammlungen.io/) als eine von SODa entwickelte cloudbasierte Arbeitsumgebung eingesetzt. 

Der SCS stellt verschiedene digitale Werkzeuge für die Arbeit mit Sammlungsdaten bereit, insbesondere die virtuelle Forschungsumgebung [**WissKI (WissenschaftlicheInfrastruktur)**](https://wiss-ki.eu/de) zur **strukturierten Erfassung und Modellierung von Daten** [1] nebst dem **fachspezifischen Modell für Konservierungs- und Restaurierungsdaten** [2] welches auf dem zuvor eingeführten Metadatenschema für die Dokumentation von Konservierungs- und Restaurierungsmaßnahmen (KuR-MDS) [3] basiert.

Konservierungs- und Restaurierungsmaßnahmen sind stets ein **zielgerichteter Prozess** **zeitlich begrenzter Ereignisse**, die einen **konkreten Objektbezug** haben und in deren Verlauf unterschiedliche Informationen zusammenkommen können. [4] Dazu gehören beispielsweise:

- beteiligte Personen,
- verwendete Materialien und Werkzeuge,
- durchgeführte Untersuchungen,
- Zustandsveränderungen sowie
- fachliche Bewertungen und Entscheidungen.

Für die digitale Erfassung bedeutet dies, dass eine **Restaurierungsmaßnahme nicht lediglich als Eigenschaft eines Objekts erfasst wird, sondern als eigenständiges Ereignis, mit dem die jeweils relevanten Informationen verknüpft werden**. 

Die in WissKI/SCS verwendete Modellierung orientiert sich genau aus diesem Grund am [**CIDOC Conceptual Reference Model (CIDOC CRM)**](https://cidoc-crm.org/), das Beschreibungen komplexer Zusammenhänge im Bereich des Kulturellen Erbes über **Ereignisse und die zwischen ihnen bestehenden Beziehungen** ermöglicht.[5] Diese **ereignisorientierte Modellierung** bietet damit eine Möglichkeit, die unterschiedlichen Informationen, die im Verlauf einer Konservierungs- oder Restaurierungsmaßnahme entstehen, systematisch miteinander in Beziehung zu setzen.

**Perspektivwechsel bei der Dateneingabe**

Diese ereignisorientierte Perspektive ist für die Datenerfassung zunächst ungewohnt: Statt ausschließlich vom Objekt und seinen Eigenschaften auszugehen, steht das **Ereignis der Konservierungs- und Restaurierungsmaßnahme** im Mittelpunkt. 


> Für die Erfassung im WissKI/SCS bedeutet dies, die **jeweiligen Maßnahme als Ereignis zu denken und zu erfassen** und die daran **beteiligten Objekte, Personen, Materialien, Werkzeuge, Untersuchungen und weiteren Informationen mit diesem Ereignis in Beziehung** zu setzen.

---

## 3.2 Ereignisorientierung bei der Datenerfassung am Beispiel

### Vom KuR-MDS zur hierarchisch strukturierten Eingabemaske

Die folgende Abbildung 1 zeigt eine Erfassungslogik, die einer klassischen Eingabemaske entspricht (links). Diese Abbildung zeigt einen Ausschnitt des Beschreibungstextes der **Sektion "Erhaltungskonzept"** sowie die zugehörigen **Metadaten aus dem KuR-MDS: insbesondere konservatorische Zielsetzunug**. 

![Visualisierung Erfassung als Eigenschaft des Objekts](assets/2026_09_09-ModellierungalsObjekteigenschaft.png)

>**Abbildung 1:** Ausschnitt des KuR-MDS als hierarchisch strukturierte Eingabemaske in der Mockup-App

Dazu gehören beispielsweise **"Anlass der Erhaltungsmaßnahmen"** und **"Konservatorische Zielsetzung"** (Planungsphase) sowie Angaben zur **"Erhaltungsmaßnahme"** selbst, etwa die **"Zuständige Person"** (Durchführungsphase). 

In der Mockup-App werden diese Metadaten in Form einer Eingabemaske visualisiert, die einer **vertrauten Erfassungsoberfläche** entspricht. Die einzelnen **Erfassungsfelder sind hierarchisch angeordnet**, sie bilden die hierarchische Struktur des KuR-MDS ab.

---

### Von der Eingabemaske zurm Ereignismodell

Die Abbildung 2 macht dagegen sichtbar, wie diese fachlichen Angaben im WissKI/SCS auf Grundlage des zugrunde liegenden Datenmodells erfasst werden. 

**Der im KuR-MDS als "Anlass der Erhaltungsmaßnahme** bezeichnete Aspekt wird dabei nicht als einfache Eigenschaft der Maßnahme erfasst, sondern als Bezug zu einem weiteren Ereignis modeliert. 

Im dargestellten Beispiel wird die **Erhaltungsmaßnahme mit einem *Condition Assessment*** verknüpft. Die Angabe *Connected with condition assessement* beschreibt diese Beziehung. Über *Create Condition assessment for reference* kann ein entsprechendes Ereignis angelegt und als Bezug zur Erhaltungsmaßnahme erfasst werden.

![Visualisierung ereignisorientierte Erfassung des Anlasses der Erhaltungsmaßnahme](assets/2026_09_09-EreignisorientierteErfassungWissKISCS1.png)

>**Abbildung 2:** Gegenüberstellung eines Ausschnitts des KuR-MDS Eingabemaske in der Mockup-App (links) und Modellierung des "Anlasses der Erhaltungsmaßnahme" als verknüpftes Ereignis im WissKI/SCS (rechts)

**Hinweis:**

> Damit wird ein zentraler Unterschied zur vertrauten Eingabemaske deutlich:
> **Bei der Datenerfassung im WissKI/SCS müssen fachliche Angaben als eigenständige Ereignisse gedacht und erfasst werden.**
> Der "Anlass" ist somit nicht lediglich eine Information, die in ein Feld eingetragen wird, sondern kann selbst zum Ausgangspunkt einer weiteren Ereignisbeschreibung und ihrer Verknüpfung mit der Erhaltungsmaßnahme werden.

---

### Die "Zuständige Person" als Teil einer Ereignisstruktur

Abbildung 3 zeigt am Beispiel der **"Zuständigen Person (Erhaltungsmaßnahme)"**, wie eine im KuR-MDS hierarchisch unter der Erhaltungsmaßnahme eingeordnete Information im WissKI/SCS als Teil eine Ereignisstruktur erfasst wird. Während die "Zuständige Person" in der vertrauten Eingabemaske unmittelbar als Angabe zur Erhaltungsmaßnahme erscheint, wird sie im WissKI/SCS über eine dazwischenliegende **Activity** modelliert: Die Erhaltungsmaßnahme (*Preservation*) **beginnt mit einer Aktivität** (*Begins with activity*). Für diese Aktivität wird anschließend die ausführende Person über **Carried out by** erfasst.

![Visualisierung ereignisorientierte Erfassung des Erhaltungsmaßnahme](assets/2026_09_09-EreignisorientierteErfassungErhaltungsmasznahme.png)

>**Abbildung 3:** Ereignisorientierte Erfassung der "Zuständigen Person" über eine Aktivität im WissKI/SCS

**Hinweis:**

> Auch hier wird deutlich, dass die Erfassung im WissKI/SCS nicht ausschließlich der hierarchischen Anordnung von Eingabefeldern folgt.
> Die im KuR-MDS als **"Zuständige Person" bezeichnete Information wird vielmehr über die Aktivität mit der Erhaltungsmaßnahme** verknüpft.
> Dadurch kann nicht nur festgehalten werden, **wer** an einer Maßnahme beteiligt war, sondern zugleich, **im Zusammenhang mit welcher Aktivität** diese Person beteiligt war.

---

### Beispielmodellierung in WissKI/SCS


xxxxx????xxx TODO

>**Video:** Modellierung des "Anlasses der Erhaltungsmaßnahme und zuständige Person" als verknüpftes Ereignis im WissKI/SCS am Beispiel


---

## 3.2 Gemeinsame Aufgabe im Medienarchäologie WissKI/SCS

[Medienarchäologie WissKI/SCS](https://wisski-medienarchaeologie.wisski.scs.sammlungen.io)

- Datensatz **„Rave Racer“** kennenlernen
- fehlende Angaben gemeinsam ergänzen
- Daten zu **T42 Tennis for Two"" erfassen
  
---

## 3.3 Diskussion

> **Was musstet ihr bei der Erfassung in WissKI/SCS anders denken als bei der Arbeit mit einer hierarchisch strukturierten Eingabemaske?**

Weitere Diskussionsfragen:

- An welchen Stellen der Dateneingabe muss **zu einer ereignisorientierten Perspektive** gewechselt werden?
- Welche Information lässt sich nicht einfach aus den Dokumentationen in ein entsprechendes Feld im WissKI/SCS übertragen?
- Welche Angaben wurden im WissKI/SCS zu **eigenständigen Ereignissen oder Entitäten**?
...


## Quellenangaben

[1] https://sammlungen.io/

[2] Verweis auf KuR-Modell, sobald publiziert.

[3] NFDI4Objects Conservation Data Framework Online Portal. (o. D.). Metadatenschema für die Dokumentation von Konservierungs- und Restaurierungsmaßnahmen (kurz: KuR-MDS), Version 1.0. https://nfdi4objects.github.io/n4o_conservation_data_framework/conservation-metadataschema/ (Stand: 11.09.2026)

[4] Schwenk, G. A., & Fischer, K. (2025, May 21). SODa Forum: Konservierungs- und Restaurierungsdokumentation gemeinsam weiterdenken - Ontologieentwicklung im Dialog. Zenodo. https://doi.org/10.5281/zenodo.15481743

[5] CIDOC CRM

---

### Metadaten

author: Canan Hastik

orcid: https://orcid.org/0000-0003-1729-4642

email: c.hastik@igsd-ev.de

author: Gudrun Schwenk

orcid: https://orcid.org/0009-0002-3156-8339

email: g.schwenk@igsd-ev.de

sessiontitle: Analyse und Strukturierung von Konservierungs- und Restaurierungsdaten am Beispiel medienarchäologischer Erschließung

sessionnumber: 2

unittitle: Modellierung und Erfassung in WissKI/SCS als graphbasierte Datenstruktur

unitnumber: 3  

duration unit: 45 Minuten (PT0H45M)

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
