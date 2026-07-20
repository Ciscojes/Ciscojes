# Instrucciones para actualizar tu perfil de GitHub

Este paquete está preparado para el repositorio de perfil:

```text
git@github.com:Ciscojes/Ciscojes.git
```

## Opción 1: clonar el repositorio existente

Abre una terminal en la carpeta donde quieras trabajar y ejecuta:

```bash
git clone git@github.com:Ciscojes/Ciscojes.git
cd Ciscojes
```

Extrae el contenido de este ZIP y copia dentro del repositorio:

```text
README.md
certificados/
```

Después ejecuta:

```bash
git status
git add README.md certificados/
git commit -m "Actualiza perfil profesional y agrega certificaciones"
git push origin main
```

## Opción 2: reemplazar el contenido local

Si ya tienes el repositorio clonado:

```bash
cd ruta/del/repositorio/Ciscojes
```

Copia `README.md` y la carpeta `certificados` dentro del repositorio.

Luego:

```bash
git status
git add .
git commit -m "Actualiza README profesional y certificaciones"
git push origin main
```

## Si la rama principal se llama master

Compruébalo con:

```bash
git branch
```

Si aparece `master`, usa:

```bash
git push origin master
```

## Verificar el resultado

Visita:

```text
https://github.com/Ciscojes
```

GitHub mostrará automáticamente el README del repositorio `Ciscojes/Ciscojes` en tu perfil.
