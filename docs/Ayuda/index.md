# modificar la pagina
## preparativos

```
apt-get install git
pip install mkdocs
```


## clonar de github

```
git clone https://github.com/knyete/knyete.github.io.git


```

## editarlo
trabajar haciendo carpetas y markdowns en la carpeta 'docs'
```
code knyete.github.io
mkdocs serve
```

## publicar
con 
- username: knyete
- password : ****

```

mkdocs gh-deploy


```

y guardar el fuente
```

git add . && git commit -m "mrr $(date)" && git push -u --all;


```
todos los menus los va creando el programa solo

[mas informacion mkdocs](https://www.mkdocs.org/)