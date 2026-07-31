# Aprendiendo Git & Github

## 1. Inicializar el repositorio git (local)

```bash
git init
```

- este comando permite inicializar el repositorio

Repositorio

## 2. Enviar archivos al area de prepación (index)

```bash
git add .
```

- enviar todos los archivos modificados

```bash
git add index.html README.md
```

- seleccionar los archivos

## 3. Enviar archivos al Head, y agregar una descipción al envío de los archivos.

```bash
git commit -m "proyecto base"
```

# Publicación en Github

- Crear un repositorio en Github

## Asociar el repositorio (local) con el repositorio (remoto) GITHUB

```bash
git remote add origin https://github.com/AramisLuciano/ramas-git-fullstack.git

```

## Verificar si ya está asoiciado al repositorio remoto

```bash
git remote -v
```

## Publicar los cambios a GitHub

```bash
git push origin master
```

## crear una nueva rama

```bash
git branch
git branch desarrollo

```

## cambiar a la nueva rama

```bash
git switch desarrollo
git checkout desarrollo

```
