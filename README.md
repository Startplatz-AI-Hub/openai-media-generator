# 🎨 OpenAI Media Generator

**Live Demo:** [Your GitHub Pages URL will be here]

---

## 🚀 Schnell-Setup für GitHub Pages

### 1️⃣ Repository erstellen
1. Gehe zu [github.com/new](https://github.com/new)
2. Repository Name: z.B. `openai-media-generator`
3. Public (für GitHub Pages erforderlich bei Free Plan)
4. **NICHT** "Initialize with README" ankreuzen
5. `Create repository`

### 2️⃣ Code hochladen
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

### Videoerzeugung (sora-2 / sora-2-pro)
- ✅ 4, 8 oder 12 Sekunden
- ✅ Verschiedene Auflösungen (1280x720, 1920x1080, etc.)
- ✅ Echtzeit-Fortschrittsanzeige
- ✅ Download als MP4

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

---

## 🎨 STARTPLATZ Branding

Diese App nutzt das **STARTPLATZ AI HUB** Corporate Design:
- **Fonts:** Matterhorn
- **Colors:** Orange (#FF7A00) & Schwarz (#000000)
- **Style:** Modern, professionell, clean

---

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

