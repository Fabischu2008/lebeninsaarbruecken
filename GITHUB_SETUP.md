# GitHub Setup Anleitung

## Repository auf GitHub erstellen

1. **Gehe zu GitHub.com** und logge dich ein
2. **Klicke auf "New repository"** (oder gehe zu: https://github.com/new)
3. **Repository-Name:** z.B. `leben-in-saarbruecken` oder `saarbruecken-website`
4. **Beschreibung:** "Website für Saarbrücken als attraktiver Lebensort - Uni-Projekt Digital Media Marketing"
5. **Sichtbarkeit:** Wähle Public oder Private (je nach Präferenz)
6. **WICHTIG:** Lass alle Checkboxen UNANGEHAKET (kein README, keine .gitignore, keine License - wir haben das schon!)
7. **Klicke auf "Create repository"**

## Lokales Repository mit GitHub verbinden

Nachdem du das Repository auf GitHub erstellt hast, führe diese Befehle aus:

```bash
# Füge das GitHub-Repository als Remote hinzu
git remote add origin https://github.com/DEIN-USERNAME/DEIN-REPO-NAME.git

# Benenne den Branch zu 'main' um (falls nötig)
git branch -M main

# Pushe deinen Code zu GitHub
git push -u origin main
```

**Beispiel:**
```bash
git remote add origin https://github.com/fabianschuck/leben-in-saarbruecken.git
git branch -M main
git push -u origin main
```

## GitHub Pages aktivieren (Optional - für Live-Website)

1. Gehe zu deinem Repository auf GitHub
2. Klicke auf **Settings** (oben rechts)
3. Scrolle zu **Pages** (links im Menü)
4. Unter **Source** wähle: **Deploy from a branch**
5. Wähle Branch: **main** und Folder: **/ (root)**
6. Klicke auf **Save**
7. Deine Website ist dann unter verfügbar: `https://DEIN-USERNAME.github.io/DEIN-REPO-NAME/`

## Weitere nützliche Git-Befehle

```bash
# Status anzeigen
git status

# Änderungen hinzufügen
git add .

# Commit erstellen
git commit -m "Deine Commit-Nachricht"

# Zu GitHub pushen
git push

# Letzte Änderungen von GitHub holen
git pull
```

## Repository-Struktur

```
lebeninsaarbruecken/
├── .gitignore          # Git-Ignore-Datei
├── README.md          # Projekt-Dokumentation
├── GITHUB_SETUP.md    # Diese Datei
├── index.html         # Haupt-HTML-Datei
├── styles.css         # Stylesheet
└── script.js          # JavaScript-Datei
```

## Nächste Schritte

1. ✅ Repository auf GitHub erstellen
2. ✅ Code hochladen
3. ✅ (Optional) GitHub Pages aktivieren
4. ✅ Tracking-IDs in index.html eintragen
5. ✅ Marketing-Kampagnen starten!

Viel Erfolg! 🚀

