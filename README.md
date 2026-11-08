# 🤖 Discord AutoMod Mine

Ein robustes Modul zur automatischen Moderation von Discord-Servern mittels Reguläre Ausdrücke.

Dieses Repository bietet eine strukturierte Aufteilung der Verstoßstypen (Low, Medium, High, Critical), um die Automatisierungsentscheidungen des Bots präzise zu steuern und False Positives zu minimieren.

## ⚙️ Funktionen

*   **Strukturierte Moderation:** Kategorisierte Wortlisten für unterschiedliche Schweregrade.
*   **Erweiterbar:** Einfache Hinzufügung neuer Wörter und Muster in den jeweiligen `*.txt` Dateien.
*   **Regelbasierte Filterung:** Nutzung von regulären Ausdrücken für komplexe Mustererkennung (Spam, URLs, Beleidigungen).

## 🚀 Installation

1.  Klonen Sie das Repository:
    \`git clone https://github.com/danltech/discord-automod-mine.git\`
2.  Platzieren Sie die Dateien in Ihrem Discord Bot Projektordner.
3.  Stellen Sie sicher, dass Ihr Bot die `low.txt`, `medium.txt`, `high.txt` und `critical.txt` Dateien korrekt lädt.

## 📜 Kategorien der Verstöße

*   **`low.txt` (Low Severity):** Geringe Verstöße (z.B. leichte Beleidigungen, Anfängerfehler).
*   **`medium.txt` (Medium Severity):** Alltägliche Schimpfwörter, Spam-Links, moderate Aggression.
*   **`high.txt` (High Severity):** Stark beleidigende oder bedrohliche Sprache, Eskalation.
*   **`critical.txt` (Critical Severity):** Rassismus, Hassrede, extreme Gewalt – sofortige harte Maßnahmen erforderlich.

## 🤝 Beitrag leisten

Wir freuen uns über jeden Beitrag zur Verbesserung der Wortlisten und zur Optimierung des Codes! Bitte siehe die Datei \`CONTRIBUTING.md\` für Details.
