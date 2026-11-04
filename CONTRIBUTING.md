# Zur Übungswebsite beitragen

Dieses Repository gehört zur GitHub-Skills-Übung. Beiträge erfolgen über einen eigenen Branch und einen Pull Request.

## Entwicklungsumgebung

1. Repository klonen und Python 3.13 mit einer virtuellen Umgebung verwenden.
2. `python -m pip install -r requirements.txt` ausführen.
3. Eine lokale MongoDB-Testinstanz unter `localhost:27017` bereitstellen. Die Anwendung legt beim Start Beispieldaten an; keine produktive Datenbank verwenden.
4. Vom Repository-Wurzelordner `python -m uvicorn src.app:app --reload --host 127.0.0.1 --port 8000` ausführen.
5. Die Übungswebsite unter http://localhost:8000 öffnen.

## Änderungen und Prüfung

Beschreibende Branchnamen verwenden, Änderungen lokal mit Beispieldaten prüfen und im Pull Request erklären. Python-Code folgt PEP 8 und verwendet verständliche Namen. Rückmeldungen vor dem Merge bearbeiten; keine echten Personen- oder Zugangsdaten einchecken.

## Fragen und Vorschläge

Zuerst vorhandene Issues prüfen. Neue Fehlerberichte sollen Schritte zum Nachstellen, erwartetes und tatsächliches Verhalten enthalten. Sicherheitslücken über den privaten Meldeweg aus SECURITY.md melden, sobald die Sicherheitsrichtlinie eingerichtet ist.
