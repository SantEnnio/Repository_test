# Intro gentile a Git per Unity
Git: software per il versionamento e la condivisione di file

- Condividiamo versioni di una cartella su disco
    - locale: commit
    - remoto: push

## Client git:
https://desktop.github.com/
https://git-fork.com/

## Glossario:
- Repository: cartella versionata, può essere locale, oppure remota
- Commit: è la "fotografia" dello stato delle modifiche ad una cartella.
    - add file
    - remove file
    - edit file
- Branch: ramificazione dei commit per modifiche potenzialmente distruttive
- Push: invio delle commit (NON DEI FILE) su una repository online
- Clone: collegamento di una repository online su repository locale
- Fetch: recupera tutti gli aggiornamenti da una repository online
- Pull: recupero i dati della repository online e li inserisco nella mia repo locale
- Merge: fusione tra due o più commit
    - Caso ottimale: i collaboratori hanno modificato dei file diversi tra loro
    - Caso OK: i collaboratori hanno modificato due parti dello stesso file
    - Conflict: i collaboratori modificano le stesse sezioni dello stesso file, i conflitti vanno gestiti.
- .gitignore: scegliere quali file ignorare all'interno della cartella

## Git + UNITY
.gitignore ignora le cartelle Library, Temp, Build, Logs...
* Step 1: creazione della repository online (template Unity)
* Step 2: clone della repository in locale
* Step 3: creazione del progetto Unity
* Step 4: root del progetto Unity -> root della repository
* Step 5: first commit -> push 
