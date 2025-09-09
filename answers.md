# Antworten

**1. Was ist der Unterschied zwischen Working Directory, Staging Area und Repository?**  
- Working Directory: dein Projektordner, wo du Dateien bearbeitest  
- Staging Area: Bereich, in dem du Änderungen für den nächsten Commit vormerkst (`git add`)  
- Repository: die Datenbank mit allen Commits (im `.git`-Ordner)  

**2. Woran erkennst du, ob ein Merge Fast-Forward war?**  
- Ausgabe von `git merge` zeigt „Fast-forward“  
- Kein zusätzlicher Merge-Commit im Log  

**3. Warum kann `git merge --ff-only` manchmal fehlschlagen?**  
- Wenn `main`/`master` neue Commits hat, die nicht im Feature-Branch sind  

**4. Was ist der Vorteil, Änderungen zuerst auf einem Branch wie dev zu machen?**  
- Saubere Trennung: `main` bleibt stabil, Entwicklung passiert auf `dev`  

**5. Mit welchem Befehl siehst du den aktuellen Branch?**  
`git branch` oder `git status`  

**6. Mit welchen Befehlen machst du Änderungen sichtbar und dauerhaft?**  
`git add <datei>` → Staging  
`git commit -m "Nachricht"` → dauerhaft ins Repository
