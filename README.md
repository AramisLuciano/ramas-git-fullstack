# Aprendiendo Git & Github

## 1. Inicializar el repositorio git (local)

```
git init
```

- este comando permite inicializar el repositorio

Repositorio

## 2. Enviar archivos al area de prepación (index)

```
git add .
```

- enviar todos los archivos modificados

```
git add index.html README.md
```

- seleccionar los archivos

## 3. Enviar archivos al Head, y agregar una descipción al envío de los archivos.

```
git commit -m "proyecto base"
```

# Publicación en Github

- Crear un repositorio en Github

## Asociar el repositorio (local) con el repositorio (remoto) GITHUB

```
git remote add origin https://github.com/AramisLuciano/ramas-git-fullstack.git

```

## Verificar si ya está asoiciado al repositorio remoto

```
git remote -v
```

## Publicar los cambios a GitHub

```
git push origin master
```

## crear una rama

```
git branch
git branch desarrollo

```

## cambiar a la nueva rama

```
git switch desarrollo
git checkout desarrollo

```
