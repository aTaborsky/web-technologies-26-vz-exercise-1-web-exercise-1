# Git & Terminal Commands
> Meine persönliche Befehlssammlung für PROG II - SoSe 2026

---

## Navigation (PowerShell)
```powershell
pwd                          # zeigt wo du gerade bist
ls                           # zeigt Inhalt des Ordners
cd Ordnername                # in Ordner wechseln
cd ..                        # einen Ordner zurück
New-Item dateiname.md        # neue Datei erstellen
```

---

## Git Basics
```bash
git status                   # was hat sich geändert?
git pull                     # neueste Version von GitHub holen
git push                     # eigene Änderungen hochladen
```

---

## Branches
```bash
git branch                           # welche Branches gibt es?
git checkout branchname              # zu Branch wechseln
git checkout -b branchname           # neuen Branch erstellen UND reinwechseln
git push -u origin branchname        # neuen Branch auf GitHub hochladen
```

---

## Änderungen speichern
```bash
git add .                            # alle Änderungen einpacken
git commit -m "was ich gemacht hab"  # Änderungen mit Nachricht speichern
git push                             # auf GitHub hochladen
```

---

## Der tägliche Rhythmus
```bash
git pull               # 1. IMMER zuerst!
# ... coden ...
git add .              # 2. einpacken
git commit -m "..."    # 3. speichern
git push               # 4. hochladen
```

---

## Maven (im Terminal)
```bash
mvn compile            # Projekt kompilieren
mvn test               # Tests ausführen
mvn clean              # Build-Ordner aufräumen
mvn package            # Projekt als JAR packen
```

---

## Projekt Setup (einmalig)
```bash
git clone URL                        # Repo herunterladen
git checkout -b exercise-01          # neuen Branch erstellen
git push -u origin exercise-01       # Branch auf GitHub hochladen
```

---

> Zuletzt aktualisiert: 10.03.2026
> Wird laufend ergänzt!
