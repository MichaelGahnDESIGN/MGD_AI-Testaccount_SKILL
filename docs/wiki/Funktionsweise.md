# Funktionsweise der Plus-Adressen

Gmail ignoriert alles zwischen `+` und `@`. Mails an `name+test1@gmail.com` und `name+test2@gmail.com`
landen beide bei `name@gmail.com`, die Zielseite hält sie aber für zwei verschiedene Adressen.

## Namensschema

`<name>+<projekt>-<nummer oder zweck>@gmail.com`

Beispiele: `name+shop-1@gmail.com`, `name+shop-reset@gmail.com`.

## Warum das hilft

- Registrierung und Bestätigungsmail beliebig oft testen.
- Jede Mail lässt sich über das `to:`-Feld einem Test zuordnen.
- Der Agent liest die Mails über einen Gmail-Connector, ohne dass du Codes abtippen musst.

## Konten-Liste

Eine Datei im Projekt (z. B. `.tmp/testaccounts.md`) mit: Adresse, Zweck, Datum, Umgebung, Status.
Keine Passwörter, keine Tokens.
