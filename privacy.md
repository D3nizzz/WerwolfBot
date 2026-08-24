# Datenschutz & Nutzungsbedingungen – Werwolf-Bot

Diese Seite beschreibt, welche Daten der Werwolf-Discord-Bot speichert
und unter welchen Bedingungen er genutzt werden kann. Sie ist bewusst
kurz gehalten und deckt sich inhaltlich mit dem `/werwolf_privacy`-Befehl
im Bot selbst.

## Welche Daten werden gespeichert?

- **Discord User-ID** (eine Zahl, kein Name, kein Avatar, kein
  Discriminator) – wird als Schlüssel für die Statistik-Tabelle genutzt.
- **Aggregierte Spielstatistiken** pro User: gespielte/gewonnene Runden,
  rollenspezifische Werte (z. B. Werwolf-Kills, richtige/falsche
  Guesses, richtige/falsche Votes, Anzahl Tode).
- **Server-Konfiguration** pro Discord-Server (Guild-ID): zuletzt
  genutzte Rollenauswahl und Rundeneinstellungen (Timer, Ein-/Aus-
  Schalter), damit ein Host sie nicht bei jeder neuen Runde erneut
  einstellen muss. Außerdem die IDs der vom Bot automatisch erstellten
  Stats-/Ergebnis-Kanäle.

Alle Daten werden in einer lokalen SQLite-Datenbank auf dem Server
gespeichert, auf dem der Bot läuft.

## Welche Daten werden NICHT gespeichert?

- Keine Nachrichteninhalte
- Keine Sprachaufzeichnungen
- Keine sonstigen personenbezogenen Daten (Name, Avatar, E-Mail, etc.)

## Eigene Daten löschen

Über den Befehl `/werwolf_privacy_loeschen` kann jede Person ihre
eigene, gesamte gespeicherte Statistik jederzeit unwiderruflich löschen
lassen. Serverbezogene Konfigurationsdaten (Rollenpresets) können vom
Bot-Owner auf Anfrage gelöscht werden.

## Nutzungsbedingungen (Kurzfassung)

- Der Bot wird kostenlos und ohne Garantie auf ständige Verfügbarkeit
  bereitgestellt ("as is"). Es besteht kein Anspruch auf einen
  bestimmten Funktionsumfang oder eine bestimmte Betriebszeit.
- Missbrauch (z. B. absichtliches Stören anderer Server, Ausnutzen von
  Fehlern, Spam) kann dazu führen, dass ein Server oder Nutzer-Account
  vom Bot-Owner gesperrt wird.
- Der Bot ist ein privates, nicht-kommerzielles Hobbyprojekt. Es
  besteht keine Verbindung zu Discord Inc.

## Kontakt

Fragen, Lösch-Anfragen für Server-Konfigurationsdaten oder Fehler-
Meldungen bitte an den Bot-Owner richten (z. B. über den Server, auf
dem der Bot ursprünglich betrieben wird, oder das verlinkte
Support-/GitHub-Repository, falls vorhanden).

---

*Diese Seite kann sich mit zukünftigen Bot-Updates ändern. Stand: siehe
Commit-Historie des Repositories, falls öffentlich einsehbar.*