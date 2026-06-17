# SQL Lernplattform

**Live:** [tower4me.github.io/Datenbanken & SQL](https://tower4me.github.io/Lerneinheit-Datenbanken-SQL/)

Eine interaktive Lernplattform für SQL und Datenbankgrundlagen, gebaut für Azubis und Einsteiger ohne Vorkenntnisse. Alle Konzepte werden von Grund auf erklärt, mit Alltagsbeispielen, einer durchgehenden Story und echten SQL-Übungen direkt im Browser.

---

## Inhalt

| Modul | Thema |
|-------|-------|
| 01 | Datenbanken – Was, Warum, Arten, ACID, persistent vs. flüchtig |
| 02 | SQL Grundlagen – DDL, DML, DCL, Systeme im Vergleich |
| 03 | Datentypen & Constraints – INT, VARCHAR, DECIMAL, BLOB, NOT NULL, UNIQUE... |
| 04 | DDL – CREATE, ALTER, DROP, TRUNCATE, Normalisierung, Index |
| 05 | DML – SELECT, INSERT, UPDATE, DELETE, JOIN, Aggregat-Funktionen |
| 06 | DCL – GRANT, REVOKE, Rechteverwaltung |
| 07 | Sicherheit – SQL Injection, Prepared Statements, Best Practices |
| ★  | Gesamtquiz – 20 Fragen aus allen Modulen mit Auswertung |

Jedes Modul hat ein Quiz mit direktem Feedback (richtig/falsch + Begründung) und die praktischen Module haben ein interaktives SQL-Terminal.

---

## Features

- **Echtes SQL-Terminal** – SQLite läuft direkt im Browser via WebAssembly, kein Server nötig
- **Story-Modus** – Die TowerTech GmbH führt durch die Praxisaufgaben (inkl. Azubi-Chaos und DROP TABLE als Rache)
- **DCL-Simulation** – GRANT/REVOKE simuliert in JavaScript, da SQLite kein Rechtesystem hat (klar gekennzeichnet)
- **Dialekt-Hinweise** – Unterschiede zwischen SQLite, MySQL und PostgreSQL sind überall markiert
- **Gesamtquiz mit Empfehlungen** – zeigt nach Abschluss welche Module nochmal durchgegangen werden sollten
- **Vollständig offline** – einmal geladen funktioniert alles ohne Internetverbindung

---

## Technologien

- Vanilla HTML, CSS, JavaScript – kein Framework, kein Build-Tool
- [sql.js](https://github.com/sql-js/sql.js) – SQLite als WebAssembly im Browser
- Google Fonts (DM Sans, DM Mono, Outfit)
- GitHub Pages als Hosting

---

## Zielgruppe

Azubis und Einsteiger ohne Datenbankerfahrung. Lieber zu viel erklärt als zu wenig. Abkürzungen werden beim ersten Auftreten immer ausgeschrieben.
