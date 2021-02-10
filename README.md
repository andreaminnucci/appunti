### Guide formattazione file README.txt

[Link 1](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
[Link 2](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Comandi GIT

All'interno della cartella nella quale creare il repository locale git (contenitore dove mettere tutti i file), eseguire:
```
git init

```

Verificare lo stato dei file all'interno della cartella.
Serve per controllare localmente se ci sono delle operazioni da fare, ci dice lo stato del repository.
E consigliabile eseguire questo comando prima di fare uan qualsiasi operazione.
```
git status

```

Aggiungere tutti i file nuovi e/o modificati nella cartella e sottocartelle.
Permette di far transitare i file dalla working directory alla staging area.
```
git add .
git add filename

```

Committare i file aggiunti e/o modificati
```
git commit -m "Messaggio obbligatorio di commit"
```


Committare i file aggiunti e/o modificati
```
git commit -m "Messaggio obbligatorio di commit"
```

Aggiungere uno username ed email
```
git config --global user.name "username"
git config --global user.email "username@domain"
```


