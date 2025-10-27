# 🎨 OpenAI Media Generator

---

## 🚀 Schnell-Setup für GitHub Pages

### 1️⃣ Repository erstellen
1. Gehe zu [github.com/new](https://github.com/new)
2. Repository Name: z.B. `openai-media-generator`
3. Public (für GitHub Pages erforderlich bei Free Plan)
4. **NICHT** "Initialize with README" ankreuzen
5. `Create repository`

### 2️⃣ Code hochladen

**⚠️ WICHTIG - Vor dem Upload:**
Ändere das Standard Admin-Passwort in `index.html` (Zeile ~1463):
```javascript
const DEFAULT_ADMIN_PASSWORD = 'admin123'; // ← ÄNDERE DIES!
```

Dann:
```bash
cd openai-media-generator-github-pages
git init
git add .
git commit -m "Initial commit: OpenAI Media Generator"
git branch -M main
git remote add origin https://github.com/DEIN-USERNAME/openai-media-generator.git
git push -u origin main
```

### 3️⃣ GitHub Pages aktivieren
1. Gehe zu deinem Repository auf GitHub
2. `Settings` → `Pages` (linkes Menü)
3. **Source:** `Deploy from a branch`
4. **Branch:** `main` → `/root` → `Save`
5. ⏳ Warte 1-2 Minuten
6. 🎉 Deine URL erscheint: `https://DEIN-USERNAME.github.io/openai-media-generator/`

---

## ✅ Das war's!

Deine App ist jetzt live unter:
**`https://DEIN-USERNAME.github.io/openai-media-generator/`**

---

## 🔑 User-Anleitung

### So nutzen deine User die App:

1. **Öffne die deployed Website**
2. **Gib deinen OpenAI API Key ein**
   - Erhalte deinen Key auf: [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
3. **Wähle:** Bild oder Video Generation
4. **Prompt eingeben** → `Generieren` klicken
5. **Fertig!** 🎉

---

## 🎯 Features

### Bilderzeugung (gpt-image-1)
- ✅ Verschiedene Bildgrößen (1024x1024, 1536x1024, 1024x1536)
- ✅ Mehrere Bilder gleichzeitig (bis zu 10)
- ✅ Download als PNG

### 👁️ Bildanalyse (Vision - gpt-4.1-mini)
- ✅ **NEU**: Bilder analysieren und verstehen
- ✅ Bild-URL oder Upload unterstützt
- ✅ Detail-Level einstellbar (low/high/auto)
- ✅ Stellt Fragen zu Bildinhalten
- ✅ Erkennt Text, Objekte, Farben, Szenen

### Videoerzeugung (sora-2 / sora-2-pro)
- ✅ 4, 8 oder 12 Sekunden
- ✅ **Preise (offiziell 2025):**
  - sora-2: $0.10/Sekunde (720p)
  - sora-2-pro: $0.30/Sekunde (720p) | $0.50/Sekunde (1024p/1792p)
- ✅ Verschiedene Auflösungen:
  - 720x1280 / 1280x720 (HD Portrait/Landscape)
  - 1024x1792 / 1792x1024 (High-Res - nur sora-2-pro)
- ⚠️ **Input Reference deaktiviert** (noch nicht von OpenAI API unterstützt)
- ✅ Echtzeit-Fortschrittsanzeige
- ✅ Download als MP4

### 🎞️ Video Remix
- ✅ **NEU**: Bestehende Videos mit neuem Prompt remixen
- ✅ Erweitert oder verändert existierende Videos
- ✅ Nutzt Video-ID von vorherigen Generierungen

### 💰 Kosten-Tracking
- ✅ **NEU**: Echtzeit-Kostenberechnung für jede Anfrage
- ✅ Session-Gesamt-Übersicht
- ✅ Transparente Preis-Details
- ✅ Basierend auf offiziellen OpenAI-Preisen (2025)

**Beispiel-Kosten:**
- 1x Bild (1024x1024): $0.04
- Bildanalyse (gpt-4.1-mini): ~$0.0001-0.001 (je nach Tokens)
- Video 8s (sora-2, 720p): $0.80
- Video 8s (sora-2-pro, 720p): $2.40
- Video 8s (sora-2-pro, 1792p): $4.00

### 🔐 Admin-Panel (NEU!)
- ✅ **Passwortgeschützt** - Sichere Admin-Authentifizierung
- ✅ **Feature-Toggles** - Einzelne Features aktivieren/deaktivieren
- ✅ **🔐 Feature-Passwortschutz** - Jedes Feature mit eigenem Passwort schützen (optional)
- ✅ **⏰ Öffnungszeiten** - Zeitbasierte Zugriffsbeschränkung (z.B. 08:00-17:00 Uhr)
- ✅ **🎬 Video-Management** - Alle Videos aus OpenAI API laden & verwalten
- ✅ **Nutzungsstatistiken** - Tracking von Requests & Kosten
- ✅ **Custom Nachrichten** - Individuelle Sperrnachrichten
- ✅ **Log-Export** - Exportiere Logs als Textdatei
- ✅ **Passwort-Verwaltung** - Sicheres Ändern des Admin-Passworts
- ✅ **Keyboard Shortcut** - Zugriff via `Ctrl+Shift+A`

**Standard-Passwort:** `admin123` (bitte beim ersten Login ändern!)

**Neu: Feature-Passwortschutz**
- Jedes Feature (Bilder, Vision, Videos, Remix) kann mit eigenem Passwort geschützt werden
- Nutzer müssen Passwort eingeben, bevor sie das Feature nutzen können
- Passwort bleibt für die Session gültig (einmalige Eingabe)
- Ideal für kostspiele Features wie Video-Generierung!

### Weitere Features
- ✅ **Media Gallery** - Historie aller generierten Medien
- ✅ **Direct API Connection** - Keine Timeouts!
- ✅ **BYOK** (Bring Your Own Key) - Sicher & transparent
- ✅ **Modern UI** - STARTPLATZ AI HUB Design
- ✅ **Responsive** - Funktioniert auf allen Geräten

---

## 🔐 Sicherheit

- ✅ **Keine Server-Speicherung** - API Keys bleiben im Browser
- ✅ **Optional LocalStorage** - Key im Browser speichern
- ✅ **Direct API Calls** - Keine Zwischenstationen
- ✅ **Open Source** - Vollständig transparent

---

## 💡 Vorteile von GitHub Pages

- ✅ **Kostenlos** - Für Public Repositories
- ✅ **Schnell** - Global CDN
- ✅ **Einfach** - Push = Auto-Deploy
- ✅ **Zuverlässig** - 99.9% Uptime
- ✅ **HTTPS** - Automatisches SSL-Zertifikat
- ✅ **Custom Domain** - Eigene Domain möglich

## 📦 Enthaltene Dateien

```
openai-media-generator-github-pages/
├── index.html       (Die komplette App - 70 KB Standalone!)
├── .nojekyll        (Deaktiviert Jekyll Processing)
├── .gitignore       (Git ignore rules)
└── README.md        (Diese Anleitung)
```

**Das war's! Keine `node_modules`, keine Build-Steps, keine Server-Konfiguration!** 🎉

---

## 🔄 Updates deployen

Bei Änderungen einfach:
```bash
git add .
git commit -m "Update: Beschreibung der Änderung"
git push
```

GitHub Pages deployt automatisch neu! 🚀

---

## 🔐 Admin-Panel Nutzung

### Zugang
1. **Button** - Klicke auf das ⚙️ Icon unten rechts
2. **Shortcut** - Drücke `Ctrl+Shift+A`

### Erste Schritte
1. **Login** mit Standard-Passwort: `admin123`
2. **Passwort ändern** - Gehe zu "🔑 Passwort ändern"
3. **Features steuern** - Toggle Features an/aus

### Feature-Steuerung

**Video-Funktion sperren:**
1. Admin-Panel öffnen
2. Bei "🎬 Videoerzeugung" den Toggle ausschalten
3. Nutzer sehen jetzt eine Sperrnachricht

**Feature mit Passwort schützen:**
1. Admin-Panel öffnen
2. Feature aktiviert lassen (Toggle auf ON)
3. Unter dem Feature erscheinen Passwort-Einstellungen
4. Checkbox "🔐 Passwortschutz aktivieren" anklicken
5. Passwort eingeben (min. 4 Zeichen)
6. "💾 Speichern" klicken
7. **Nutzer müssen jetzt das Passwort eingeben, bevor sie das Feature nutzen können!**

**Beispiel-Szenario:**
- Bilder: Für alle frei (kein Passwort)
- Bildanalyse: Passwortgeschützt mit "vision123"
- Videos: Passwortgeschützt mit "video456"
- Remix: Komplett deaktiviert

**Hinweise:**
- Passwort-Eingabe erfolgt einmalig pro Session
- Nach korrekter Eingabe bleibt Feature für die Session freigeschaltet
- Bei neuem Browser-Tab muss Passwort erneut eingegeben werden
- Admin kann verschiedene Passwörter für jedes Feature setzen

**Custom Nachricht setzen:**
1. Unter "💬 Sperrnachricht" eigene Nachricht eingeben
2. "💾 Nachricht speichern" klicken
3. Diese Nachricht sehen Nutzer bei gesperrten Features (nicht bei passwortgeschützten!)

### Statistiken

Das Admin-Panel zeigt dir:
- **Anzahl generierter Bilder**
- **Anzahl Bildanalysen**
- **Anzahl generierter Videos**
- **Anzahl Video Remixes**
- **Gesamt-Kosten** aller Requests

**Statistiken zurücksetzen:**
- Button "🔄 Statistiken zurücksetzen" klicken
- Bestätigung erforderlich

### Logs exportieren

1. Button "📥 Logs exportieren" klicken
2. Textdatei wird heruntergeladen
3. Enthält alle Log-Einträge mit Timestamps

### ⏰ Öffnungszeiten einrichten

**Aktivieren:**
1. Admin-Panel öffnen
2. Unter "⏰ Öffnungszeiten" den Toggle aktivieren
3. Einstellungen erscheinen automatisch

**Konfigurieren:**
1. **Start-Zeit** eingeben (z.B. 08:00)
2. **End-Zeit** eingeben (z.B. 17:00)
3. **Custom Nachricht** für außerhalb der Zeiten
4. "💾 Öffnungszeiten speichern" klicken

**Funktion:**
- App ist NUR während der eingestellten Zeiten nutzbar
- Außerhalb der Zeiten: Alle Features sind gesperrt
- Nutzer sehen eine freundliche Nachricht mit den Öffnungszeiten

**Beispiel:**
```
🕐 Außerhalb der Öffnungszeiten

Die App ist nur während unserer Öffnungszeiten 
(08:00 - 17:00 Uhr) verfügbar.

Öffnungszeiten: 08:00 - 17:00 Uhr
```

### 🎬 Video-Verwaltung

**Videos laden:**
1. Admin-Panel öffnen
2. Unter "🎬 Video-Verwaltung" → "🔄 Videos laden"
3. API Key wird verwendet, um alle Videos zu laden

**Was wird angezeigt:**
- **Video-ID** - Eindeutige Kennung
- **Status** - completed, queued, failed
- **Model** - sora-2 oder sora-2-pro
- **Dauer & Größe** - z.B. 8s, 1280x720
- **Prompt** - Erste 100 Zeichen des Prompts

**Aktionen:**
- **⬇️ Download** - Video direkt herunterladen (nur bei completed)
- **📋 Copy ID** - Video-ID in Zwischenablage kopieren
- **↻ Aktualisieren** - Video-Liste neu laden

**Verwendung:**
- Alle generierten Videos überblicken
- Videos nachträglich herunterladen
- Video-IDs für Remix kopieren
- Status von laufenden Jobs prüfen

### Sicherheit

- **Passwort** wird im LocalStorage gespeichert
- **Empfehlung**: Passwort sofort beim ersten Login ändern!
- **Länge**: Mindestens 6 Zeichen
- **Ändern**: Über "🔑 Passwort ändern" im Admin-Panel

---

## 🆘 Troubleshooting

### Problem: "404 Page not found"
- ✅ Warte 2-3 Minuten nach dem ersten Deploy
- ✅ Check: Settings → Pages → Branch ist auf `main` / `root` gesetzt
- ✅ Force-Refresh: `Ctrl + F5` (Windows) / `Cmd + Shift + R` (Mac)

### Problem: "API Key funktioniert nicht"
- ✅ Check: Key beginnt mit `sk-proj-`
- ✅ Check: Key hat Guthaben auf [platform.openai.com](https://platform.openai.com)
- ✅ Check: Browser-Console auf Fehler prüfen (F12)

### Problem: "Timeouts bei komplexen Prompts"
- ✅ Das ist normal! Die App nutzt jetzt Direct API, aber OpenAI braucht Zeit
- ✅ Komplexe Bilder: 20-30 Sekunden
- ✅ Videos: 2-5 Minuten
- ✅ Browser-Tab offen lassen!

---

## 🌐 Custom Domain (Optional)

Möchtest du eine eigene Domain wie `ai.deine-firma.de`?

1. Erstelle eine `CNAME` Datei im Repository-Root:
   ```
   ai.deine-firma.de
   ```
2. In deinem DNS (bei deinem Domain-Provider):
   ```
   CNAME  ai  DEIN-USERNAME.github.io
   ```
3. GitHub → Settings → Pages → Custom Domain eintragen
4. Fertig! 🎉

---

## 📊 Monitoring & Analytics (Optional)

Du kannst Google Analytics, Plausible oder andere Analytics hinzufügen:

Füge im `<head>` der `index.html` hinzu:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
```

---

## 🤝 Support & Community

- **Issues:** [GitHub Issues](https://github.com/Startplatz-AI-Hub/openai-media-client/issues)
- **OpenAI Docs:** [platform.openai.com/docs](https://platform.openai.com/docs)
- **STARTPLATZ:** [startplatz.de](https://www.startplatz.de)

---

## 📄 Lizenz

MIT License - Feel free to fork, modify, and deploy! 🎉

---

**Viel Erfolg mit deiner deployed App! 🚀🎨**

