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


Comando per annullare le ultime modifiche fatte, per rimuovere dallo staging i file.
```
git rm --cached <file>...
```


Comando che permette di salvare le modifiche nel repository locale.
Questo comando è come se fosse un checkpoint: indicher
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


La prima volta occorrerà collegare il repository locale ad un repository remoto
```
git remote add origin https://github.com/....
git branch -M master
git push -u origin master
```



Portarà tutte le modifiche presenti su tutti i commit in remoto:
```
git push 
```