# AR Model Viewer 

Eine erweiterte und optimierte Abwandlung der AR-Demo von [edoardomignano](https://github.com/edoardomignano/ar-demo). Diese Version wurde um eine cloudbasierte Upload-Infrastruktur, automatisierte QR-Code-Generierung und eine intelligente Empfänger-Landingpage für Direkt-Downloads erweitert.

Ein leichtgewichtiger, webbasierter 3D-Modell-Viewer mit Augmented Reality (AR) Unterstützung. Lade deine `.glb`-Dateien hoch, betrachte sie im Browser und teile sie per Link mit anderen.

---

## Features

* **3D Viewer:** Interaktive Ansicht von Modellen (Rotation, Zoom, Fullscreen).
* **AR-Modus:** Betrachte Modelle in deiner echten Umgebung (unterstützt WebXR, Scene-Viewer und Quick-Look).
* **Cloud-Upload:** Automatischer Upload zu Litterbox (Catbox). Erzeugt einen teilbaren Link, der 24 Stunden gültig ist.
* **Smart Receiver Workflow (Direkt-Download):** Der erzeugte Link startet beim Empfänger sofort einen automatischen Hintergrund-Download der `.glb`-Datei auf das Endgerät (inkl. automatischem Zeitstempel-Dateinamen). Zusätzlich erhält der Empfänger einen Button, um das Modell mit einem Klick direkt im Browser-AR zu öffnen.
* **Mobile Ready:** Optimiert für Smartphones und Tablets.
* **Deep Linking:** Parameter-Unterstützung (`?model=URL`), um Modelle direkt über die URL zu laden.

---

## Technologien

* **Frontend:** HTML5, CSS3, JavaScript (ES6+).
* **3D Rendering:** Google Model-Viewer.
* **Hosting/API:** Externer Dienst für temporäres Asset-Hosting.

---

## Installation & Nutzung

Da es sich um eine reine Client-seitige HTML-Datei handelt, ist keine Installation notwendig:

1. **Klone das Repository:**
   ```bash
   git clone [https://github.com/DEIN-BENUTZERNAME/ar-model-viewer.git](https://github.com/DEIN-BENUTZERNAME/ar-model-viewer.git)
