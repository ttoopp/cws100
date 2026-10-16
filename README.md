Disassembling a cheap ALDI vintage CWS 100 Camera

# 📷 Kamera Hacking: Teardown & Custom Firmware Setup

Dieses Repository dokumentiert, wie ich meine Kamera geöffnet habe und vorbereite, um eigenen Code (Custom Firmware) darauf aufzuspielen. 

---

## 🛠️ Benötigtes Werkzeug & Vorbereitung
* **Präzisions-Schraubendreher** (z. B. Phillips )
* **Kunststoff-Spudger / Plektrum** (um das Gehäuse ohne Kratzer zu öffnen)
* **ESD-Armband** (zum Schutz vor statischer Aufladung)

---

## 🔍 Schritt-für-Schritt: Kamera öffnen

### 1. Gehäuse trennen
* Mit dem Spudger vorsichtig entlang der Gehäusenaht fahren.
* **Achtung:** Auf Flachbandkabel (Ribbon Cables) achten, die Vorder- und Rückseite verbinden!

### 2. Schrauben entfernen
* Schrauben auf der Platine lösen
* Flachbandkabel trennen

### 3. Analyse der Platine (PCB)
* Suche nach **UART/Seriell-Pins** (GND, TX, RX, VCC) für den Hardware-Zugriff.
* Identifikation des Hauptchips (Mikrocontroller/SoC) und des Flash-Speichers.

---

## 💻 Firmware-Vorbereitung (Eigener Code)
* [ ] Dump des originalen Flash-Speichers erstellen (Backup!).
* [ ] Bootloader analysieren.
* [ ] Eigene Toolchain für den Chip einrichten.

---

## ⚠️ Wichtige Sicherheitshinweise
* **Garantieverlust:** Das Öffnen der Kamera lässt jegliche Garantie erlöschen.
* **Kurzschlussgefahr:** Vor dem Öffnen unbedingt den Akku entfernen und ggf. Restspannung abbauen.

