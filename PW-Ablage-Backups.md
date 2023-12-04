# PW, Ablage & Backup Aufgaben DS

## Authentifizierung und Autorisierung

- "Peter hat das Recht auf den Ordner Geschäftsprozesse zuzugreifen."  
  -> Autorisierung

- "Martina sperrt ihren Bildschirm vor der Kaffeepause und muss ihr Passwort eingeben, wenn Sie zurückkommt."  
  -> Authentifizierung

- "Standard User haben keinen Zugriff auf die Server-Management-Konsole."  
  -> Autorisierung

- "Standardmässig kann in Linux Dateisystemen für jede Datei oder Ordner ein Benutzer, eine Gruppe, sowie die Zugriffsberechtigungen Lesen, Schreiben und Ausführen definiert werden."  
  -> Autorisierung

- "Nur Lehrerpersonen können in MS Teams einer Gruppe Lernende hinzufügen oder entfernen."  
  -> Autorisierung

- "Permission denied."  
  -> Autorisierung

- "Für das Online-Banking benötige ich mein Benutzername, mein Passwort und das Foto-TAN App."  
  -> Authentifizierung

## Have I been pwned?

- Weshalb macht es Sinn, unterschiedliche Passwörter zu verwenden?  
  -> Ein geleaktes Passwort kann schnell geändert werden, und selbst wenn nicht, beschränkt sich der Schaden vermutlich nur auf diesen einen Pawned Account. Wenn dasselbe Passwort überall verwendet wird, kann eine ganze Identität gestohlen werden, da auch die Sicherheitsmaßnahmen mit dem Passwort umgangen werden können. 

- Mit welchen Ihrer persönlichen Zugangsdaten lässt sich am meisten Schaden anrichten?  
  -> Ich verwende seit Jahren Passwortmanager, und bin daher nicht sehr anfällig für Attacken, welche es probieren, auf alle meine verschiedenen Konten zuzugreifen. Ich verwende einen Hardware Key für die 2FA an meinem Passwortmanager, also selbst dieses Passwort ist nicht kritisch. 

## Der eigene Passwort-Manager

- Was tun Sie, wenn Sie ihr Master-Passwort vergessen?  
  -> Sehr unwahrscheinlich. Ich habe bei der Bank Backup-Keys gespeichert. Ich habe auch einen Dead-man's-switch, welcher nach zu langem Nicht-Anmelden, einer bestimmten Person Zugriff auf meine Passwörter gibt. 

- Wie erstellen Sie ein Backup von Ihrer Passwortdatenbank?

---

- Wenn Sie einen Cloud-Dienst verwenden: Was tun Sie, wenn Sie keinen Zugriff auf Ihren Account mehr haben?  
  -> Das wäre sehr mühsam… Ich vertraue jedoch meinem Anbieter. Es wäre eventuell schlau, periodisch die Passwörter als Plaintext zu exportieren und an einem sicheren Ort aufzubewahren.


| Service       | Funktion                                                                    | Betroffene Daten                      | Backup                            | Wiederherstellung                                                                             |
|---------------|-----------------------------------------------------------------------------|---------------------------------------|-----------------------------------|---------------------------------------------------------------------------------------------|
| Telefon       | Anrufe tätigen und empfangen, Voicemail                                    | Kontaktliste, Anrufliste, Voicemails  | iCloud Backup                     | Kontakte und Anruflisten werden durch Wiederherstellen des iCloud-Backups zurückgeholt.     |
| Fotos         | Speicherung von Bildern und Videos                                         | Fotos und Videos                      | iCloud-Fotomediathek              | Fotos und Videos sind über die iCloud-Fotomediathek auf neuen Geräten zugänglich.           |
| WhatsApp      | Nachrichtensofortversand (Text, Foto, Video, Ton)                          | Chatverläufe, Fotos, Videos           | iCloud Backup                     | Bei der Installation der App wird gefragt, ob ein iCloud-Backup wiederhergestellt werden soll. |
| Notizen       | Erstellen und Speichern von Notizen                                        | Geschriebene Notizen                  | iCloud Backup                     | Notizen können durch Wiederherstellen eines iCloud-Backups zurückgeholt werden.             |
| Mail          | Senden und Empfangen von E-Mails                                           | E-Mails und Anhänge                   | Serverseitiges Backup             | E-Mails sind nach erneuter Anmeldung im E-Mail-Konto auf dem neuen Gerät wieder zugänglich.  |
| Kalender      | Verwaltung von Terminen und Ereignissen                                    | Kalendereinträge                      | iCloud Backup                     | Kalendereinträge werden durch Wiederherstellen des iCloud-Backups zurückgeholt.              |
| App Store     | Download und Update von Apps                                                | App-Liste, Einkäufe, Updates          | iCloud Backup                     | Apps müssen erneut heruntergeladen werden, Einkaufshistorie bleibt erhalten.                |
| Nachrichten   | Senden und Empfangen von SMS und iMessages                                 | SMS und iMessages                     | iCloud Backup                     | Nachrichtenverlauf kann durch das iCloud Backup wiederhergestellt werden.                   |
| Google Maps   | Navigation und Ortsinformationen                                           | Gespeicherte Orte, Suchverlauf        | Mit Google-Konto synchronisiert   | Durch Anmeldung im Google-Konto auf einem neuen Gerät wieder zugänglich.                    |
| Telegram      | Nachrichtensofortversand (Text, Foto, Video, Ton)                          | Nachrichten, Medien, Kontakte         | Mit Telegram-Cloud synchronisiert | Bei der Installation der App wird gefragt, ob die Cloud-Daten wiederhergestellt werden sollen. |
| Instagram     | Teilen und Ansehen von Fotos und Videos                                    | Hochgeladene Fotos und Videos, Kontakte | Mit Instagram-Servern synchronisiert | Durch Anmeldung im Konto auf einem neuen Gerät wieder zugänglich.                            |
| iCloud Drive  | Speicherung von Dateien und Dokumenten                                     | Dateien und Dokumente                 | iCloud Backup                     | Dateien sind über iCloud Drive auf neuen Geräten zugänglich, wenn diese Option aktiviert ist. |
| Authenticator | Generierung von Zwei-Faktor-Authentifizierungscodes                        | Authentifizierungsdaten               | Kein automatisches Backup         | Wiederherstellung variiert je nach Dienst; einige bieten Wiederherstellungscodes an.        |
| Wallet        | Speicherung von Kreditkarten und Bordkarten                                | Zahlungsinformationen, Bordkarten     | iCloud Backup                     | Karteninformationen werden durch das iCloud Backup wiederhergestellt.                        |
| Spotify       | Streaming von Musik                                                         | Playlists, gespeicherte Songs          | Mit Spotify-Konto synchronisiert  | Durch Anmeldung im Konto auf einem neuen Gerät wieder zugänglich.                            |
