# teco-docs README
Documentación recopilada sobre los procesos desarrollados en salesforce.

**Links útiles:**
* [Funcionalidad 1](./test/test.md)
* [Funcionalidad 1](./test/test.md)

## Buscar documentación:

* [Funcionalidad 1](../test/test.md)
* [Funcionalidad 2](../test/test.md)

## Colaborar:
* Desde vs code:

```
// Creá un directorio
$ cd mi-carpeta
$ git init
$ git add remote origin https://github.com/dantefilareto/teco-docs.git
$ git fetch
$ git pull origin master

// Creá un archivo .md en tu directorio local
// Utilizá la sintaxis descrita mas abajo
// Añadí las imagenes necesarias al directorio
// Desplegá tus cambios al repositorio remoto
$ git add .
$ git commit -am "doc funcionalidad etc"
$ git push origin master
```

### Sintaxis markdown
-----

**Insertar imágenes:**
```
![](./test/imagen_1.jpg)
```

Resultado:

![](./test/imagen_1.jpg)


**Títulos:**
```
# Título 1
## Título 2
### Título 3
```

Resultado:

# Título 1
## Título 2
### Título 3

**Regla horizontal:**
```
Párrafo 1
_______
Párrafo 2
```

Resultado:

Párrafo 1
_______

Párrafo 2

**Frases:**
```
> Lorem ipsum  
> Dolor sit amet
```

Resultado:
> Lorem ipsum  
> Dolor sit amet

**Todos los comandos [Acá](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)**