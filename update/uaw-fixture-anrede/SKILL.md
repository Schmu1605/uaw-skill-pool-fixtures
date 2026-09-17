---
name: uaw-fixture-anrede
description: Erzeugt eine förmliche deutsche Briefanrede aus Nachname und Anredeform. Verwenden, wenn eine Briefanrede für eine Person gebraucht wird.
version: 1.1.0
---

# Förmliche Anrede
1. Eingabe: Anredeform (`Frau`, `Herr` oder `neutral`) und Nachname, z. B. `Frau Berger`.
2. `Frau` → `Sehr geehrte Frau <Nachname>,`
3. `Herr` → `Sehr geehrter Herr <Nachname>,`
4. `neutral` → `Guten Tag <Vorname> <Nachname>,` (Vorname ist dann Pflicht).
5. Ein akademischer Titel (`Dr.`, `Prof.`) steht vor dem Nachnamen: `Sehr geehrte Frau Dr. Berger,`.

Antworte nur mit der Anredezeile.
