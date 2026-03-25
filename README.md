# 📅 ICS CRM Reminder v1.0

Ein **Claude Cowork Skill** für strukturierte Kalender-Reminder mit CRM-Daten. Entwickelt für B2B-Sales-Teams, die ihre Follow-ups nicht in Excel, sondern direkt im Kalender tracken.

> **"Sag Claude, wen du wann anrufen willst — du bekommst eine ICS-Datei mit allen Deal-Infos."**

## Was macht dieser Skill?

Er generiert professionelle **.ics Kalender-Dateien** mit eingebetteten CRM-Informationen:

- **Kundendaten** — Firma, Ansprechpartner, Telefon, E-Mail
- **Deal-Status** — Phase, Budget, letzte Interaktion
- **Nächster Schritt** — Was genau beim Anruf passieren soll
- **Priorität** — Hoch / Mittel / Niedrig mit visuellen Markern
- **Alarm** — Konfigurierbare Erinnerung vor dem Termin

Die ICS-Datei ist **Doppelklick-importierbar** in Apple Calendar, Google Calendar und Outlook.

## Für wen?

- **B2B-Vertriebler** die ihre Pipeline im Kalender sehen wollen
- **Agenturen** die Kundenansprachen systematisch planen
- **Freelancer** die Follow-ups nicht vergessen dürfen
- **Jeder** der kein CRM-Tool bezahlen will, aber trotzdem Struktur braucht

## Installation

```bash
clawhub install KopfKinoK3/ics-crm-reminder
```

## Auch verfügbar auf

- 🦞 **LobstrHunt** — [lobstrhunt.com/skills/KopfKinoK3/ics-crm-reminder](https://lobstrhunt.com/skills/KopfKinoK3/ics-crm-reminder)
- 🦀 **ClawHub** — [clawhub.ai/KopfKinoK3/ics-crm-reminder](https://clawhub.ai/KopfKinoK3/ics-crm-reminder)

## Beispiel

Du sagst zu Claude:

> "Erstell mir einen Reminder: Siemens AG anrufen am 15. April um 10 Uhr, Ansprechpartner Dr. Müller, Thema WebAR-Konfigurator, Priorität hoch."

Claude generiert eine ICS-Datei mit diesem strukturierten Inhalt:

```
═══ viSales CRM Reminder ═══

📋 KUNDE
Firma: Siemens AG
Ansprechpartner: Dr. Müller

🎯 ANLASS
Thema: WebAR-Konfigurator Folgegespräch
Priorität: ⚡ HOCH

📊 DEAL STATUS
Phase: Angebot
Budget: 25.000 €

➡️ NÄCHSTER SCHRITT
Angebot nachfassen
```

## Projektstruktur

```
ics-crm-reminder/
├── SKILL.md              # Skill-Manifest (YAML frontmatter + Anweisungen)
├── scripts/
│   └── generate_ics.py   # ICS-Generator (Python 3, keine Dependencies)
├── LICENSE               # MIT
└── README.md
```

## Requirements

- Python 3.x (keine externen Dependencies)
- Claude Cowork, Claude Code, Cursor oder Codex CLI

## Hintergrund

Gebaut von **viSales GmbH** (Bochum) — B2B-Agentur für visuelle Vertriebskommunikation. Wir machen 3D-Visualisierung, WebAR und Produktkonfiguratoren für den Maschinenbau.

Dieser Skill entstand aus dem eigenen Bedarf: Sales-Reminder ohne CRM-Overhead, direkt im Kalender.

## Lizenz

MIT — frei nutzbar, auch kommerziell.
