
# 🤖 Eishockey-Bot – Autonomer Robotergegner für Tischspiel

Ein technisches DIY-Projekt zur Entwicklung eines autonomen Roboters, der als Gegenspieler bei einem physischen Eishockey-Tischspiel agiert. Der Bot erkennt Spielbewegungen mit einer Kamera und steuert Spielfiguren über Motoren – alles auf Basis von Computer Vision und KI.

---

## 🔧 Projektziele

- Bau eines autonom spielenden Gegners für ein Mini-Eishockeyspiel (ähnlich Tischfußball)
- Einsatz von Kamera und KI zur Erkennung von Puck und Spielfiguren
- Steuerung über Motoren für Dreh- und Schiebebewegungen
- Rechenplattform: NVIDIA Jetson Nano oder vergleichbarer Einplatinencomputer
- Budget: max. 250 CHF

---

## 🧠 Technologien

- **Python** & **OpenCV** für Bildverarbeitung
- **YOLOv5/YOLOv8** für Objekterkennung
- **Jetson Nano** für Onboard-KI
- **Servomotoren / Stepper** für Bewegungssteuerung
- **Git** für Versionskontrolle

---

## 📁 Projektstruktur

```
eishockeybot/
├── docs/               → Projektbeschreibung & Dokumentation
├── hardware/           → Motorsteuerung, technische Zeichnungen
├── models/             → KI-Modelle & Trainingsdaten
├── notebooks/          → Trainings- & Analysetools
├── scripts/            → Code für Steuerung, Vision, Logik
├── config/             → Konfigurationsdateien
├── test/               → Tests & Kalibrierungsskripte
├── media/              → Beispielbilder & Videos
├── requirements.txt    → Python-Abhängigkeiten
├── setup.sh            → Installationsskript
├── .gitignore
└── README.md
```

---

## 🚀 Schnellstart

1. Repository klonen:

```bash
git clone https://github.com/dein-benutzername/eishockeybot.git
cd eishockeybot
```

2. Abhängigkeiten installieren (auf Jetson Nano oder Linux-PC):

```bash
pip install -r requirements.txt
```

3. Kamera-Setup testen:

```bash
python scripts/camera.py
```

4. Modell laden & Bildverarbeitung starten:

```bash
python scripts/vision.py
```

---

## 📸 Beispiel

| Kameraansicht | Erkennung |
|---------------|-----------|
| ![camera](media/samples/camera_view.jpg) | ![detect](media/samples/vision_detected.jpg) |

---

## 🧪 TODO

- [ ] Python & OpenCV lernen und testen
- [ ] Webcam kaufen (Logitech C270)

---


## ✉️ Kontakt

Fragen, Ideen oder Beiträge?  
**Lionel Schoch** – [GitHub-Profil](https://github.com/lioschoch)
