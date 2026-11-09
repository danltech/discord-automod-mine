# 🤖 Discord AutoMod Mine

Ein robustes Tool zur automatischen Moderation von Discord-Servern mittels Regex.

Dieses Repository bietet eine strukturierte Aufteilung der Verstoßstypen (Low, Medium, High, Critical), um die Automatisierungsentscheidungen des Bots präzise zu steuern und False Positives zu minimieren.

## ⚙️ Funktionen

*   **Strukturierte Moderation:** Kategorisierte Wortlisten für unterschiedliche Schweregrade (`low.txt` bis `critical.txt`).
*   **Erweiterbar:** Einfache Hinzufügung neuer Wörter und Muster in den jeweiligen `.txt` Dateien.
*   **Regelbasierte Filterung:** Nutzung von Regex für komplexe Mustererkennung (Spam, URLs, Beleidigungen).
*   **Scam/URL-Erkennung:** Einführung von `scamurls.txt`, um Shortener, Gewinnphrasen und verdächtige Discord Invite Links (`discord.gg`) zu blockieren.

## 🚀 Installation

1.  Klonen Sie das Repository:
    `git clone https://github.com/danltech/discord-automod-mine.git`
2.  Platzieren Sie die Dateien in Ihrem Discord Bot Projektordner.
3.  Stellen Sie sicher, dass Ihr Bot die `low.txt`, `medium.txt`, `high.txt`, `critical.txt` und `scamurls.txt` Dateien korrekt lädt.

## 📜 Kategorien der Verstöße

*   **`low.txt` (Low Severity):** Geringe Verstöße (z.B. leichte Beleidigungen, Anfängerfehler).
*   **`medium.txt` (Medium Severity):** Alltägliche Schimpfwörter, Spam-Links, moderate Aggression.
*   **`high.txt` (High Severity):** Stark beleidigende oder bedrohliche Sprache, Eskalation.
*   **`critical.txt` (Critical Severity):** Rassismus, Hassrede, extreme Gewalt – sofortige harte Maßnahmen erforderlich.

## 🌐 Scam URL & Link Moderation (scamurls.txt)

Dieses neue Modul dient zur Erkennung und Blockierung potenziell betrügerischer URLs und Einladungslinks (`discord.gg`). Die Datei `scamurls.txt` verwendet ein Regex-Format, um komplexe Muster wie Shortener, Gewinnphrasen und verdächtige Domain-Endungen zu erfassen. Es ist entscheidend, diese Liste regelmäßig mit aktuellen Bedrohungsinformationen zu pflegen.

## 🤝 Beitrag leisten

Wir freuen uns über jeden Beitrag zur Verbesserung der Wortlisten und zur Optimierung des Codes! Bitte siehe die Datei `CONTRIBUTING.md` für Details.
