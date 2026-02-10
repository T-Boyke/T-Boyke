# ADR-0001: Einführung der Architektur-Roadmap (ADR)

**Status:** Akzeptiert  
**Datum:** 2026-02-10  
**Beteiligte:** Tobias Boyke

---

## 1. Kontext
Die Komplexität des Profil-Repositories wächst durch die Integration verschiedener Technologiestacks wie **C# 14**, **.NET 10** und **Kotlin 2.3**. Um die Konsistenz der Engineering-Standards wie **Clean Architecture**, **TDD** und **DDD** langfristig zu sichern, fehlte bisher ein strukturiertes Format zur Dokumentation grundlegender Architekturentscheidungen.

## 2. Entscheidung
Es wird ein formales Verfahren für **Architectural Decision Records (ADR)** eingeführt. Jede signifikante Änderung an der Architektur oder dem Tech-Stack muss in diesem Format dokumentiert werden. Als Basis dient das Nygard-Format, um Kontext, Entscheidung und Konsequenzen präzise festzuhalten.

## 3. Begründung
* **Transparenz**: Entscheidungen wie die Wahl der **AGPLv3-Lizenz** werden nachvollziehbar begründet.
* **Wartbarkeit**: Neue Mitwirkende verstehen die technologische Evolution, ohne den gesamten Code manuell analysieren zu müssen.
* **Disziplin**: Der Prozess erzwingt eine bewusste Auseinandersetzung mit den im **CODE_OF_CONDUCT.md** definierten Effizienz-Zielen.

## 4. Konsequenzen
* **Positiv**: Klare Historie über die Nutzung von C# 14 und .NET 10 Features.
* **Positiv**: Standardisierung der Dokumentation gemäß den "Sacred Code"-Vorgaben.
* **Neutral**: Zusätzlicher zeitlicher Aufwand bei der Erstellung neuer Architektur-Komponenten.
