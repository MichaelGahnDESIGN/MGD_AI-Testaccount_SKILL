# Fehlersuche und Grenzen

| Problem | Ursache / Lösung |
|---|---|
| Mail kommt nicht an | Spam-Ordner prüfen; Zustellung kann Minuten dauern; Absender-Domain der Zielseite prüfen |
| Zielseite lehnt `+` ab | Manche Dienste filtern Plus-Adressen. Alternative: eigene Domain mit Catch-all-Postfach |
| Zweite Anfrage mit derselben Adresse wird ignoriert | Viele Seiten blocken doppelte offene Anfragen je Adresse. Neue Plus-Adresse nehmen |
| Agent möchte auf Live-Seite ein Konto anlegen | Nicht erlaubt. Den Inhaber bitten, das Konto selbst anzulegen |
| Gmail-Connector findet nichts | Suchbegriff `to:name+tag@gmail.com` prüfen und Zeitraum erweitern |
