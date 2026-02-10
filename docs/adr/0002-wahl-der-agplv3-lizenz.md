# ADR-0002: Wahl der GNU Affero General Public License v3.0 (AGPL-3.0)

**Status:** Akzeptiert  
**Datum:** 2026-02-10  
**Beteiligte:** Tobias Boyke

---

## 1. Kontext
Das Projekt definiert sich als "Technical Temple of the Omnissiah" und legt extrem hohe Maßstäbe an Code-Qualität, Dokumentation und technologische Reinheit (C# 14, .NET 10). Es besteht das Bedürfnis, sicherzustellen, dass sämtliche Erweiterungen oder Modifikationen, insbesondere im Cloud-Kontext, der Community unter denselben Bedingungen zur Verfügung stehen.

## 2. Entscheidung
Sämtliche Code-Bestandteile dieses Repositories werden unter der **GNU Affero General Public License v3.0 (AGPL-3.0)** lizenziert. Diese Entscheidung ist bindend für alle zukünftigen Module und Beiträge.

## 3. Begründung
* **Copyleft-Stärke**: Im Gegensatz zur Standard-GPL schließt die AGPL die "Cloud-Lücke". Wenn der Code über ein Netzwerk (SaaS) bereitgestellt wird, muss der Quellcode ebenfalls offengelegt werden.
* **Philosophie**: Dies entspricht den "Sacred Code"-Vorgaben. Wer die Technologie nutzt, muss zur Integrität des "Tempels" beitragen.
* **Transparenz**: Die Lizenz erzwingt eine Offenlegung von Derivaten, was die Einhaltung unserer Architektur-Standards (Clean Architecture, DDD) auch in Forks fördert.

## 4. Konsequenzen
* **Positiv**: Sicherstellung der dauerhaften Offenheit des Quellcodes, auch bei Cloud-Nutzung.
* **Positiv**: Rechtlicher Schutz gegen proprietäre Ausbeutung ohne Gegenleistung.
* **Negativ**: Kann die Nutzung in geschlossenen kommerziellen Enterprise-Umgebungen einschränken, was jedoch im Sinne der Projekt-Integrität akzeptiert wird.
