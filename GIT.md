# Git
Software per il versionamento e la condivisione di file
Un tonno dei miei
- Condividiamo versioni di una cartella su disco
    - locale: commit
    - remoto: push
Questa non è Ibiza
# Client git:

https://desktop.github.com/
https://git-fork.com/

# Glossario:
- Repository: cartella versionata
- Commit: stato delle modifiche ad una cartella:
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
    - Conflict: i collaboratori modificano le stesse sezioni dello stesso file
