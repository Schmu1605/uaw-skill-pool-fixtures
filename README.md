# uaw-skill-pool-fixtures

Synthetische Prüfskills für die Gesamtabnahme (Paket 10) des Skill-Pools im
Ultimate-AI-Workcenter. Kein produktiver Nutzen. Die Telemetrie-Adresse im
Rewrite-Fall nutzt die reservierte Domain `.invalid` und ist nie erreichbar.

| Ordner | Zweck |
|---|---|
| `einzel/` | Einzelinstallation |
| `paket/` | Paket mit Teilerfolg (ein gültiges Mitglied, ein Mitglied über dem Eingabebudget) |
| `unterbrechung/` | Technische Unterbrechung (Worker während der Modellphase beenden) |
| `rewrite/` | Umschreibenlassen (unnötiger Netzwerkzugriff) |
| `update/` | Update eines aktiven Skills (Commit 2: gültiges Update, Commit 3: scheiterndes Update) |
