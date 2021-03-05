### Guide formattazione file README.txt

- [Link 1](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
- [Link 1](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
- [Link 2](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


### Comandi GIT

Memorizzare le credenziali

```
vim ~/.git-credentials
--> https://USER:PASS@github.com
```

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



### Risose tutorial Java, Spring
- [https://github.com/thombergs](https://github.com/thombergs)
- [Design Pattern Tutorial](https://www.tutorialspoint.com/design_pattern)
- [https://loizenai.com/](https://loizenai.com)
- [Java Tutorials](https://howtodoinjava.com)
- [Video Corsi Java, C++11 STL, Python, OOP, Visual Studio C#, Basi di dati, HTML, CSS, Javascript, Sistemi Operativi](https://www.youtube.com/channel/UC5_j0dmvXE0xs6ra-clGz4A)
- [Java67](https://www.java67.com)
- [JavaSterling](https://javasterling.com)
- [Java Technology and Beyond](https://javatechonline.com)
- [Baeldung](https://baeldung.com)
- [Javarevisited](https://javarevisited.blogspot.com)
- [italianCoders](https://italiancoders.it)
- [Lo Sviluppatore](http://losviluppatore.it)
- [Z Koder](https://bezkoder.com)
- [Making Java easy to learn](https://javatechonline.com)
- [SpringHow](https://springhow.com)
- [JavaGuides](https://www.javaguides.net)

### Progetti Interessanti
- [Free Book](https://ebookfoundation.github.io/free-programming-books/books/free-programming-books-it.html#database)
- [Shopizer Ecommerce source code Spring Boot](https://github.com/shopizer-ecommerce/shopizer)
- [RameshMF](https://github.com/RameshMF)
- [In 28 minutes](https://github.com/in28minutes)

![2021 Java Developer RoadMap](2021_Java_Developer_RoadMap.png)
