# 🌐 ProfilX – Dein digitales Profil zum Mitnehmen

**ProfilX** ist eine minimalistische Web-App, mit der du dein persönliches digitales Profil erstellen, teilen und durch innovative Technologien wie QR-Code oder NFC-Armband überall zugänglich machen kannst.

---

## 🚀 Ziel der Anwendung

ProfilX hilft Menschen, sich auf charmante und persönliche Weise vorzustellen – egal ob zum Freunde finden, Netzwerken oder einfach, um einen bleibenden Eindruck zu hinterlassen.

---

## 🧩 Funktionen

- **Benutzerregistrierung & Login**
- **Individuelle Profilgestaltung**
  - Text, Bilder, Seitenanzahl frei wählbar
- **Öffentliche Profilseite per URL aufrufbar**
- **Nachrichtenfunktion (bald serverseitig via Raspberry Pi)**
- **Scanbar per NFC oder QR-Code**
- **PWA-fähig (installierbar auf Mobilgeräten)**
- **Responsive Design für alle Bildschirmgrößen**

---

## 🔧 Technischer Aufbau

- **Frontend:** HTML, CSS, JavaScript
- **Deployment:** [Netlify](https://www.netlify.com/)
- **Geplant (Backend):** Raspberry Pi als lokaler Node.js/PHP-Server für Nachrichtenempfang & Account-Verwaltung

---

## 📁 Projektstruktur

```bash
📦 ProfilX
├── 📁 img             # Bilder und Icons
├── 📁 css             # Stylesheets
├── 📁 js              # Später: JavaScript-Dateien
├── 📄 index.html      # Startseite
├── 📄 start.html      # Willkommen
├── 📄 profil.html     # Persönliches Profil
├── 📄 weiter.html     # Folge-Seite
├── 📄 kontakt.html    # Nachrichtenformular
├── 📄 impressum.html  # Rechtliches
├── 📄 manifest.json   # PWA-Unterstützung
└── 📄 README.md       # Dieses Dokument
