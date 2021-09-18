# P3.4 Minimizando mis ficheros CSS

Como corolario a este apartado hemos propuesto varias herramientas que nos van a permitir minimizar nuestros ficheros CSS

* sass
* css-minify
* uglifycss

### Sass

Si queremos minimizar con Sass debemos ejecutar la siguiente orden.

```sh
    sass --style=compressed file.css file.min.css
```

### css-minify

Si queremos minimizar con css-minify debemos ejecutar la siguiente orden.

```sh
    css-minify -f file.css
```

Creará el fichero minimizado en la carpeta css-dist.
### uglifycss

Si queremos minimizar con uglifycss debemos ejecutar la siguiente orden.

```sh
    uglifycss file.css > file.min.css
```


Curso desarrollado por @pekechis para @openwebinars