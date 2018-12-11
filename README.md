# VCS: Git

## Cos'è
"Il controllo versione (versioning), in informatica, è la gestione di versioni multiple di un insieme di informazioni. Gli strumenti software per il controllo versione sono ritenuti molto spesso necessari per la maggior parte dei progetti di sviluppo software. La cronologia di Wikipedia è un esempio di sistema di controllo versione. (cfr. https://it.wikipedia.org/wiki/Controllo_versione)"

## Cos'è: repository
Si tratta di una directory digitale o spazio di archiviazione in cui è possibile accedere al progetto, ai suoi file e a tutte le versioni dei suoi file salvate da Git. Esempio: [repository](https://github.com/serenasensini/FZTH-Angular6)

## Cos'è: branch
Un branch in Git è semplicemente un puntatore ad un ramo della versione di commit. Il nome del ramo predefinito in Git è master. Ogni volta che si committa, si sposta automaticamente in avanti il puntatore.

![storia dei commit repository](https://etrivinos.files.wordpress.com/2016/01/ramas-historicas.png?w=620)

## Getting started

### Installazione su Windows
[Link](https://gitforwindows.org/)

### Installazione su Linux
[Link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Installazione su MacOS
[Link](https://git-scm.com/download/mac)

## Comandi: init
Per creare un nuovo repository a partire da una directory locale, si usa il comando:
`git init`

## Comandi: clone
Per clonare un repository presente su GitHub.com si usa il comando:
`git clone /path/to/repo`

## Comandi: add
Per proporre il salvtaggio delle modifiche nel repository, si usa il comando:
`git add file1 file2 file3 ...`

Per salvare __tutti__ i file presenti nella cartella, si usa il comando:
`git add *`

## Comandi: commit
Per committare le modifiche (aggiungendo un messaggio che ne spieghi i cambiamenti), si usa il comando:
`git commit -m "message here"`

## Comandi: push
Per salvare le modifiche sul repository, si usa il comando:
`git push origin master`
dove __master__ rappresenta il branch principale del repository, e __origin__ la cartella corrente.

## Comandi: pull
Per prendere le modifiche dal repository e salvarle in locale, si usa il comando:
`git add remote origin path/to/repo`
dove __origin__ è la cartella corrente.

## Comandi: merge
La fusione è il modo di Git di rimettere insieme modifiche sullo stesso file. Si usa il comando: 
`git merge`
