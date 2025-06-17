# System-Monitor-Digilab & Discord Bot

## 🔧 Projektübersicht

Dieses Projekt kombiniert einen **System-Monitor für den Raspberry Pi** mit einem **Discord Bot**. Der System-Monitor zeigt auf einem Digilab-Touchscreen die CPU-Auslastung, Temperatur, RAM und Netzwerkstatus an. Der Discord Bot ermöglicht die Fernabfrage dieser Systemdaten über Discord-Kommandos.

## 📦 Funktionen

### System-Monitor (Digilab)
- Anzeige von:
  - CPU-Temperatur & Auslastung
  - RAM-Verbrauch
  - IP-Adresse & Netzwerkstatus
- Optimiert für Touchscreen-Bedienung
- Läuft direkt auf dem Raspberry Pi (kein Browser, kein HTML)

### Discord Bot
- Slash-Commands zur Systemabfrage
- Zeigt Live-Systemstatus im Discord-Channel
- Einfache Erweiterbarkeit für weitere Befehle

## 🚀 Technologien
- **Node.js**
- **Python**

## ⚙️ Installation

```bash
git clone https://github.com/Jerry123456789ccc/system-monitor-digilab.git
cd system-monitor-digilab
npm install
