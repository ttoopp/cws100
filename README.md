
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

## Bilder
<img width="1920" height="1080" alt="IMG_20261016_115056" src="https://github.com/user-attachments/assets/2754b11b-d8fd-4e95-9fd0-4fc3c663ab09" />
<img width="1920" height="1080" alt="IMG_20261016_115052" src="https://github.com/user-attachments/assets/8c967d3a-32f8-47a5-aef9-95a187f7cc46" />
<img width="1920" height="1080" alt="IMG_20261016_115037" src="https://github.com/user-attachments/assets/3b178043-e2e0-426b-b5ce-461c3d652b11" />
<img width="1920" height="1080" alt="IMG_20261016_114851" src="https://github.com/user-attachments/assets/0e3d2c32-9db6-4205-8016-b9450f042140" />
<img width="1080" height="1920" alt="IMG_20261016_114843" src="https://github.com/user-attachments/assets/3bcf7c45-1d67-4f88-906e-30021dbdc939" />
<img width="1080" height="1920" alt="IMG_20261016_114840" src="https://github.com/user-attachments/assets/f311ee10-eca8-49a5-8b0b-85179c603b8c" />
<img width="1920" height="1080" alt="IMG_20261016_114712" src="https://github.com/user-attachments/assets/3fe3a3f5-354c-4f60-8aca-dc687f417ec6" />
<img width="1920" height="1080" alt="IMG_20261016_114704" src="https://github.com/user-attachments/assets/6888ed2f-111a-4e1c-a8bf-ad02ef59f841" />
<img width="1920" height="1080" alt="IMG_20261016_114657" src="https://github.com/user-attachments/assets/eef5eb30-1ad2-462f-b558-a92f30d9c565" />
<img width="1920" height="1080" alt="IMG_20261016_114638" src="https://github.com/user-attachments/assets/d0befe55-5804-452e-9255-56145cd56a0d" />
<img width="1920" height="1080" alt="IMG_20261016_114630" src="https://github.com/user-attachments/assets/09e9180b-fde3-4d27-87ec-14cb59a1dd36" />

